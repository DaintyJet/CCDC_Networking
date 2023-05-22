# Cisco Packet Tracer Learning Scenario 1
**Getting Started**
We need to download the Cisco Packet tracer to start playing around with simulated networks. This can be done from <a href="https://skillsforall.com/learningcollections/cisco-packet-tracer?courseLang=en-US&utm_source=netacad.com&utm_medium=referral&utm_campaign=packet-tracer&userlogin=0">Cisco's Website</a>, the website may change as time goes on. But a simple google search should be able to solve this issue. Once we have navigated to this website we can <a href="https://skillsforall.com/course/getting-started-cisco-packet-tracer?courseLang=en-US">enroll</a> in Cisco's **free** course, and download the Packet Tracer.

We can download the packet tracer from the <a href="https://skillsforall.com/resources/lab-downloads?courseLang=en-US">download page</a> and follow the instructions listed there. We will need a **skills for all** account to validate the packet tracer install.

> This is self-note for a link to the course <a href="https://skillsforall.com/launch?id=ec0847b7-e6fc-4597-bc31-38ddd6b07a2f&tab=curriculum&view=e101fd3b-2d5c-587d-9d40-fcb2f0f1664e">Link</a>

## Packet Tracer Menues

**Files**: This menus allow us to open, close, and save new workspaces. Each version of Packet Tracer includes *Sample Sceneries* that we can view from this drop down

**Prefernces**: Customize interface, change font sizes, color and the font itself. We can setup a auto backup

**Main tool Bar**: undo Zoom in and out
**Secondary Bar**: select and delte objects
**Workspace tool bar**: 
* Logical - Logical connections between devices and how data flows
* Physical - The physical connections between devices (May not be as useful in our case)
  * This can be city or room sized representation

**Bottom Bar**: 
* Power cycle all devices
* fast forward or converge all protocols to their completion 
* Real Time - Real time in network as things happen
* Simulation - Control time and add packets 


Below all this we can see devices and links that we can add.
_______
**Empty Program**
<img src="Images/Empty_Program.png" alt="Cisco Packet Tracer Empty">
_______

## Creating a Network

We can utilize the symbols in the **Bottom Left** to select the devices we are going to include in the network. The Top row is the Category of devices, and the bottom row is the Sub Category - The sub catagories change based on the current category selected.

Below is an example of the Category and Sub Category.
<img src="Images/CandSubC.png">

## Connections
One **Important** category is the connections category, this is represented by the **lightning bolt**. Unless we know the connection type we are best off selecting the **automatically chose** option which is again the lightning bolt (in the right table)

This is shown below:
<img src="Images/Conn.png">

Once we have selected the connection type we can click on **any two** ***end devices*** to create a connection between them. Cisco Packet Tracer will utilize the **next open interface** on the device to create the connection.

Below is a connection in progress, **take note of the striped line between the laptop and wireless router**. 
<img src="Images/PrgCon.png">

To create a wireless connection between the laptop we need to do a few things, as by default it has a ethernet interface.
1. Click on the laptop icon. The interface below will appear.
    <img src="Images/Laptop1.png" width="500" height="600" >
1. Power off the laptop 

    <img src="Images/Laptop2.png" width="500" height="600">
2. Drag old interface out

    <img src="Images/Laptop3.png" width="500" height="600">
3. Drag new interface in

    <img src="Images/Laptop4.png"  width="500" height="600">
4. Power on the laptop

    <img src="Images/Laptop1.png" width="500" height="600">

## Device Configurations
### Physical Tab
This is the tab that we were interacting with **above**, it all allows us to power the devices on or off, and change out the network interface cards (NIC)

<img src="Images/RPhys.png" width="500" height="600"> 

### Config Tab
This tab allows us to make basic configuration changes to intermediate devices such as switches and routers without knowing the CLI commands, as this executes the necessary commands for us.

This shows us the commands run to configure the system - so it provides a nice way to learn some of the CLI Commands. **The CLI commands will have their own document**

<img src="Images/RConf.png" width="500" height="600">

### CLI Tab
This is a tab that allows us to interface with the device using the CLI, we need knowledged of the CLI commands and Cisco's Internetworking Operating System.

<img src="Images/RCLI.png" width="500" height="600">

## Attributes  
This contains atributes about the specified device such as cost, power supplies ect. This will not be too useful to us.

<img src="Images/RAttr.png" width="500" height="600">

### Desktop View
This is available to any devices that would have a desktop GUI interface. This allows us to interact with and configure those devices. We can even interact with a simulated terminal!

<img src="Images/DeskTop.png" width="500" height="600">

### Services
Servers have additional functionality over desktops and laptops that can be configured in the services tab. 

<img src="Images/Server.png">


## Packet Tracer Tutored Activity (PTTA)
These are structured, and guided challenges. We get to select the depth and number of hints that we are given at the start of the PTTA.


### Physical Mode
Right click a device, we can inspect the front or back of the device, this can be used when we are cabling the device. In this case we can connect to specific interfaces or ports. 


We can **switch** between the logical and physical mode using the **Shift-L** and **Shift-P** shortcuts in addition to the buttons on the GUI.

In cities there are some buildings that are defined which we can enter.

**Copper Straight Throughs** Are used for ethernet connections
**Consol Cables** are used for RS232 and other consol (serial?) connections,

### Activity 
There are two cities connected with a submarine cable, listed with a ISP and solid Black Line. In each city there is a building defined with some number of devices in them. These devices can be connected with Ethernet (or some equivalent) **Solid Lines** or Wireless **Striped Lines** links. Once we are able to access the physical display of the Office, we are able to connect devices and modify their configurations.




