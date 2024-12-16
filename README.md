# Welcome !

This repository is meant for users who wish to practice before entering the 42 Piscine or for Pisciners to find guidance within this rough month.

# Introduction

Online, I go by Cheyo, I'm currently a 42 student in 42 Lausanne, and I'll try my best to guide you to successfully pass your piscine at 42. During my piscine i've seen a lot of people being scared and giving up, but I've seen plenty succeed with no previous knowledge with hard work. The Piscine is a hard step for almost everyone, so getting lost will happen.

42 Also have strict rules on the code you must produce. I am mostly making this guide so people can find proper sources faster and easier. If you try to learn C online, you'll be surprised that most of what you've learned is not going to be authorized here. It doesn't mean it would be useless however ⚠️

## What is the Piscine about ?

The piscine is the one month long entry test at 42 where you will have to do projects. Forget about Python or Javascript if you thought about those programming languages. The Piscine is all about Shell/Bash and C programming.

## Why C ? and why other things ?

42 Campus's use Macs or Linux systems only. I've seen many being confused as why we wouldn't or couldn't use Windows as an operating system. To put it simply, they're better development environments. MacOS is based off Linux, so there might be a few hardware or architecture differences, but they, either way, remain better to work with than Windows.

C is a programming language, a so called "low-level" one. The lower level a programming language is, the closer it is to actual "machine instruction language." This means it can seem very primitive, but mastering it will definitely make you great at understanding and learning higher level languages faster. Low-level programming languages are also very powerful and lightweight, for example, most major cyber attacks involve low-level vulnerabilities.

In my opinion, C is an excellent language to start with. Yes, you will struggle to do anything at first, but if you get comfortable with it, you will gain non-negligeable knowledge on computers and security. This will also make learning and adapt to newer languages or recent frameworks, much easier.

## Piscine from home ? Sure why not

Although you won't be able to have your projects evaluated, you can find all the Piscine's subjects in this guide. Testers made by 42 students are available and are most likely good enough to do your own Piscine. Grademe, an exam simulator, is also very well made and contain the actual subjects of the exams.

