# How to use the Urgent Publisher Website

This is a guide for how to use and update the Urgent Publisher website. You will need:
- a code editor (Visual Studio Code or Sublime Text)
- a modern browser (Chrome, Firefox, Safari)
- Github Desktop

## About the Website
The website of [The Urgent Publisher](urgentpublisher.macd-falmouth.studio) is a static website, static meaning that it doesn't change unless you (the author) changes it. The opposite of this is dynamic, which means a website can change based on new data or on interaction from a user.

The website is currently stored on a platform called Github. Github is a Microsoft owned platform that programmers use to store and share their code in things called repositories. Luckily for us, Github offers a service called Github Pages that allows you to add website files to a repository which can then be published as a website. (Usually this process requires a server to host the website).

## How to add to the website
To get started with uploading your websites, we will go through some of the first steps of downloading the current code, adding your own, and uploading new code. Whilst we will do this together, I have written out the steps below if you need to refer to it in the future.

1. In order to download the repository from Github, you need to make a Github account. Go to [github.com](https://github.com/) and click on "sign up" which is usually in the top right hand corner of the website. Add in your email, a password, a username and your country/region.
2. Ben needs to collect usernames and add you to the urgent-publisher repository that has already been set up.
3. Once you've been added to the repository, go to the link: https://github.com/benjaminearl/urgent-publisher and click on a green button with  "<> Code" on it. It should open a dropdown menu where you should see the option to "Open with Github Desktop", click on this. It should open up the Github Desktop app automatically and give you the option to download the contents of the repository to a certain folder on your computer. Choose somewhere that makes sense for you. I use a "websites" folder to store all my code. (if it doesn't automatically open the app, you can open it yourself and click on the down arrow in the top-left corner and then click on the "add" button and then the "clone repository" button, you can then type in benjaminearl/urgent-publisher and click on the correct repository in the list)
4. Open the folder where you saved the contents of the repository to and check that it has files inside it. The files should include a "index.html" file, a "templates" folder, a "workshop-presentation folder" and a file called "CNAME"
5. Make a new folder with your first name as the title.
6. To check that everything is working, go back to Github Desktop and you should see the folder that you added in the sidebar on the left. Click on the "Fetch origin" button and then add a summary of what you're uploading in the "summary" text-field at the bottom-right. Press the blue "commit" button and then click "Push origin" button which is where the "Fetch origin" button used to be.
7. This adds the folder you made to the repository for everyone to see and also download to their own computer
8. Go to your text editor and drag and drop the entire folder of the repository into it.
9. Go to the templates folder and copy and paste one of the templates into the folder with your name on it. Rename this file index.html - this is the file you will be adding your code to.
10. Once you're happy with the code you've added to your file, you can upload it to Github in the same way you added the folder with your name. It is important that you are adding your index.html file to your own folder, rather than someone else's.
11. Once you've successfully uploaded your new code, you can preview it by going to the urgent-publisher website and then typing in `/your-name/index.html` (replacing "your-name" with your actual name)
