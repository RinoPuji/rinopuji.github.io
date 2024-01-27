---
layout:  post
title:  MGS English Version
tags:  android monopolygo
last_modified_at:  2024-1-27
---

**TABLE OF CONTENT**
* TOC
{:toc}

## 1. What is MGSe ?
MGSe is stand for **Monopoly Go Script** and the letter **e** is for english version.This apps will help us **minimizing** the usage of dice we use when completing the event at MonopolyGo game.Because is just more on "automation" and to save my time,this apps actually just a simple automation script that i made using "tasker".

## 2. The main function of MGSe
MGSe help us to minimize our dice usage by expoiting current monopoly vulnerability that the dev still not fix.This apps will help us to "return back to our last position" if we did not wan the latest tile or position.Just think this apps just like a "time machine" that can help us "goes back to past" if we do not get the place that we wan in monopolygo game.

I made short video for you to see example of how this "time machine" work,pay attention on my position,current dice and what will happen when i click **Reset** Button :

<div class="embed-container"><iframe width="963" height="1712" src="https://www.youtube.com/embed/mOjlXIOrlNg" title="Example usage for MGSe 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>

Now we should can clearly see why i call this apps is just like "time machine".When we goes back to our last state before,we will get back the dice that we already spent on that move.

> This is how we can minimize the usage of our dice we use for completing the event.Only targeting tiles that give us a point for event.Goes back or reset back if we did not land on non event tiles.Repeat this process until we finish the event.

## 3. Advantage of MGSe
The main advantage for this apps is : 
- This app not required our device to be rooted.Some apps with similar like this need a rooted environment for it to work.And most of non-tech user will just using a VM and installing SU inside their VM.

This apps is created for solving often crash problem when using a VM in our device.

> p/s : VM that i means is Android Virtual Machine.Not solely on Virtual Master.There are many varity of Android Virtual machine that available like vmos,vphonegaga,virtual master,f1vm etc.

## 4. Disadvantage of MGSe
Because this apps is running on unrooted device or stock device,this apps only have a limited function due to security limitation on stock device.But the most important thing,the function for roll/reset back to the last state is working.

## 5. File and Installation Guideline
To avoid making this post become long,i have seperated the posting at **[Installation Guideline for MGSe](https://rinopuji.com/Installation-guideline-for-MGSe/){:target=_blank}**

## 6. Explanation on why we need to use MGe + MGSe
On the installation guideline post,i clearly state that we need to installing 2 application,

1. MGe 
2. MGSe

### 6.1 MGe
This file is actually just a monopoly go application that i modify to be pair and work with MGSe.

### 6.2 MGSe
This file contain the scripting to help exploting the vulnerability bug in monopoly go game.

> MGSe only work on MGe.This 2 need to be paired.It not work on another monopoly go application like the speed mod etc and it also not work foe original monopolgo application.

### 6.3 More depth explanation
The **"key"** for "reset" bug/trick is lay on the "restricted folder" or easy said a "fobidden folder".

> From here on,i will using "ReRoll application" from Edward as comparison.To be honest,i am not saying MGSe is better rather than ReRoll or ReRoll is better rather than MGSe.I just use "ReRoll" as comparison because most of us who playing trick surely know about this apps.So it make it easy to explaning thing.

In order to access this folder,we have many option,but i will just explaining with 2 option to avoid this post become a long post....

1. **Rooting our device**
- The common way to accessing this "restricted folder" is by rooting our device.I know some user here already know about "ReRoll" application by Edward (Go search discord group,*monopolygosecret").
- For using ReRoll,the requirement for using this apps is by installing VM.The purpose for installing VM is for getting root access,that why you also need to install SuperSu in the VM.
- Without a VM,you need to **direct rooting** your device by patching ramdisk and this process is totally confusing for non technical user.
<br>
2. **Modified R/W root folder permission for the application**
- The other work around for accessing this "restricted folder" is by modifying the READ and WRITE root folder permission inside the application itself.
- This is what i do on the MGe apps to accessing the "restricted folder" for monopolygo data without root environment.

In short,ReRoll will work on original mono application from playstore including the speed mod,etc but it will required you to have "root environment".Either you use a VM or direct rooting your device.

While MGSe will work on your stock device but it required you to use MGe that i already modified the permission to gaining access to "restricted folder".

This 2 application produce a same result but the method for this 2 application accomplish the result is totally different.
