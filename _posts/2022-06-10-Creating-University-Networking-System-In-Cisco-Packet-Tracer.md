---
title:  "Creating University Networking System In Cisco Packet Tracer"
mathjax: true
layout: post
categories: 
 -Networking system
 -Cisco Packet Tracer
---

   Hello, today I and my friends tell you how to create a networking system in Cisco Packet Tracer. This is our CET 314 homework and this is a group project. Our group's name is Cetgiller.

   Before reading the article;
   It is assumed that you know Cisco Packet Tracer.
Part 1- General Information About The System

   Group member;
   Ali Eren Kayhan
   Bengisu Kaya
   Ege Eroğlu
   Enes Sucu
   Numan Kaya


   First, you need to know what the system must have, and what you have
Company Name: Gezi school’s campuses
The number of campus: 4
The number of students: 1150
The number of teachers: 64
The number of workers: ≌ 40
The number of desktops: ≌ 250
The number of classrooms: ≌ 24
The number of labs: ≌ 5
Total of cabling in the current system: 1400 meters
They want internet access with an average 300 kbit/s.
Every campus and buildings have the same network speed.









   Moreover, you should clarify your plan.

   1. Business Objectives 


a. What does the company do? 

Giving education to next generations.

b. Why do they think they need a network?

To access more information and resources, communicate with each other (especially during the Pandemic) and also others (teachers from other schools), giving lessons by some platforms like Zoom and so on.

c. What divisions/departments would be impacted by the network?

Every department and division would be positively impacted by the network, especially if they deal with computers.

   2. Future Growth 

a. What is the projected growth of the company?

Thanks to networking designed by us, they have a chance to give better and more qualified education to students and graduating more successful and qualified students from the school means more and more students want to be part of this. In other words, students become more willing  to study in our schools. Therefore, the school will become like Bogazici university, which means becoming a top ranking school because better network and better education’s conditions make the school a target school for those students who want to improve themselves.

b. Are new divisions/departments planned to be developed in the near future?

Yes. Technology changes day by day and there are new areas. Therefore, to catch the trends in the working area there should be new departments and the current departments should be improved.

c. Where does the company see itself in one year? Five years?

In one year, the school should be in the top fifty schools in ranking. In five years, the school should be in the top twenty schools in ranking.

   3. User/Group Requirements

      a. How will the network impact and improve user performance?

       Users have access to a limitless source, the internet. Therefore, they can use this limitless source to improve themselves.

b. How will the network allow users to grow within their current roles?

Thanks to networking designed by us, they can find better instructional materials to give students to educate them better and more qualified.

c. What type and amount of resources must be available to each group?

They should have equal access to the internet.

   4. Security

      a. What are the levels of security within the company?
    
      There should be 4 security levels. Like this;



      For P1, everyone in the campus has access. For P2, not everyone can have access. Only students, teachers and workers, IT team members, have access. For P3, teachers and workers have access. For P4, only workers have access.

      b. Are there different levels of security when dealing with outside sources?
      Yes. The security should be like this;



c. What is the physical security in the company?

The school’s servers are in a room and the room is only accessible by a personnel who has high-level access. 

    5. Fault Tolerance

               a. If the company had a major network failure, what would the impact be?

               If the school had a major network failure, the system wouldn't stop because we use mesh topology. Every point in the mesh topology is directly and indirectly connected to each other. Therefore, if there would be a problem in a line between 2 points, they continue to transmit data over other points. Data transfer does not pause in mesh topology.



b. How fast does the network need to be repaired in the event of a failure?

As soon as possible because education continues.

c. How critical is fault tolerance and redundancy for this network?

Since we are using the mesh topology, our fault tolerance and redundancy are not very critical. In case of any systematic problem, network traffic will not be interrupted because all points in the system are connected to each other. In case of any device failure, the settings can be backed up and transferred to the new device as it is. Since we are using the mesh topology and considering our economy, we did not want to use the point-to-point pair cable laying method for network traffic redundancy. We believe that we can continue the network traffic smoothly, thanks to the requirements and provides of the mesh topology.

    6. Existing Network Architecture

               a. Does the company have an existing network?

               Yes, they have. However, they have a lot of complaints lately that they are slow and break down just when you need it.

b. Can that network be successfully upgraded or retained?

To answer this question, we need to know the current network exactly and we need the answers for these questions.

●       What type of line do they use in the current network?

●       What is the design of the current network?

●       What parts of the current network should improve?

               The number of  questions can be more.

c. What would be the impact of replacing the legacy network?

If we change the legacy network completely, the price increases but we will have a better network. If we change some parts of the legacy network, the price is not as expensive as changing the legacy network completely but the quality is not the same, which means it would be  better than old but not better than completely new network. 

    7. Management

               a. How much time and resource management is necessary to maintain the network?

               This changes according to whether we use a completely new network or changing some parts of the legacy network. Secondly, we need more time and resources to manage it.

               b. What level of network management does the company expect?












This is the detailed plan about our network design. 




They want a system where all computers and other devices will be on the same LAN, but all campuses network traffic will remain local, and all users can use it at the same speed.We consider WAN and LAN and BYOT in networking and different design style networking, like mesh and point to point, while we are creating the network.


North campus has three buildings. Two of them are 5 floor-buildings and the other one has 3 floors. The distance between buildings is 25 meters.

