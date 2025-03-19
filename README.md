# Network-Building-With-Cisco-RIPv2

<p align="center">
    <a href="https://youtu.be/w5Kgd4MYS98">
        <img src="https://img.icons8.com/color/48/000000/youtube-play.png" width="50">
    </a>
    <br>
    <strong>Click Above For YouTube Demonstration</strong>
</p>





<h2>Description</h2>
This project features a virtual network simulation of three Cisco 3600 series routers using GNS3, a free and robust network simulation tool. The network is configured with Cisco’s proprietary Routing Information Protocol version 2 (RIPv2) to demonstrate efficient routing operations. Each router is also equipped with a loopback address to enhance network reliability and stability. This setup highlights advanced network configuration techniques and the practical application of dynamic routing protocols in an educational and demonstration context.
<br />

<h2>Objectives</h2> 

- <b>Demonstrate the configuration and functionality of the Routing Information Protocol version 2 (RIPv2).</b>
- <b>Illustrate the setup of virtual loopback interfaces to ensure stable routing through the network.</b>
- <b>Show competence in network simulation and configuration using GNS3.</b>


<h2>Tools and Technologies</h2>

- <b>GNS3: Network simulation software used to virtualize the network.<b/>
- <b>Cisco 3600 Series Router Images: Required for simulating the specific Cisco router configurations.<b/>
- <b>RIPv2 Configuration: Dynamic routing protocol setup on all routers.</b> 

<h2>Environments Used </h2>

- <b>Windows 11</b>
  

<h2>Project walk-through:</h2>

<p align="center">
Network Diagram: <br/>
<img src="https://i.imgur.com/CPijL8i.jpeg"/>
<br />
<br />
Open GNS3 and choose local server, then click next:  
<img src="https://i.imgur.com/CDtO620.png" >
<br />
<br />
Choose the same options as the image below and upload the Cisco 3640 router image. Then click next.
<img src="https://i.imgur.com/GbIBXz3.png">
<br />
<br />
For general routing purposes choose the network adapter NM-1FE-TX for slot 0 and slot 1.
<img src="https://i.imgur.com/yletXXP.png">
<br />
<br />
Drag and drop 3 of the Cisco routers and form a triangle shape. 
<img src="https://i.imgur.com/aJABEWx.png">
<br />
<br />
Click the bottom left box with the red x such as in the image below and connect each router to the other using the FastEthernet. Once all routers are connected start the devices by hitting the green play button on the top. 
<img src="https://i.imgur.com/xGSuhz4.png">
<br />
<br />
Once all of the devices are on and running indicated by the green dots on the wires connecting the routers, click Consol connect to all devices as in the image below.
<br />
<img src="https://i.imgur.com/q8jd9oO.png">
<br /> 
<br />
<img src="https://i.imgur.com/go62rqJ.png">
<br />
<br />
Enter all the commands for each router as shown in the image below. 
<img src="https://i.imgur.com/KG9IK1v.png">
<br /> 
<br />
This is how the network output should look after entering the show IP interface brief command for each router. 
<br />
<img src="https://i.imgur.com/uFno9Qh.png">
<br />
<br />
Ping networks to test connectivity and make sure everything is working. 
<img src="https://i.imgur.com/lQ9IGem.png">
<br />
<br />
<img src="https://i.imgur.com/P6UNJaJ.png">
 
