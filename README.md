# Reflection & Making a Portfolio

The 16 week long semester is finally over and you have accomplished so much! You learned about problem solving and programming and created a portfolio of programs that demonstrate your competency and along the way you learned and improved your note taking and team work skills.

Our goal is to create an online resume or personal homepage which shows off some of your achievements. Ideally, you will add to this portfolio as you work on school related projects as well as your own personal projects.

If you do not have any experience or knowledge on how to make a web page, this will be your opportunity to learn how to create one. Over time, you can revisit, improve, and customize your web page to make your own personal corner of the Web stand out.

We shall use GitHub's service called [GitHub Pages](https://pages.github.com/) to host your web page in a GitHub repository. We shall use [Markdown](https://en.wikipedia.org/wiki/Markdown) instead of HTML to simplify creating our web pages.


## Background & Motivation

Sharing the fruits of our labor is an important part of the learning process and the mentoring process. To this end, it is beneficial to create our own little corner on the Internet where we can show off some of the cool things you have done.

GitHub is a lot more than just uploading and downloading code.

Consider where you will be in a few years. You may be looking to collaborate with some friends on writing software to address a family business need. Perhaps you will be applying for jobs and they ask you for your GitHub link. Invariably, your name comes up in a conversation and someone Googles your name - up comes your GitHub page. The next thing you know you've got a job iterview, an internship, or that independent study project you wanted to do gets approved.

Consider this as a first draft of what shall be many drafts of your personal home page. On this page, you can share a little bit of information about yourself and some of the topics you are interested in. As your programming skills evolve, you can add and remove projects to show your latest interests and achievements.


