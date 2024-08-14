---
title: "Thoughts on Linux After 3 Years"
date: 2023-06-28T19:09:32+08:00
#url: '/posts/thoughts-on-linux-after-3-years/'
tags: ['Linux', 'Software', 'personal']
#draft: true
---
## The beginning
I have been using GNU/Linux for three years now and i wanted to share my thoughts after all this time. Like millions of others on this planet of ours, i was using windows as my primary Operating System. Every computer i have ever used had windows running on it, regardless if it was windows Xp, vista, 7, 10 or 11. As you can clearly tell, windows had complete dominance over the market. All of the large or well-known companies sell computers that run windows as an operating system. In fact, i have never come across a big company selling a pc that primarily runs linux as an OS. The first time i have heard about linux was 2016 or 2015 if i recall correctly, a close friend of mine 
was interested in trying it out in his PC and told me about it. However, i was not fully invested on Linux yet. Fast forward to 2020, another close friend of mine sent me an image of his desktop and upon inspecting the image it was clearly not a windows desktop. It was quite "elegant" and was looking somewhat like android but on a PC. It was obvious that he customized it to a great extent. I was intrigued and asked him about what he was using and he told me that it was Linux (Arch linux to be specific). He also introduced me to the concept of Linux "distributions", basically these distributions all have the same linux kernel but a different  package manager and desktop environment. A common analogy is going to an ice cream shop and selecting the flavor you desire. Essentially, they are all ice-cream but have different flavours. All linux distributions have the same building components.

Thus, i have decided to embark on a journey to learn about Linux and use it as an operating system. My friend adviced me to try kubuntu as my first distro. It was the first time that i have actually installed and used Linux on my laptop and it was a thrilling experience. I was somewhat clueless at the begining and was actually using it the same way i was using windows. However, as time progressed i started getting the hang of it and began to use Linux as my primary operating system. Additionally, I learnt alot about the linux terminal. It appears that a linux user must be accustomed to the terminal as it significantly improves the linux experience. It makes your usage of your system more efficient in certain ways. I will dive in about the terminal topic in a dedicated section 

## Benefits 
Given that i have made Linux my primary operating system, there are several benefits that i have found in using linux from my experience and from what i learnt in the past 3 years. 
1. **Linux is not resource intensive**: You may have noticed when accessing the task manager on windows that half of your RAM is being used even though you just booted into your system or opened a few programs. Windows has a lot of background processes that consume a significant amount of RAM. On the contrary, linux is quite lightweight. Even when im running a number of programs, my ram usage doesn't exceed 4 GBs (my Ram size is 16 Gbs). While on windows just booting into it you will have almost 50% of your RAM being used. In other words, majority of linux distributions are not as demanding as windows which makes it suitable for old or weak laptops. 
The image below shows my ram usage while running firefox with 10 tabs and 3 other programs.
![htop img](/htop_usage.png)

2. **Developer-friendly**: Most linux distributions/desktop environments come with a number of pre-installed development tools (eg. python intrepter, KDevelop from kde, Vim, GCC: C++ Compiler). Saves time and effort of looking & installing some developer tools (altho installing on linux is quite simple i will discuss this later). It also supports almost all programming languages if iam not mistaken. 

3. **Customizable**: Unlike windows, linux is **waaaaaaaaaay** more customizable. Almost anything can be changed and this is the done with the help of desktop environments* or window managers*. In windows, the most you can do is change the wallpaper and the color of the task bar. However, on Linux icons, taskbars, cursor, wallpapers, appearance of programs and even the lockscreen it self can be customized. You have complete control on how your system can look like. Actually you have complete control on how your system works the GUI interface is not the only the thing that is customizable in linux. You can modify your terminal's configuration files for instance to add a new feature or smth. 

4. **Open source**: Linux is indeed primarily an open-source operating system. This means that its source code is available to the public, allowing anyone to view, modify, and distribute it. The open-source nature of Linux fosters a community-driven development model, where users and developers can contribute to improving the operating system's security, fixing bugs, and adding new features

5. **Downloading/Installing software**: is remarkably simple compared to the process on Windows. On Windows, you typically need to open your browser, search for the desired software, navigate to a specific website, download the file, run the .exe installer, and click through several "Next" buttons before the program is finally installed. This can be a lengthy and cumbersome process. In contrast, Linux offers a much more streamlined approach. 98% of the time when wanting to install a software package on linux, users will need to use a package manager* through the terminal. Basically, a package manager automates the long process that i just described. Different linux distros come with different package managers for example ubuntu uses "apt" as its package manager. 
For instance for installing firefox on linux (iam using pacman as the package manager) all i have to do is simply type:  
`sudo pacman -S firefox` 
on my terminal and press enter.  

## The terminal 
Like a lot of people, i was completely clueless to using a terminal or the command line. I barely interacted with it when i was using windows and i only used it when i had to fix something by following a tutorial. I did not fully understand what i was doing but i just followed along to fix an issue i was facing eg. blue screen of death. 
When i started using linux and learned more about it, i realized that the terminal is a rudimentary component when it comes to linux. In fact, average linux users (let alone experts) use the terminal daily if iam not mistaken. 
In case you don't know,a terminal is basically a program used to interact directly with the operating system through a command line interface i.e. by entering commands. As i have briefly mentioned in the section above, using the command line / terminal improves your efficiency and saves effort. A simple example is the installation of packages that i have mentioned earlier. Everything becomes easier and faster when using it and since you are directly interacting with the OS, you can virtually do anything (even browsing the web altho terminal browsers are not exactly great). In addition, interacting with the terminal constantly gives you a much better understanding of your system. 
It is also a quicker way for developers to manage their projects (by using a text editor such as vim or emacs) instead of using GUI IDEs. 
(Iam basically repeating the same point but in different wording lel but you get it)

## Conclusion

I may have included a *bit* of unnecessary details in the sections above but basically iam glad that i stumbled upon linux and benefited alot from using it. I would recommend anyone to giving it a try, you can use a virtual machine if you dont wanna mess up your disk partitions. Then you can transit to dual booting or completely removing windows from your life :O. This page is actually quite general i did not dive into specifics when it comes to the terminal or some of the benefits. You can think of it as a page that somewhat introduces linux and why you should use it.




