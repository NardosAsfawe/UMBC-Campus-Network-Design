# UMBC-Campus-Network-Design


<P1>The admin building has ten floors which consists of a lecture room, conference rooms, staff and faculty offices. The topology that would serve best the admin building is a star topology in which it makes it easier to manage and control the network as well as to achieve scalability. While designing the hierarchical network structure for this building, our team decided to approach the three layers keeping in mind how the building comprises several offices. 
For the access layer, using switches would be the optimum choice to connect several access points on each floor. 
As for the distribution layer, we decided to use layer 3 switches because they can filter broadcast traffic, and they allow different VLANS, which are deployed to create separate networks among the different offices and departments to ensure security, to communicate with each other. Additionally, since these offices handle sensitive information, it is important to prioritize security. Moreover, to guarantee a reliable connection and redundancy, we will deploy a pair of routers.
Lastly, from the distribution layer, it will connect to the core layer of the campus, which is located in the data center. 
</P1>

<h1> Logical Diagram </h1>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/D2.jpg)

<h1> Ground Floor </h1>
<p1>mainly contains mechanical areas, elevator spaces, and access to the utility tunnel that connects it with the rest of the campus. There are a total of 12 ports on this floor. 
Since this floor does not contain multiple rooms, it will be sufficient to use 2 Ubiquiti Unifi UAP-AC-PRO access points. And a Catalyst 3650-24TS (24 ports) switch will be used to connect all the ports. Additionally, for the access layer, one switch will be used to connect with the distribution layer.
The distribution layer will be placed here, where the rest of the access layer switches come to connect with the layer 3 switches. And finally they connect with the core layer of the campus network which will be located in the data center.
</p1>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/Ground_floor.png)

<h1> First Floor</h1>
<p1>This floor has a lecture room, lounge areas, Cust Areas, Elec Area, and Mech Areas. It has a total of 27 ports. In order to provide a wireless connection, we will deploy Ubiquiti Unifi UAP-AC-PRO access points. 3 in the Lecture room, 2 on each side of the Lounge area. In total there will be 7 access points for this floor to ensure wireless connectivity. And a Cisco Catalyst 3650-48T switch will be used to connect all the ports. Additionally, for the access layer, one switch will be used to connect with the distribution layer.
</p1>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/first_floor.png)

<h1> Second Floor</h1>
<p1>This floor contains staff offices, a conference room, staff services, and telecommunication cabinet. It has a total of 119 ports. In order to provide a wireless connection, a total of 5 Ubiquiti Unifi UAP-AC-PRO access points will be placed in different parts of the corridor. And 2 Cisco Catalyst 3650-48T switches will be used to connect all the ports. Additionally, for the access layer, one switch will be used to connect with the distribution layer.
</p1>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/2nd_floor.png)

<h1> Third Floor</h1>
<p1>This floor contains staff offices, conference rooms, staff services, electric area, and telecommunication cabinet. It has a total of 185 ports. In order to provide a wireless connection, a total of 5 Ubiquiti Unifi UAP-AC-PRO access points will be located in different parts of the corridor. And 4 Cisco Catalyst 3650-48T switches will be used to connect all the ports. Additionally, for the access layer, one switch will be used to connect with the distribution layer.
</p1>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/3rd_floor.png)

<h1> Fourth Floor</h1>
<p1>This floor contains staff offices, conference rooms, staff services, and telecommunication cabinet. It has a total of 123 ports.In order to provide a wireless connection, a total of 5 Ubiquiti Unifi UAP-AC-PRO access points will be placed in different parts of the corridor. And 3 Cisco Catalyst 3650-48T switches will be used to connect all the ports. Additionally, for the access layer, one switch will be used to connect with the distribution layer.
</p1>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/4th_floor.png)

<h1>Fifth Floor</h1>: <p>This floor contains staff offices, conference rooms, staff services, and telecommunication cabinet. It has a total of 127 ports. In order to provide a wireless connection, a total of 5 Ubiquiti Unifi UAP-AC-PRO access points will be deployed in different parts of the corridor. And 3 Cisco Catalyst 3650-48T switches will be used to connect all the ports. Additionally, for the access layer, one switch will be used to connect with the distribution layer.</p>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/5th_floor.png)

<h1>Sixth Floor</h1>: <p>This floor contains staff offices, conference rooms, staff services, and telecommunication cabinet. It has a total of 133 ports. In order to provide a wireless connection, a total of 5 Ubiquiti Unifi UAP-AC-PRO access points will be deployed in different parts of the corridor for optimum connectivity. And 3 Cisco Catalyst 3650-48T switches will be used to connect all the ports. Additionally, for the access layer, one switch will be used to connect with the distribution layer.</p>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/6th_floor.png)

<h1>Seventh Floor</h1>: <p>This floor contains staff offices, conference rooms, faculty offices, a study room, and telecommunication cabinet. It has a total of 125 ports.In order to provide a wireless connection, a total of 5 Ubiquiti Unifi UAP-AC-PRO access points will be deployed in different parts of the corridor for optimum connectivity. And 3 Cisco Catalyst 3650-48T switches will be used to connect all the ports. Additionally, for the access layer, one switch will be used to connect with the distribution layer.</p>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/7th_floor.png)

<h1>Eighth Floor</h1>: <p>This floor contains several staff offices, conference rooms, staff services, and telecommunication cabinet. It has a total of 135 ports. In order to provide a wireless connection, a total of 5 Ubiquiti Unifi UAP-AC-PRO access points will be deployed in different parts of the corridor for optimum connectivity. And 3 Cisco Catalyst 3650-48T switches will be used to connect all the ports. Additionally, for the access layer, one switch will be used to connect with the distribution layer.</p>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/8th_floor.png)

<h1>Ninth Floor</h1>: <p>This floor contains staff offices, a conference room, and staff services. It has a total of 121 ports. In order to provide a wireless connection, a total of 5 Ubiquiti Unifi UAP-AC-PRO access points will be deployed in different parts of the corridor for optimum connectivity. And 3 Cisco Catalyst 3650-48T switches will be used to connect all the ports. Additionally, for the access layer, one switch will be used to connect with the distribution layer.</p>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/9th_floor.png)

<h1>Tenth Floor</h1>: <p>This floor contains staff offices, conference rooms, staff services, electric area, and telecommunication cabinet. It has a total of 133 ports. In order to provide a wireless connection, a total of 5 Ubiquiti Unifi UAP-AC-PRO access points will be deployed in different parts of the corridor for optimum connectivity. And 3 Catalyst 3650-48T switches will be used to connect all the ports. Additionally, for the access layer, one switch will be used to connect with the distribution layer.
</p>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/10th_floor.png)