This campus has  6 classes, 2 labs, 6 executive offices and 3 connection rooms, which is the room where the server and router are in and only personnel who have high-level access can enter the room.  We use mesh style for this campus. In this campus, there are 60 computers, 14 access pointers,3 switches and 1 router. We don’t want to use a hub because we can keep a MAC address with a switch and this makes progression faster, which the customer wants.

East and West campuses have the same design. Each of them has 7 classes and 1 lab which has 20 desktops. There are 4 executive offices and 4 connection rooms. In each campus, there are 62 computers, 34 access pointers, 8 switches and 2 routers. We use mesh style for this campus.

Last campus is South campus and has two buildings which are 4 floors. The distance between buildings is 30 meters.  It has 4 classes and 1 lab. There are 40 desktops in the lab. Also, there are 17 access points, 2 switches, 1 router. We use point to point style for this campus but we also connect them with each other because we want to continue to share data even if there is a problem in the line that connects each building.

First of all, we decided to use Mesh Topology  between campuses  because in case of problems in the line between 2 campuses or buildings, they can continue to share data between each other. But we use both mesh and point to point style design networks for buildings in the campuses.

Then, to ensure every building has the same quality of internet we use a router for one building in each campus to get internet from modem under Firewall  and as customers demand, we use access points  to enable them to connect the wireless technology. We also add a phone line in some buildings, mentioning also examples of floor plans. We will use 320 meters of the 1400 meters of cabling for the connection between the buildings and the rest for the connection between the floors. We prefer switches for some floors especially in the labs floors because it is enough for required internet access speed and cheaper than a router.

To provide users with a better network we use cable between campuses and buildings because when they use cable, the duty of cable is one thing, however, if we would use wireless technology, its duty is more than one, therefore, the internet speed would not be good. We also use their old cable system and in some parts we use both fiber cables to provide faster access and CAT6 cable to provide internet access with an average 300 kbit/s and also their cable to decrease the cost.

We assume that 70 percent of 1254 people will use the internet actively at the same time,

(1254*70) /100 = 877.8,

Each user is connected to the internet with 2 divices,

877.8 * 2 = 1755 devices at the same time , 

Each user’s bandwidth: 10Mbps

The total bandwidth of our Internet provided by ISP:300 Mbps

Contention Ratio = 1755* 10 : 300 = 58.5:1 = 59:1

Therefore, with a contention ratio of 59:1 on a 300 Mbps internet,


 we guarantee 300 Mbps/59 = 5,084745762711864 ≈ 5,1 Mbps (640 KB/s) speed. 

 

Part 2- Working With Cisco Packet Tracer


    First, let's see the final work.
    










    These images are belonged to our 4 main campus. To create this, there are several steps.

You should select your devices and their places.
You should connect them correctly. I advise you to use an automatic connection if you don't know which cable you should use.
You use cable computer to switch, or access point to switch or switch to switch. However, when you connect switch to router, you should do some settings.
First, you should use correct port in your router. Your router should be like in "physical" part;

    This ports is for connection between swtich to router.



     This ports is for connection between router to router. We use console connection and it needs this port and serial cable.

    Then, you should go "config" part in your router. You should select the interface that you use. In our case, we use gigabitethernet for connection between switch and router. It is necessary to give IP address and click on "Port status".  You do this process how many switch you use. Then, you should go back your computer that connected with a switch or access pointer. Go config and give IP address. You can give IP address by changing the last number of the router IP adress. 

    DO NOT USE THE SAME IP ADDRESS OR 0.

    Then, do the same operation with other devices in a campus. If you want to use server or modem, you should prefer to use gigabit ethernet to give IP address.

    After finishing one campus and doing the same operation in other campus, it is time to connect each campus.
   



    You use a serial cable to connect each campus. Go your any router and go "config" part. Here we use static routing. To do this, you should go interface and select one of the serial part which you use. You give IP address them but you should use like 11.0.0.1 (the last "1" representing north campus). You should give number according to a system. 

    Our system is order campus, devices and give the user devices this number but at the and change the last one. What this means is, your user device's number can be like North PC 15122 IP address. Each number represent campus and devices to reach the user devices.

    After you give IP address to serials, you should go RIP in Routing. You enter every serial and router IP address here but the last number must be 0. After that, go static.
   
    Network   = Router IP address that you want to reach
    Mask        = Under the Router IP address that you want to reach^
    Next Hop = Router serial' IP address that you want to reach

    It is important that you must connect serial cable to the same number port. If you connect serial 0/0/0 port, you should connect serial 0/0/0 in another router.

    You do this operation for every router. Then you can send ping.

    Important Note= When you send first time message, you see "failed" but if you try it again you see "successful". Every time your first message will be like that.

Part 3- Sending Message or Ping In Cisco Packet Tracer
    You can send message with click this icon;


    You select the 2 devices. First devices is for sending message and second one is for receiving it.

    Or you can write it in command prompt. First select your devices one for sending and one for receiving. You should know the device's IP address that you send ping. Go the device that you send ping and select "desktop" part. Then click "command prompt". Write ping IP address (for receiving computer) and click enter.


    
Thank you for reading our project 
Cetgiller
Reference

https://security.berkeley.edu/education-awareness/what-your-role-protecting-berkeley-campus-data
https://www.scnsoft.com/blog/3-levels-corporate-network-security
https://www.fool.com/the-blueprint/network-diagram/
CET 314 lesson
https://giphy.com/
 
