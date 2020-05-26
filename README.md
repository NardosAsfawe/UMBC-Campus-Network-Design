# UMBC-Campus-Network-Design


<P1>The admin building has ten floors which consists of a lecture room, conference rooms, staff and faculty offices. The topology that would serve best the admin building is a star topology in which it makes it easier to manage and control the network as well as to achieve scalability. While designing the hierarchical network structure for this building, our team decided to approach the three layers keeping in mind how the building comprises several offices. 
For the access layer, using switches would be the optimum choice to connect several access points on each floor. 
As for the distribution layer, we decided to use routers because they can filter broadcast traffic, and they allow different VLANS, which are deployed to create separate networks among the different offices and departments to ensure security, to communicate with each other. Additionally, since these offices handle sensitive information, it is important to prioritize security. Moreover, to guarantee a reliable connection and redundancy, we will deploy a pair of routers.
Lastly, from the distribution layer, it will connect to the core layer of the campus, which is located in the data center. 
</P1>

<h1> Ground Floor </h1>
<p1>mainly contains mechanical areas, elevator spaces, and access to the utility tunnel that connects it with the rest of the campus. There are a total of 12 ports on this floor. 
Since this floor does not contain multiple rooms, it will be sufficient to use 2 Ubiquiti Unifi UAP-AC-PRO access points. And a Catalyst 3650-24TS (24 ports) switch will be used to connect all the ports. Additionally, for the access layer, one switch will be used to connect with the distribution layer.
The distribution layer will be placed here, where the rest of the access layer switches come to connect with the layer 3 switches. And finally they connect with the core layer of the campus network which will be located in the data center.
</p1>

![](https://github.com/NardosMe/UMBC-Campus-Network-Design/blob/master/Ground_floor.png)
