# <h1>Using a Scripting Application and Proxy Servers on an AWS EC2 Virtual Machine to Purchase a Sneaker from a Limited Online Release</h1>
 
 </h2>

<h2>Description</h2>
In 2020, I wanted to purchase a pair of Nike shoes, but I could not do it manually because of the rise of people using "Sneaker Bots". These bots run scripts that automate the purchasing process of shoes online as soon as they are released. This makes it almost impossible for the normal consumer to purchase shoes. I was fascinated with the technology and really wanted those shoes, so I decided to try using a sneaker bot myself. This project explains some of the steps I took to accomplish that.



<br />
<br />

<h2>Tasks in Nike Shoe Bot</h2>
<p align="center">
<img src="https://imgur.com/0V1ZGHt.png" height="65%" width="65%" alt="Exmaple of Tasks in Nike Shoe Bot"/>
</p>

In this image, you can see the scripting application (or "Bot" as it is referred to in the community) that I used called Nike Shoe Bot. This application allows you to input the website, size, model, payment information, and proxies into a task. All of this information is then passed into the variables of the script that is used to purchase the shoes. 

<br />

The websites that sell sneakers online try to prevent people from using sneaker bots, but they mainly block duplicate IP addresses to stop it. In order to have the best chance at purchasing the desired shoes, I ran many tasks with different proxies so my IP address did not get blocked. 

<h2>AWS EC2 Virtual Machine</h2>
<p align="center">
<img src="https://imgur.com/RA1KVNU.png" height="65%" width="65%" alt="AWS EC2 Virtual Machine"/>
</p>

As an added layer of protection from getting my home IP address banned, as well as increased performance and my interest in cloud computing, I ran this application on an AWS EC2 virtual machine. I used a 2016 Windows Base machine image and downloaded Nike Shoe Bot into it. From there I created my tasks and waited for the release.


<h2>Example Python Script</h2>
<p align="center">
<img src="https://i.imgur.com/YlFFQoi.png" height="65%" width="65%" alt="Example Python Script"/>
</p>

This is an example of the type of code used to run the bot.


<h2>Success!</h2>
<p align="center">
<img src="https://i.imgur.com/Ko5FEGT.jpeg" height="65%" width="65%" alt="Example Python Script"/>
</p>

The picture above shows my successful attempt at using the Bot to purchase the shoes. The task that succeeded first was the one I used with no proxy server, so I stopped running all other tasks. I ended up receiving my shoes and learned a lot in the process about AWS, writing scripts, web application security, proxy servers, and more.




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
