# Developer Training

## Students

| Number | Discord Id    | Progress               | Ghpages Index          |
|:------ |:------------- |:---------------------- |:---------------------- |
| 00     |               | Completed Lesson       |                        |
| 01     | Coranos#4281  | Completed Lesson Four  |[coranos.github.io]     |
| 02     | Mayrapina#9547| Completed Lesson Two   |[mayrapina007.github.io]|
| 03     | not_idol#3950 | Completed Lesson Four  |[not-idol.github.io]    |
| 04     | Lee#2040      | Completed Lesson Two   |[acidlee.github.io]     |
| 05     | Parvu#7388    | Completed Lesson Three |[parvulitum.github.io]  |
| 06     | Monachita#2427| Completed Lesson one |[Monachita.github.io]   |

[coranos.github.io]: https://coranos.github.io/
[mayrapina007.github.io]: https://mayrapina007.github.io/
[not-idol.github.io]: https://not-idol.github.io/
[acidlee.github.io]: https://not-idol.github.io/
[parvulitum.github.io]: https://Parvulitum.github.io/

## Lesson One, Github and Atom.

1) Go to https://github.com and create an account.

*You must enter the aforementioned link, place your data, register and then verify your email to have your account 100% active

2) Go to https://git-scm.com/downloads and download git.

*Enter the download link, proceed to download it and install the GIT on your computer.

3) Go to https://atom.io/ and download atom (it is a editor).

*For atom we will perform the same discharge procedure as the GIT

4) clone https://github.com/coranos/coranos.github.io to your local computer.

*To clone a github we will open our GIT after having installed it and it will give us 3 options CREATE NEW REPOSITORY, CLONE EXISTING REPOSITORY AND OPEN EXISTING REPOSITORY, as it is the first time that we will go to where it says clone existing repository and we will place the address of the github that we want to clone and the address where the cloning process will be saved

*If you are unsure of how to do this, here are the commands to use in *git bash*:
```
cd;
pwd;
mkdir git;
cd git;
git clone https://github.com/coranos/coranos.github.io.git;
git pull;
git push;
```

5) Using the Github Web Page, add your Discord ID to the Student  list.

## Lesson Two, gh-pages.

1) Create a Github Pages site https://pages.github.com/

```
Create a repository
Head over to GitHub and create a new repository named username.github.io, where username is your username (or organization name) on GitHub.
If the first part of the repository doesn’t exactly match your username, it won’t work, so make sure to get it right.
```

2) clone the Github Pages repository to your local computer.

3) Edit the github pages site in atom, locally add your discord id to the top.

## Lesson Three, simple index.html.

1) in your github pages site, add an index.html with the following code:
```
    <!DOCTYPE html>
    <html>
    <meta charset="utf-8" />
    <head>
    <title>Banano</title>
    </head>
    <body onload="onLoad();">
      <div id="banano"></div>
      <script>
          function onLoad () {
            document.getElementById('banano').innerHTML = 'Coranos Bananos';
          }
        </script>
    </body>
    </html>
```
2) update this page with a link to your Github Pages

## Lesson Four, add HTML to your index.html, use CSS.

1) in your github pages site, add an index.css with the following code:

```
.small_image {
  height: 100px;
  width: 100px;
}
```

2) in your github pages site, add an ordered list of images. set the image's width and height to be 100 pixels using CSS classes.
```
<!DOCTYPE html>
<html>
<meta charset="utf-8" />
<head>
<title>Banano</title>
<link rel="stylesheet" type="text/css" href="index.css">
</head>
<body onload="onLoad();">
  <div id="banano"></div>
  <ol>
    <li><img class="small_image" src="https://cdn.discordapp.com/attachments/416341951416369153/473520270309720064/kinderschoko.jpg" /></li>
  </ol>
  <script>
      function onLoad () {
        document.getElementById('banano').innerHTML = 'Coranos Bananos';
      }
    </script>
</body>
</html>
```

### eventually
freelancer amazon-turk fiverr wordpress prestashop opencart joomla magento autotrading-crypto-arbitrage-bot

https://getbootstrap.com/