If you're here to practice the Piscine in advance or to try it out at home. I'd suggest getting the tools available [Here](#PiscineHome).

## The first project

You probably know if you're in the piscine already, but the Piscine starts off with a module called Shell00. You will have to make small "Bash scripts". Bash is a scripting language, which pretty much lets you make executable scripts to do commands you could do on a command line interface. It could do something like retrieving the names of all files containing "2024" in their name in the folder and subfolders you are and show them on the terminal for example. They can also be used to do things like installers, running the script would import and download the necessary files and apply changes if needed. Basically, they can do a lot.

To navigate around your terminal , here's a few command you'll need :

- ```pwd```   Shows the "Print working directory", basically, shows you where you are.
- ```ls```    To list files and folders
- ```cd```    Change directory, ex : ```cd Desktop```
- ```mkdir``` Make directory, ex : ```mkdir piscine```
- ```touch``` Create a file, ex : ```touch test.txt```
- ```rm```    Remove a file
- ```rmdir``` Remove a directory
- ```chmod``` "Change mode", edit permissions. Learn about it. It'll be important. chmod calculators exist ⚠️

Terminal commands can also use flags, for example ```ls -al```. This will list files and directories where you are currently.
- The ```-a``` flag will let you see hidden files, which starts with a dot(.)
- The ```-l``` flag will show additional information for each element, such as the last edited date, size, permissions and more.

To navigate around, you can do ```cd folder_name``` and then to go back, do ```cd ..```

```..``` in terminals means the parent directory, a single dot ```.``` means the current directory.

This is one of **many** examples and possibilities, but the point is understanding terminal commands and flags. See more here about ls if you wish [ls command documentation](https://www.ibm.com/docs/en/power6?topic=commands-ls-command).

## Text editing 101

You maybe are already fighting with how to edit text on a terminal, well you have a couple options.

- Nano ```(nano script.sh)```
- Vim ```(vim script.sh)```
- Visual Studio Code ```(Just run the program and open your files with the interface)```

For Shell00 and Shell01, I would recommand using Nano, it is very basic. Here's a small guide on how to use it :

## Nano

In your terminal, simply write "nano your_file_name" and it will open. There you can use the arrow keys and keyboard to write whatever. Avoid copying/pasting stuff into it or using mouse scrolling, unless it is setted up for it, terminals don't really like it. If you open nano and give it a filename that doesn't exist, it will create it when you save it.

To finish editing, you can do Ctrl+x to exit, it will ask you if you want to write changes. There, you will either type "y" for yes or "n" for no. If you type yes, it will show you the name of the file in case you want to change it. Just press Enter and nothing else to apply the changes and it will exit Nano.

## Git... keep it simple for now.

If you're reading this, you maybe know what a Git repository is, but if that's not the case. Let me help you real quick.

Git is a version control system. Its purpose is to upload, share and update project files in what we call repositories.

A repository is basically a folder you've initiated git within it. The purpose of version controlling is being able to go back to any older version of your project. It has many other purposes, specially later on for group projects. For now, we'll keep it very very simple.

When you want to end a project, you'll have to upload your files to a git repository. They're the vogsphere links in your project's page. Here's a very simple way to upload your project safely without encountering issues, because during the piscine, many students will end up having issues.

1) Copy the vogsphere link. In your terminal, type ```git clone vogsphere_link_goes_here wanted_name```. (Ex : ```git clone git@vogsphere.42lausanne.ch:vogsphere/XXX Shell00```) This will make a repository with only git initiated within it, containing the information it needs to upload the project to the intra.
2) Copy your work into the folder/repository. Make sure the folders and files match up to what the subject PDFs demand.
3) Use the command ```git add .``` This will add everything in the current folder in a queue.
4) Use the command ```git status``` This command you should use at pretty much every step to make sure everything is working right. At this point it should list all of the files you've added to your queue.
5) Use the command ```git commit``` This will open your preferred text editor. Add in a description of what you've added. Save and leave the editor. Right now you have a commit, this commit has a description, and the files you added to your queue. Git keeps track of all commits, so it's important to name them well in case you want to go back to an older one.
6) Use the command ```git status``` once again to make sure everything seems fine and is ready to be "pushed". If everything looks good, you can use ```git push``` to finish uploading your work.

Once you've pushed your project, you can ```git clone``` the vogsphere repository again, give it another name or anything. You should now see that the clone you just made holds your files. You can do this to make sure your folders and files are right and properly available for the intra. Once you're sure everything is in order, you can set your project as finished.

## Evaluation system

Maybe you finished Shell00, or it's very late at night and you're seeing Piscine retryers going over each others computers. They're most likely evaluating each others.

During the Piscine at 42, you will be evaluated by the infamous **Moulinette**. The Moulinette is a program which consists of brutally strict checks to judge your work. But before anything happens through the Moulinette, you will be evaluated by 2 other students. This is where peer learning shines.
- If you are being evaluated by a more experienced person, they should be able to teach you if you have questions or did something wrong.
- If you are evaluating a more experienced person on a project you don't know or haven't seen yet, their role is to teach you how it works to prove they understood the assignment.
- Once you get more comfortable with projects, you'll be the one teaching others, this is very important as teaching is one of the best ways of studying your previous work.

When you evaluate someone, you'll get evaluation points. You will consume points everytime you will want to get evaluated. So let's say you finished Shell00. You spend 2 points to get evaluated, but something wasn't right. First of all, **you'll have a cooldown before being able to send your project again**. You will also get an email with the result of the Moulinette, telling you where the first problem was found. **It will only show you the first problem it encounters**, this means there could be more errors further in your project. All of this is designed to make sure you send something you've checked and tested many times.

