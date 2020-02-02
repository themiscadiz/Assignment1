<!-- Every README should start with an H1 -->
# Assignment 1: Setup and Net Art Readme 
<!-- A one sentence description of the project or assignment -->
Setup and Net Art assignment is about how to open a Visual studio file, downloaded to your Github, open a ssh key, and commit and push the code updates through the Terminal. 

<!-- It is good practice to add an about or summary -->
## About

In this assignment I created a website using html/css to illustrate part of a Deerhoof song, "Flower". 
The first part of the assignment was to use the code editor Visual Studio and upload different versions to the Github. In this repository you can see different versions of the html and css files and follow the progress of this exercise.

<!-- It is essential to describe how to set up your project -->
## Setup
To run my code you need to:
1. Download the repository to your computer from my Github account. 
2. Open terminal. 
3. Navigate to project folder.
4. Create a Local Web server.

5. Open localhost

Now you are going to see the website in your local server.

<!-- Any knowledge or tools you will need before hand -->
### Prerequisites

To be able to open and this website in your computer you need:
1. to have a terminal or Command line.
2. Have a browser.


<!-- any installation needs should be defined -->
### Installation

If you are going to make changes to the code, you need to download a text editor (ex. Visual Studio, Atom, Sublime).

<!-- Write instructions on how to start working on your project -->
<!--### Develop

<!--To develop this document, you can follow the steps provided below:
1. create a fork of this project on Github
2. ping the author of this repo via Github Issues to see if they are looking for contributions on the specific feature you're looking to add
3. open the file in VS Code and make updates 
4. add and commit those changes in your forked github repo
5. make a pull request specifying what additions and changes were made
6. have a nice chat and communication with me about those changes. 
7. celebrate the contribution! -->

<!-- Notes about the deployment -->
### Deployment

To runs this project on your computer, you need to:
  1. Open terminal
  Type ‘cd ‘ (don’t forget the space)
  In Finder or files(Mac or Windows), navigate to the folder. Drag and drop the folder into the Terminal.
  
  2. In Terminal, type:  
  If is python 2.X
  $ python -m SimpleHTTPServer

  or, if you are running Python 3
  $ python3 -m http.server 8000
  
  3. open on your browser
     localhost:8000


## Built with

* [VS Code](https://code.visualstudio.com/)
* [Github](https://github.com)

## Authors
* [Themis Garcia] -- ITP student 

<!--## Code of Conduct

<!--Please read the [CODE OF CONDUCT](https://www.mozilla.org/en-US/about/governance/policies/participation/) 

<!--## License

<!--This is README template is licensed according to [Attribution 4.0 International (CC BY 4.0) ](https://creativecommons.org/licenses/by/4.0/)

<!-- thank and reference all the things that made your project happen -->
## Acknowledgements

Readme template provided by 
* [Joey Lee](https://jk-lee.com) -- adjunct professor -- [NYU ITP](https://itp.nyu.edu)
* [Cassie Tarakajian](https://cassietarakajian.com/) -- adjunct professor -- [NYU ITP](https://itp.nyu.edu)
for the Dynamic Web Development Class at ITP

***

* [Creative Commons](https://creativecommons.org/licenses/by/4.0/) for their licensing documentation
* [Openmoji project](https://www.openmoji.org/library/#search=notebook&emoji=1F4D4) for their glyphs
* [PurpleBooth's Readme Template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)

***
***
***

<!-- For your assignments you might consider  -->
# Notes & Process

In this assignment I created a website using html/css to illustrate part of a Deerhoof song, Flower. 
The first part of the assignment was to use Visual Studio and upload different version to Github.
I had a lot of difficulties understanding the terminal flow such as: how to create a file through the terminal and open in Visual studio. Because at first I tried to make the step using my notes from the class, I missed information and I wasn't able to open the file. Then, I followed [“Your First Website Guide”] (https://github.com/itp-dwd/2020-spring/blob/master/guides/your-first-website-guide.md) from the class on github and that helped me to complete the information. After I open the file in visual Studio, I copied the template from the first website example:

After I was able to see it run in github I used the instructions to open a local server. 

**I didn't add pictures of my process because I didn't want to show images of my terminal.**



<!-- How you built this project - Include images, gifs, and notes here -->
## Process & Documentation

Running website in local server:
At the beginning of the project I used the Step 4 instructions to run a local server, writing: 
$ python -m SimpleHTTPServer

However, I noticed that for some reason the local server didn't show all the changes that I was making. I decided to use another instruction that I had to create a local server: 
browser-sync start --server -f -w

Not sure why but in this case, the ip address is 3000 and the local server uploaded each time that I save the code. 

**HTML and CSS**
Fot the development of the Net Art website I decided to create a visual representation of each part of the song "Flower" by Deerhoof. I started the creation of the website from the html, and when I felt that I have something that I can work on, I started the the css file.
I created an additional file where I have separeted the main.css file form the html. This helped me to feel more organized and experiment better with the style without affecting the html.

In the html I experimented with the creation of div, paragraph, headers, ordered and unordered list, links to pictures, videos, navigation and id.

In the css I tried a different font from Google Font, different selectors, property such as hover, display, float and others.


<!-- Any specific challenges or struggles documented -->
## Challenges & Struggles

The biggest difficulties that I encountered in this process was to **create the ssh key**. 
The [github guideline] (https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) assumes you already are familiarized with github, terminal and development process. At first I didn't understand why I need an ssh key.

Step: Adding your SSH key to the ssh-agent
To  modify your ~/.ssh/config file, it is not clear what are the steps that you have to do. After getting help, I found out that I have to write:
$ nano ~/.ssh/config

and then paste:

Host *
  AddKeysToAgent yes
  UseKeychain yes
  IdentityFile ~/.ssh/id_rsa
  
  **HTML and CSS challenges**
Because html and css is very straight foward it was relatively easy to follow book examples, or tutorials about how to make parts of the html or create the style on css.
However, I have difficulties trying to understand the logic of **display**, how to fix indentation or margins on css.

<!-- Any questions you have -->
## Questions
1. How to better use "display" on css? Is there a difference with Flexbox?

<!-- References for resources and inspiration -->
## References

* Jon, Duckett. [HTML & CSS: Design and Build Web Sites](https://www.amazon.com/HTML-CSS-Design-Build-Websites/dp/1118008189)
<!--* Author First Name, Author Last Name. [Link]()-->
