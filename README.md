# Welcome !

This repository is meant for users who wish to practice before entering the 42 Piscine or for Pisciners to find guidance within this rough month.

# Introduction

Online, I go by Cheyo, i'm currently a 42 student in 42 Lausanne, and i'll try my best to guide you to successfully pass your piscine at 42. During my piscine i've seen a lot of people being scared and giving up, but i've seen plenty succeed with hard work. The Piscine is a hard step for almost everyone, so getting lost will happen.

# What is the Piscine about ?

The piscine is the one month long entry test at 42 where you will have to do projects. Forget about Python or Javascript if you thought about those programming languages. The piscine is all about Shell/Bash and C programming.

# Why C, and why other things ?

42 Campus's use Macs or Linux systems only. I've seen many being confused as why we wouldn't or couldn't use Windows as an operating system. To put it simply, they are better development environments. MacOS is based off Linux, so besides a few hardware or architecture differences, they remain better to work with than Windows.

C is a programming language, a so called "low-level" one. The lower level a programming language is, the closer it is to actual "machine language". This means it is very primitive, but mastering it will definitely make you great at understanding and learning higher level languages faster. Low level programming languages are also very powerful and lightweight, for example, most major cyber attacks involves low level vulnerabilities.

In my opinion, C is an excellent language to start with. Yes, you will struggle to do anything at first, but if you get comfortable with it, you will gain non-negligeable knowledge on computers and security. This will also make learning and adapting to newer languages or recent frameworks, much easier.

# The early projects

You probably already know if you're in the piscine already, but the Piscine starts off with a module called Shell00. You will have to make small "Bash scripts". Bash is a scripting language, which pretty much lets you make executable scripts to do commands you could do on a command line interface. It could do something like retrieving the names of all files containing "2024" in their name in the folder and subfolders you are and show them on the terminal for example. They can also be used to do things like installers, running the script would import and download the necessary files and apply changes if needed. Basically, they can do a lot.

## Text editing 101

You maybe are already fighting with how to edit text on a terminal, well you have a couple options.

- Nano ```(nano script.sh)```
- Vim ```(vim script.sh)```
- Visual Studio Code ```(Just run the program and open your files with the interface)```

For Shell00 and Shell01, i would recommand using Nano, it is very basic. Here's a small guide on how to use it :

## Nano

In your terminal, simply write "nano your_file_name" and it will open. There you can use the arrow keys and characters to write whatever. Avoid copying/pasting stuff into it or using mouse scrolling, unless it is setted up for it, terminals don't really like it. If you open nano and give it a filename that doesn't exist, it will create it when you save it.

To finish editing, you can do Ctrl+x to exit, it will ask you if you want to write changes. There you will either type "y" for yes or "n" for no. If you type yes, it will show you the name of the file in case you want to change it. Just press Enter and nothing else to apply the changes and it will exit Nano.

## Vim & Vscode (Visual studio code)

I will get into those later on, as they're most useful for the C programming part of the piscine.