## Markdown
We shall start by creating a personal web page using [Markdown](https://en.wikipedia.org/wiki/Markdown) instead of HTML. Markdown is a human readable, lightweight markup language with a syntax that is easy to learn and use. Markdown is the markup language that your instructor uses for all the `README.md` files. The Markdown project's home page is https://daringfireball.net/projects/markdown/.

Everything you need to know can be learned from this Markdown cheat sheet, https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet and by looking at README.md files from past lab assignments. (Even this one!)

Students who are interested in having a page that looks fancier can use [HTML](https://www.w3schools.com/html/), [CSS](https://www.w3schools.com/css/default.asp), [JavaScript](https://www.w3schools.com/js/default.asp), [images](https://wordpress.org/openverse/), etc. however this is not required.

## Step 1: URL and Lab URLs

A _universal resource locator_ or _URL_ is the term we use to identify unique addresses on the World Wide Web. Casually in conversation, we may refer to a URL as a _link_. GitHub's URL or link is http://github.com and CSU Fullerton's is http://fullerton.edu.

Think about your three favorite lab exercises that you completed this semester. Below are the links to each Canvas lab assignment. Bookmark or write down your favorite lab repositories or lab parts. You will need these URLs for the next step.

* [Lab 02](https://csufullerton.instructure.com/courses/3381162/assignments/34485143)
* [Lab 03](https://csufullerton.instructure.com/courses/3381162/assignments/34562947)
* [Lab 04](https://csufullerton.instructure.com/courses/3381162/assignments/34596717)
* [Lab 05](https://csufullerton.instructure.com/courses/3381162/assignments/34609273)
* [Lab 06](https://csufullerton.instructure.com/courses/3381162/assignments/34624315)
* [Lab 07](https://csufullerton.instructure.com/courses/3381162/assignments/34637727)
* [Lab 08](https://csufullerton.instructure.com/courses/3381162/assignments/34650867)
* [Lab 09](https://csufullerton.instructure.com/courses/3381162/assignments/34662067)
* [Lab 10](https://csufullerton.instructure.com/courses/3381162/assignments/34685849)
* [Lab 11](https://csufullerton.instructure.com/courses/3381162/assignments/34697637)
* [Lab 12](https://csufullerton.instructure.com/courses/3381162/assignments/34727919)

## Step 2: Transferring Repositories

If you did not bookmark your favorite repositories in Step 1, please go back and do that before continuing.

The repositories that you used in your course are all owned by your instructor. After the semester is over, the repositories will be archived and then deleted. This means that if you want to save a copy of your work for your portfolio or for next semester, you will need to transfer the repository to your own GitHub account.

Use GitHub's [Importer](https://docs.github.com/en/github/importing-your-projects-to-github/importing-source-code-to-github/importing-a-repository-with-github-importer) to import your lab repositories into your personal GitHub account. GitHub has [instructions posted online](https://docs.github.com/en/github/importing-your-projects-to-github/importing-source-code-to-github/importing-a-repository-with-github-importer) with screenshots to help you navigate how to do it. If you get stuck or need help, ask your instructor or teaching associate for help.

The tricky part starts on _step 6_. This is where you provide your username and password to import your old repository (the one you used for this class) into the new repository (the repository you just created following GitHub's instructions). Attempt your GitHub password first. If this does not work, use your GitHub Personal Authentication Token (PAT).

If you do not know what your PAT is, just create a new one following [GitHub's PAT instrctions](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).


Verify that you have imported the repository by visiting your GitHub profile. If you do not see the repository in your profile then it did not transfer. Try following the steps again and if you continue to be unsuccessful ask an instructor for help. (To get to your profile, login to [GitHub](https://github.com/), click on your profile icon in the upper right hand corner, and then click on _Your profile_.)

## GitHub Pages

[GitHub Pages](https://pages.github.com/) is a service where you create a git repository that contains HTML, CSS, JavaScript, images, etc. for your own personal home page and GitHub will serve those pages for you at no cost to you.


To create your own home page, I shall followed the instructions given on https://pages.github.com.
1. Log into GitHub, https://github.com
1. My GitHub login is `mshafae`. I created a new repository, https://github.com/new, and named it `mshafae.github.io`. Replace `mshafae` with your GitHub username.
1. Clone the repository to your computer using the `git clone` command.
```
git clone https://github.com/username/mshafae.github.io
```
Again, replace `mshafae` with your GitHub username.
1. Change directory to be inside your repository, `cd mshafae.github.io` for example. In this directory, using your text editor, create a file named `index.md`.

Start by adding the following into `index.md` and replace your_username with your GitHub username. Additionally, replace the URL for Lab 1 with the correct URL for your own lab 1 assignment.
```
# Hello World
This is my home page! My name is Your Name and I am a student at [Cal State Fullerton](http://www.fullerton.edu/).

## Computer Science Projects
My GitHub page is http://github.com/your_username.
### CPSC 120
* [Lab 1](http://github.com/your_username/)

```

Save this file and commit it, `git commit -a -m "Initial commit of my home page"`. Then push the changes back to GitHub, `git push`.

Once you have pushed the changes to GitHub, use your web browser to visit your GitHub Page. In your instructors case, that URL is http://mshafae.github.io. Replace `mshafae` with your GitHub login to see if your changes appeared online.

If your changes did not appear online, then
1. Make sure you have the correct URL, remember it is github.io not github.com
1. Make sure you have committed and pushed your changes, look at the repository on GitHub.com to make sure the changes are there
1. Retrace all your steps

(If you are interested in having private repositories, you can explore the [GitHub Student Developer Pack](https://education.github.com/pack). You will have GitHub Pro while you are a student with the option to cancel when you are no longer a student. There are many other commercial services with student oriented promotions which are included in the pack.)

## Templates
Markdown is an effective tool to create readable documents that can be processed into HTML. However, it is very hard to create a beautiful, responsive web page.

Students interested in creating a web page that better reflects their personal aesthetic and is not as bland as what you can produce with Markdown are encouraged to use templates.

You are encouraged to visit sites such as [TEMPLATED](https://templated.co/) where many templates are available for you to copy and use for your own needs. Remember, that you are using someone else's work and that work has been licensed to you so please do not remove the copyright and the attribution.

Open the html files in your text editor and makes changes as you see fit. You will be surprised at how easily you can take a template and adapt it for your own needs.

You can make your links to your projects more interesting by using animated GIFs of your terminal. You can create animated gifs using [ttyrec](https://en.wikipedia.org/wiki/Ttyrec) with [ttygif](https://github.com/icholy/ttygif) or [terminalizer](https://www.terminalizer.com). On Ubuntu Linux, you can easily install packages `ttyrec`, `ttygif`, and `xdotool` with the command `sudo apt install ttyrec ttygif xdotool`. Below is an animated GIF of the installation process.

![Animated GIF of the terminal output from the commands `sudo apt update` and `sudo apt install ttyrec ttygif xdotool`.](images/ttyrec-install-small.gif)

Once you have the tools installed, you can create GIFs demonstrating your programs like the one below demonstrating a _Hello World!_ program that we wrote back in Week 1.

![Animated GIF of the terminal output compiling a C++ program and then executing the binary which prints the messaage "Hello World!".](images/clang-hello-world.gif)

Paul Czarkowski has some [brief instructions](https://medium.com/@pczarkowski/how-to-make-an-animated-gif-of-your-terminal-commands-62b08dfb6089) on how to create an animated GIF and then optimize it using [`gifsicle`](http://www.lcdf.org/gifsicle/) to make the file size smaller.

## Submission
In the file homepage.txt, write your GitHub Pages URL and push it to your repository.


https://help.github.com/en/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site

https://domains.google.com/