## Shell01 ? or C00 ?

Once your Shell00 is valid, you are free to choose either Shell01 or C00 as your next project.

To be very honest, C modules are way more important, specially because you will never have exam questions on Shell. If you don't lose too much time on it, Shell01 will teach you more complex bash scripts and could be worth it.

# How to approach C modules

## Have you done code before ?

If you never did code before, do some research and find out what variables are, what if statements are. Here's one great book that can help you out (CHAPTER 3) : [Beej's guide to C Programming](https://beej.us/guide/bgc/pdf/bgc_usl_c_1.pdf)

I can't recommend this book enough. It talks to you as if it was a conversation. It helped me during my entire Piscine. It doesn't use many external functions which are forbidden at 42 and goes into great technical details when needed.

**Remember.. no printf, no ```for``` loops, no unauthorized functions or libraries**, you can use printf(); for testing as long as you remove it before uploading your projects.

Every project in C, must respect the [Norm V4](https://cdn.intra.42.fr/pdf/pdf/96987/en.norm.pdf). A set of strict rules to follow.

## Try out Vim

Vim is probably the most used text editor during the Piscine at 42, It is set up with plugins such as proper indentation and the 42 Header to make it work well with the 42 Norm. Vim can be hard to use at first, but if you take the time to learn it well, you can produce code really really fast.

**Let's open something, edit it, and exit Vim**

"How do I exit Vim" is a popular joke but something you might actually hear.

	vim test.c

 You opened test.c in vim, if you wish to type something you will need to press the ```I``` key. You will see an --INSERT MODE-- text pop up. Now you can type stuff.

 To exit Insert mode, press the ```ESC``` key.

 Vim works with different "Modes", but --INSERT-- mode is going to be your friend here.

 you can now press ```:```, You will be able to type at the bottom of the screen where the modes show up usually. this is where you can enter commands.

 ```:set nu``` Set number. this is pretty useful, as it will now show the line numbers on screen.

 ```:w``` Write. writes and saves what you may have edited.

 ```:q``` Quit, exits Vim, but won't work if there's is unsaved work.

 ```:q!``` Force Quit, will exit Vim discarding unsaved changes.

 ```:wq``` Write and Quit, saves and quits.

Vim is full of shortcuts and features, if you enter a mode you didn't want by accident, just press ```ESC```.
I would suggest doing some research on simple Vim shortcuts to get used to it.

Congratulations, you can now exit Vim.

## Let's do C00's first exercice together.

```Turn-in directory : ex00/```

```Files to turn in : ft_putchar.c```

```Allowed functions : write```

Okay here's the most important part of the Piscine : No external libraries or functions in C (except if allowed)

In ex00, it says that ```write``` is an allowed external function.

RTFM (Read the fucking manual), is something you might hear a couple times. During the Piscine, you will have to read a lot. It is best to read and learn how things work factually rather than just apply hearsay.

In your terminal, you can do ```man write```

```man``` stands for manual. You can use it for many functions in C. If your terminal doesn't have a manual entry, just Google it. There's most likely a manual entry online.

The ```man``` entry for ```write``` says the following :
```
#include <unistd.h>

      ssize_t write(int fildes, const void *buf, size_t nbyte);
DESCRIPTION
          The write() function shall attempt to write nbyte bytes from the buffer pointed to by buf to the file associated with the open file descriptor, fildes.
```
Okay now that sounds very complicated, but for now, I will simplify what that terminology means.

- ```write``` is a function. A function is something we can call in a program to do something. ```write``` just writes something on the terminal window.
- The manual shows ```#include <unistd.h>```. As ```write``` is an external function, we must no forget to include the library it's from.
- In the manual, we can see the function starts with ```ssize_t```. That is it's type. ssize_t is a type of size, which means it will return a number. The return value of write will be negative if the function fails (which honestly shouldn't)
- It takes 3 **arguments**, ```int fildes```, ```const void *buf```, ```size_t nbyte```. These 3 arguments have types and names.


```fildes```, ```*buf```, and ```nbytes``` are not very intuitive for a beginner. So let's simplify this.


```fildes``` we can use as a setting for the write function. There's 3 available options.


- ```0``` for an **input** type, but it isn't used anymore.
- ```1``` for an **output** type, something we want to push out. This is what we'll use to write something out.
- ```2``` for an **error** type, this will be used later on when projects will ask you to print out errors.


The second argument ```*buf``` is the text we would like to print out, it can be raw text or a value we give it.

The third argument, nbyte, is the number of bytes we would like to print out. Yes, bytes as in 8 bits, bits as in 0s and 1s. Luckily for you, a single character weighs 1 byte.

Putting everything together, we can actually have a function that will print out something.

```write(1, "A", 1);```

We use ```1``` to have write acts as an output.
We have ```A``` as our text.
We use ```1``` because we only print out one letter.

You could also do this : ```write(1, "Hello", 5)```

Let's read the subject again to actually make the thing as a ft_putchar.c file.



- Write a function that displays the character passed as a parameter.
- It will be prototyped as follows :

      void ft_putchar(char c);

- To display the character, you must use the write function as follows.

      write(1, &c, 1);

- Do not forget to add the standard 42 header in each of your .c/.h files. The norminette check its existence anyway!


Within Vim, 42 Schools usually have a plugin installed to automatically put your "42 Header". The header is here to pretty much have some information and signature on your own code. To add the header in your .c file, pressing ```F1``` should do the trick. If it doesn't, ask a mate around. If you use Vscode, you will have to install a plugin yourself to have a similar option.

When subjects say that a function "will be prototyped as follows", it means the moulinette will try to call the exact line they give you. Meaning your function should have the same name, types and arguments.

Let's break down the ```void  ft_putchar(char c);``` function.

- ```void``` is a data type. When a function is of void type, it means it will not return a value.
- ```ft_putchar``` is the function's name.
- ```(char c)``` When calling ```ft_putchar();```, we need to give it a character variable named ```c```, char is the variable type for **a single** character.

When the moulinette calls for ```ft_putchar();```, it will try something like this :

- ```ft_putchar('A');```
- ```ft_putchar('+');```
- ```ft_putchar('W');```

Back to the PDF, we can see something unfamiliar with the ```write``` function.

    write(1, &c, 1);

Without going too deep into details, the ```&``` means we send the Memory address of the ```char c``` variable. We do this because the ```write();``` function wants us to send the text this way.

To sum it up one last time, we call the ```write();``` function, set the first parameter as an output with ```1```, send the memory address of our ```c``` variable and finally the number of bytes to ```1``` because we are printing a single character.

I've stated that functions could return values, printing a character on the screen doesn't mean we are returning a character.

Let's put out an example of what a function that returns something would look like.

```C
int  multiply(int number1, int number2)
{
	int result; // int is the most common type used for numbers (Integer)

	result = number1 * number2;
	return (result); // a program could use this function like so : int x = multiply(7, 2);
}
```

I hope so far that my explanations on functions are clear. If you believe there is room for improvement, please contact me and let me know.

**This should be the final function :**

```C
/* ************************************************************************** */
/*                                                                            */
/*                                                        :::      ::::::::   */
/*   ft_putchar.c                                       :+:      :+:    :+:   */
/*                                                    +:+ +:+         +:+     */
/*   By: nrey <nrey@student.42.fr>                  +#+  +:+       +#+        */
/*                                                +#+#+#+#+#+   +#+           */
/*   Created: 2024/10/08 06:10:50 by nrey              #+#    #+#             */
/*   Updated: 2024/10/08 06:11:45 by nrey             ###   ########.fr       */
/*                                                                            */
/* ************************************************************************** */

#include <unistd.h> //including the standard C library for write();

void	ft_putchar(char c)
{
	write(1, &c, 1);
}
```

# Testing your function - introduction to mains

Cool, we got some of the theory down, but how can we use that function to make sure it works ?

We will have to **compile** a program. Right now our ```ft_putchar.c``` file only has a function, it's not a program.

Compiling a file means translating the code we've written to "machine instruction language", so that our computer can execute it.

For a program to be compilable, it will look for a ```int  main()``` function.

This function's type is ```int``` meaning it will return a numeric value.

The most common practice is to return (0) if a program ended successfully, you could return any wanted numbers if you were trying to find an error for example.

Let's make a main function to test out ```ft_putchar();``` function.

```C
/* ************************************************************************** */
/*                                                                            */
/*                                                        :::      ::::::::   */
/*   ft_putchar.c                                       :+:      :+:    :+:   */
/*                                                    +:+ +:+         +:+     */
/*   By: nrey <nrey@student.42.fr>                  +#+  +:+       +#+        */
/*                                                +#+#+#+#+#+   +#+           */
/*   Created: 2024/10/08 06:10:50 by nrey              #+#    #+#             */
/*   Updated: 2024/10/08 06:11:45 by nrey             ###   ########.fr       */
/*                                                                            */
/* ************************************************************************** */

#include <unistd.h> //including the standard C library for write();

void	ft_putchar(char c)
{
	write(1, &c, 1);
}

int  main(void)
{
  ft_putchar('W'); // Calling ft_putchar
  return(0); // Program ends here
}
```

Notice how the main function is at the bottom. This is because it wouldn't be able to see ```ft_putchar();``` if the main was on top. There are of course many ways around this, but they'll come up handy later on. I will let you explore that by yourself.

To compile our code, we'll use the ```cc``` command in our terminal. Short for **C Compiler**.

    cc ft_putchar.c

This will make an executable called ```a.out```

If you wish to give your executable another name, you can alternatively use :

    cc ft_putchar.c -o program_name

```-o``` is a flag, o for output.

Now just like a Shell script, you can run it using ```./program_name```

And voilà, you can see your program in action !

**Make sure to remove main functions before finishing the project**, only include a main function if the subject asks you to !

Uh oh, you are printing a character now, but it's on the same line as your Shell's path line ? Can you find what character you need to call ```ft_putchar();``` with to print a newline ? Go find it ! Your putchar function should not print a newline, but knowing this will come in very handy in future projects.

# Valuable tools and ressources to practice the Piscine

- 42 Norm V4, the strict rules you'll be facing with all C projects : [42 - Norm V4](https://cdn.intra.42.fr/pdf/pdf/96987/en.norm.pdf)
- 42 Norminette, a checker for Norm issues in your code : [42 - Norminette](https://github.com/42School/norminette)
- Beej's Guide to C Programming, I find this book to be extremely easy to read and it was by far my best ressource during the Piscine : [Beej's guide to C Programming PDF](https://beej.us/guide/bgc/pdf/bgc_usl_c_1.pdf)
- Mini-Moulinette, a tester program by 42 Students for your C modules during the Piscine. Which saves plenty of time. **Learn how to make your own tests and main functions efficiently first !** [k11q's Mini-Moulinette](https://github.com/k11q/mini-moulinette)
- Grademe.fr, an amazing replica of the 42 Exam system, which features the actual exercices of the cursus : [Grademe.fr](https://grademe.fr)
- Francinette, another great tester for 42 Modules : [xicodomingues's Francinette](https://github.com/xicodomingues/francinette)

# Piscine@Home

- [42 - Norminette](https://github.com/42School/norminette)
- [k11q's Mini-Moulinette](https://github.com/k11q/mini-moulinette)
- [xicodomingues's Francinette](https://github.com/xicodomingues/francinette)
- [Grademe](https://grademe.fr)
- [42 Header plugin](https://github.com/42Paris/42header)
