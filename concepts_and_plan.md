What is this?
=============
This project will configure cloud-like system such as AWS/MS Azure service.
Still, I have no background-information about Cloud system, so in this project, there will be some study-like side project as well.<br>
My main goal is to learn more about technical structure of cloud system, and to implement my own cloud system.

Basic Concepts
===============
This project has total of three main goals.
1. Allocate system with limited resource per person.
2. Initialize monitoring system<br>- High Load Alert<br>- Security Alert
3. Create web-based monitoring/managing system.

1: Allocate system with limited resource per person
---------------------------------------------------
Basically, the plan is:
1. Limit CPU Usage(eg: 2core per - person)
2. Limit RAM Usage(eg: 4GB per - person || swap)
3. Limit GPU Usage(eg: 100 cuda core per - person)<br>(I don't even know whether this kinda thing work tho. Have to research/find it if limiting gpu usage is possible.) --> Based on NVidia GPU
4. After all those 3 things are completed, add a configuration option.<br>
   eg: n-core per person.

2: Initialize Monitoring System
-------------------------------
As we know, monitoring system and managing is same priority as developing back-core stuff. So in the plan, we will implement monitoring feature every single work(something like implementing limit-cpu-usage)-update.<br>
This is to handle URGENT situation in cloud server ASAP and investigate cause of situation.

3: Create web-based monitoring/managing system
-----------------------------------------------
As I said on 2(initialize monitoring system), I will make monitoring system as I work core function, but in console-way. After all system are implemented, there is a plan to make those console-managing system to WEB-based managing system.<br>
Using GUI instead of CLI is way-more efficient to normal private user.


Target System
==============
<b><u>Those systems are still planning, things may vary.</u></b>

For Alpha-Testing Device(1)
-------------------------
CPU: i7-9850H<br>
RAM: DDR4-32GB<br>
GPU: RTX2060<br>
P.N: ROG Zephyrus M GU502GV<br>
OS: Windows 10 Home, WSL2 with Ubuntu 18.04(Insider Preview)<br>

For Alpha-Testing Device(2)
---------------------------
CPU: ARM Cortex-A53<br>
RAM: LPDDR2-1GB<br>
GPU: Integrated<br>
P.N: Raspberry Pi 3 B
OS: Ubuntu Server 18.04(64-bit)<br>

For Private Research-working
-----------------------------
CPU: i7-6800K(Overclocked to 4.3Ghz)<br>
RAM: DDR4-8GB<br>
GPU: ROG STRIX RX460(Overclocked)<br>
P.N: Custom-Built PC<br>
OS: Ubuntu 18.04<br>

For Embedded Edition - Slaves (Provided by Research Laboratory)
-------------------------------------------------------
CPU: ARM A57(Quad-Core)<br>
RAM: LPDDR4-4GB<br>
GPU: Maxwell Architecture with 128 Cuda Core<br>
P.N: NVidia Jetson Nano<br>
OS: NVidia - Provided Ubuntu 18.04 <br>

For Embedded Edition - Master (May Provided by Research Laboratory)
-------------------------------------------------------------------
CPU: ARM v8.2(8-core)<br>
RAM: LPDDR4-32GB<br>
GPU: Volta GPU + Tensor Cores --> Total 512 Cuda Core<br>
P.N: Jetson AGX Xavier<br>
OS: NVidia - Provided Ubuntu 18.04 <br>

Research(Project) Laboratory
============================
Department of Electrical and Electronic Engineering, <br>
Research Laboratory for Value Diffusion Activities.<br>

Research(Project) Member
===============
Jason. HW. Kang
-----------
Dept: Department of Computer Science<br>
Role: Leader of this project.<br>
Github: https://github.com/KangDroid