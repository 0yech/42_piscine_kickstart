# Welcome !

This repository is meant for users who wish to practice before entering the 42 Piscine or for Pisciners to find guidance within this rough month.

# Introduction

Online, I go by Cheyo, i'm currently a 42 student in 42 Lausanne, and i'll try my best to guide you to successfully pass your piscine at 42. During my piscine i've seen a lot of people being scared and giving up, but i've seen plenty succeed with no previous knowledge with hard work. The Piscine is a hard step for almost everyone, so getting lost will happen.

42 Also have strict rules on the code you must produce. I am mostly making this guide so people can find proper sources faster and easier. If you try to learn C online, you'll be surprised that most of what you've learned is not going to be authorized here. It doesn't mean it would be useless however /!\

## What is the Piscine about ?

The piscine is the one month long entry test at 42 where you will have to do projects. Forget about Python or Javascript if you thought about those programming languages. The Piscine is all about Shell/Bash and C programming.

## Why C, and why other things ?

42 Campus's use Macs or Linux systems only. I've seen many being confused as why we wouldn't or couldn't use Windows as an operating system. To put it simply, they're better development environments. MacOS is based off Linux, so there might be a few hardware or architecture differences, but they, either way, remain better to work with than Windows.

C is a programming language, a so called "low-level" one. The lower level a programming language is, the closer it is to actual "machine instruction language". This means it can seem very primitive, but mastering it will definitely make you great at understanding and learning higher level languages faster. Low-level programming languages are also very powerful and lightweight, for example, most major cyber attacks involve low-level vulnerabilities.

In my opinion, C is an excellent language to start with. Yes, you will struggle to do anything at first, but if you get comfortable with it, you will gain non-negligeable knowledge on computers and security. This will also make learning and adapting to newer languages or recent frameworks, much easier.

## The early projects

You probably know if you're in the piscine already, but the Piscine starts off with a module called Shell00. You will have to make small "Bash scripts". Bash is a scripting language, which pretty much lets you make executable scripts to do commands you could do on a command line interface. It could do something like retrieving the names of all files containing "2024" in their name in the folder and subfolders you are and show them on the terminal for example. They can also be used to do things like installers, running the script would import and download the necessary files and apply changes if needed. Basically, they can do a lot.

to navigate around your terminal (Using iTerm2), here's a few command you'll need :

- ```pwd```   Shows the "Path to working directory", basically, shows where you are.
- ```ls```    To list files and folders
- ```cd```    Change directory, ex : ```cd Desktop```
- ```mkdir``` Make directory, ex : ```mkdir piscine```
- ```touch``` Create a file, ex : ```touch test.txt```
- ```rm```    Remove a file
- ```rmdir``` Remove a directory
- ```chmod``` "Change mode", edit permissions. Learn about it, it'll be important. /!\ chmod calculators exists /!\

Terminal commands can also use flags, for example ```ls -al```. This will list files and directories where you are currently.
- The ```-a``` flag will let you also see hidden files, which starts with a dot(.)
- The ```-l``` flag will show additionnal information for each element, such as the last edited date, size, permissions and more.

This is one of **many** examples and possibilites, but the point is understanding terminal commands and flags. See more here about ls if you wish [ls command documentation](https://www.ibm.com/docs/en/power6?topic=commands-ls-command)

## Text editing 101

You maybe are already fighting with how to edit text on a terminal, well you have a couple options.

- Nano ```(nano script.sh)```
- Vim ```(vim script.sh)```
- Visual Studio Code ```(Just run the program and open your files with the interface)```

For Shell00 and Shell01, I would recommand using Nano, it is very basic. Here's a small guide on how to use it :

## Nano

In your terminal, simply write "nano your_file_name" and it will open. There you can use the arrow keys and keyboard to write whatever. Avoid copying/pasting stuff into it or using mouse scrolling, unless it is setted up for it, terminals don't really like it. If you open nano and give it a filename that doesn't exist, it will create it when you save it.

To finish editing, you can do Ctrl+x to exit, it will ask you if you want to write changes. There, you will either type "y" for yes or "n" for no. If you type yes, it will show you the name of the file in case you want to change it. Just press Enter and nothing else to apply the changes and it will exit Nano.

## Vim & Vscode (Visual studio code)

I will get into those later on, as they're most useful for the C programming part of the piscine.

## Git... keep it simple for now.

If you're reading this, you maybe know what a Git repository is, but if that's not the case. Let me help you real quick.

Git is a version control system. It's purpose is to upload, share and update project files in what we call repositories.

A repository is basically a folder you've initiated git within it. The purpose of version controlling is being able to go back to any older version of your project. It has many other purposes, specially later on for group projects. For now, we'll keep it very very simple.

When you want to end a project, you'll have to upload your files to a git repository. They're the vogsphere links in your project's page. Here's a very simple way to upload your project safely without encountering issues, because during the piscine, many students will end up having issues.

1) Copy the vogsphere link. In your terminal, type ```git clone vogsphere_link_goes_here wanted_name```. (Ex : ```git clone git@vogsphere.42lausanne.ch:vogsphere/XXX Shell00```) This will make a repository with only git initiated within it, containing the information it needs to upload the project to the intra.
2) Copy your work into the folder/repository. Make sure the folders and files match up to what the subject PDFs demand.
3) use the command ```git add .``` This will add everything in the current folder in a queue.
4) use the command ```git status``` This command you should use at pretty much every step to make sure everything is working right. At this point it should list all of the files you've added to your queue.
5) use the command ```git commit``` This will open your prefered text editor. Add in a description of what you've added. Save and leave the editor. Right now you have a commit, this commit has a description, and the files you added to your queue. Git keeps track of all commits, so it's important to name them well in case you want to go back to an older one.
6) use the command ```git status``` once again to make sure everything seems fine and is ready to be "pushed". If everything looks good, you can use ```git push``` to finish uploading your work.

Once you've pushed your project, you can ```git clone``` the vogsphere repository again, give it another name or anything. You should now see that the clone you just made holds your files. You can do this to make sure your folders and files are right. Once you're sure everything is in order, you can set your project as finished.

## Evaluation system

Maybe you've finished Shell00, or it's very late at night and you're seeing Piscine retryers going over each others computers. They're most likely evaluating each others.

During the Piscine at 42, you will be evaluated by the infamous **Moulinette**. The Moulinette is a program which consists of brutally strict checks to judge your work. But before anything happens through the Moulinette, you will be evaluated by 2 other students. This is where peer learning shines.
- If you are being evaluated by a more experienced person, they should be able to teach you if you have questions or did something wrong.
- If you are evaluating a more experienced person on a project you don't know or haven't seen yet, their role is to teach you how it works to prove they understood the assignment.
- Once you'll get more comfortable with projects, you'll be the one teaching others, this is very important as teaching is one of the best ways of studying your previous work.

When you evaluate someone, you'll get evaluation points. You will consume points everytime you will want to get evaluated. So let's say you finished Shell00, you spend 2 points to get evaluated, but something wasn't right. First of all, **you'll have a cooldown before being able to send your project again**. You will also get an email with the result of the Moulinette, telling you where the first problem was found. **It will only show you the first problem it encounters**, this means there could be more further in your project. All of this is designed to make sure you send something you've checked and tested many times.
