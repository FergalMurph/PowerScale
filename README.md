# PowerStore Management

In this module, you will login to the PowerStore interface called PowerStore Manager. You will review the settings of the PowerStore system, create custom dashboards, and review the system view.

#### PowerStore Manager Dashboard


1\. If you are starting the lab with this section, you will have to first login to the PowerStore Manager. Double-click **PowerStore** on the desktop.

Once the PowerStore Manager opens, notice that the first thing that is shown is a login banner message. We will show later in this lesson how to enable and customize it.

Login to PowerStore Manager with the following settings:

- User: **admin**
- Password: **Password123!**

Click **"Log In"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/f9bf8e86-ae06-41a8-83de-9bedc7a24c65/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=524,463)


Tip: After you log into PowerStore Manager, you will see the main Dashboard page. From this page you can quickly see high level information about your PowerStore system and be able to drill down to find more details as necessary. The Dashboard page is meant to give a quick glance into the current status of the environment and bring to attention any issues that should be addressed by the administrator.


2\. The Dashboard page utilizes tabs to show various system information separated by top level category including **Overview, Capacity**, and **Performance**. Let's start with the Overview tab.

The **Overview** tab includes the following information:

- The number of appliances included in the PowerStore cluster
- The number of Critical, Major, and Minor Alerts
- The number of items selected to be watched on the Watchlist

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/5d4e1af9-e55c-4ebb-b20d-a40d778ca8b6/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0)


3\. The **Overview** page itself includes additional overall system information to give a brief holistic view about the system and provide quick links to associated pages.

The **Overview** tab allows the end user to view the following information:

- The number of Volume Groups, Volumes, Hosts, and Virtual Machines
- The number of File Systems, SMB Shares, NFS Exports, and NAS Servers
- A short list of Alerts separated by Critical, Major, Minor, and Info categories
- Selecting View All Alerts directs the user to the full page of alerts
- A Watchlist of user-selected storage resources to monitor from the Dashboard page
- The Cloud IQ Health Score

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/0dbae0c9-fe5a-402b-83c3-b462f6cdc2bc/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0)


4\. Within the **Overview** tab, the **Cloud IQ Health Score** provides customers with a high-level overview of their cluster’s health. By hovering over the gear icon in the **System Health** card, users can view a pop-up with more details about current issues. Users can click on the pop-up to view the alert details.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/f802ed61-c34b-41be-a05a-62b80aada504/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0)


Tip: Tip! Each blue link is a clickable link to the associated page. Feel free to click on each link and then come back to the Dashboard page by clicking Dashboard in the top left of the interface


5\. Next, click **"Capacity"** tab. This tab includes the following information:

- The percentage of used storage space compared to available storage space for the cluster
- The amount of free space in the cluster
- The amount of physical capacity installed in the cluster

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/5eb7da48-7392-44cd-a40a-16ffad4ce370/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0)


6\. The **Capacity** page provides additional information about the system related to capacity including historical usage and data savings from data reduction methods.

The **Capacity** tab allows the end user to view the following information:

- Physical capacity separated by used and free space
- Historical usage over time including capacity usage forecast
- Data savings from snapshots, thin provisioning, and data reduction
- Top storage resources in relation to consumed (used) capacity

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/c991bf90-aaf0-4a92-8131-646f7de887fa/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=1459,146)


7\. Click **"Performance"** tab

The **Performance** tab allows the end user to view the following information:

- The average latency of all storage resources within the system(s) in the cluster
- The total amount of IOPS for all storage resources within the system(s) in the cluster
- The total bandwidth for all storage resources within the system(s) in the cluster

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/d7c4c8cb-0765-47fb-9ad8-cdaa6a1aef67/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0)


8\. The **Performance** page provides additional information about the system related to performance including historical performance statistics as well as a mapping of Alerts in the same timeline for easier troubleshooting.

The **Performance** tab allows the end user to further narrow down and customize viewing of performance information such as:

- Historical summary of Latency, IOPS, and bandwidth in graph form
- Summaries available in last hour, 24 hours, 1 month, or 2 years
- Mapping of alerts in the same graph (if no alerts are shown, change the For: to 24 hours)

If the default time ranges for the graphs are not sufficient, you are able to zoom into smaller portions of the chart to get a smaller range and more details. **Click (hold)** into the Performance graph and **drag** into a smaller portion of the graph.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/452d33d8-818c-4e3d-943b-e5f6f91d2ed7/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=582,364)


9\. Notice how the performance graph zooms in for the select range.

Click **"Reset Zoom"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/98e098f0-9572-404f-884b-89880cc0d7d9/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=88,291)


#### Verify PowerStore Manager Settings


Tip: We explore the various options available such as the login banner as well as various cluster settings in this section.


10\. At the top right of the PowerStore Manager interface, click the **Gear** icon labeled **"Settings"** to open the Settings Menu.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/aa7ce77b-5163-4dad-97ee-45b4fa2ccf45/File.jpeg?tl_px=0,0&br_px=1365,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=1028,23)


11\. Take a minute to review the left navigation pane, which organizes various settings by category like **Cluster** and **Security**. From within the Properties page, notice the attributes shown:

- Cluster Name
- Cluster Time
- Global ID
- Primary Appliance
- Primary Node on Appliance

Click **"Login Message"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/e7cef9ba-2f52-40e9-8ac4-82965e28bb2b/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=25,464)


12\. By default, the login message is disabled. We have enabled it and provided a message beforehand.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/edb7952f-6f83-4a42-99e8-726c196ce3f3/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0)


13\. Customize the message to state the following:

The use of this system is intended for authorized user ONLY.

Click **"Apply"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/33855a50-66c1-4592-9820-40287f598706/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=293,374)


14\. Once the message is updated, log out by selecting the user icon on the top-right and click **"Log out"**.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/f3cc250d-6d29-4b32-b03f-cb79eef6039c/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=906,121)


15\. Click **"Log Out"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/a7cb347b-d1e0-42f6-a111-aee41ac448cd/File.jpeg?tl_px=0,0&br_px=1365,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=702,317)


16\. Once the PowerStore Manager opens, notice that the login banner now shows the message provided in the previous step.

Login again with the same credentials used previously:

- User: **admin**
- Password: **Password123!**

Click "**Log In"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/d9b3e2c3-3846-4269-a089-4cb8d1c20b28/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0)


17\. Click **"Infrastructure Services"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/50ad7ded-cbba-427b-8998-49fba893bdda/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1365,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=42,480)


18\. DNS helps the system resolve host names in your environment. For this lab, **192.200.53.108** and **192.200.254.66** have been configured as the DNS servers.

System time can be synchronized across multiple disparate systems by using NTP servers. For this lab, NTP has been configured on the system with the addresses **192.200.53.108** and **192.200.254.66**.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/96b4f386-4f69-4bcf-8cdb-9aac3ada6647/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=36,691)


19\. Click **"Support Connectivity"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/67bd2a3c-8a79-4832-8287-d70475edacd5/File.jpeg?tl_px=0,0&br_px=1365,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=21,427)


20\. Support connectivity allows the PowerStore System to connect back to Dell Support services so that troubleshooting can be more easily performed in the event of issues and time to resolution is shortened.

Click **"Connection Type"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/1de30759-e23e-40b6-930e-66d0c3842ccd/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=387,226)


21\. Verify that Support Connectivity is in an **Enabled** state and the **Connect Directly** status is **Good**. Also, notice that **Connect to CloudIQ** is automatically selected. CloudIQ is a no-cost cloud native application that proactively monitors Dell storage, including PowerStore. For more information on CloudIQ, please refer to hands on lab HOL-0511-APEX AIOps Observability.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/2a85b500-2244-450e-b98a-431722569897/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0)


#### Data In Place Upgrade


Tip: PowerStore supports the Data In Place Upgrading from an earlier **PowerStore x00 model** to an equal or higher **PowerStore x200 Model.** PowerStore also supports the upgrading of the same family to a higher model for the **PowerStore x200 models.**

Note that while this demo provides a comprehensive overview, specific details, and step-by-step instructions are available in the PowerStore Installation and Service Guide. For those looking to delve deeper into each stage of the DIP upgrade process or undertake the upgrade themselves, consulting the guide is strongly recommended.


22\. In the top navigation pane, Navigate to **"Hardware"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/25364898-bba3-4b9d-b751-a652b50dd7a5/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1365,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=600,23)


23\. On the **Hardware** page, the **Appliances** tab is shown by default which displays all appliances (systems) that are configured under the same PowerStore cluster management interface. A single PowerStore cluster can manage up to 4 appliances.

To perform a Data In Place Upgrade select the **PowerStore 1000T** System 

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/9a25a37a-c429-475a-ae79-4b2eb69a8661/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=4,225)


24\. 
Click **More Actions &gt; Data-In-Place Upgrade**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/f3ae307c-5fba-4458-ad05-b4af936c0c17/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=260,266)


25\. Select the Model Type as **PowerStore 1200T**  

Click **"Next"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/e2d0f9fd-2a8e-4638-8227-205f56900729/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=1028,560)


26\. Click **"Perform Validation"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/b2e287be-27c6-4318-8a04-506fd7ef6403/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=371,98)


27\. The wizard performs and validates that all prerequisites are met for the Data In Place Upgrade. Once the Validation has Passed

Click **"Next"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/63c8e496-4b34-4f69-8aec-ada3332f4021/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=1028,559)


28\. Note the important information on the summary page. 

To start the Data In Place Upgrade process click **"Finish"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/29880eef-4a69-4085-ad20-44d8555a681f/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=1021,557)


29\. Once the **Hardware Upgrade** Job has started, PowerStore will provide multiple Alerts and Banners instructing the user of the next steps and when physical intervention is needed for Hardware to be upgraded.

Being a simulator the upgrade will take a few minutes to complete and will cycle through a few of the alerts and banners.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/b656ac89-67a2-443f-b17e-bb63cf813051/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0)


30\. Once the Hardware Upgrade job has completed you will see that the once **PowerStore 1000T** reports as successfully upgraded and reflects the newly chosen model of **PowerStore 1200T**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/76437cf4-a1f5-4535-a125-38a035faa3d8/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0)


#### Review System Hardware View


Tip: To view the status of the physical hardware for your PowerStore system, you navigate to the Hardware view page. Here, you discover information about your system.


31\. Proceed to click the **5200T-B** appliance.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/e7467aaa-b42f-4533-8c56-59f9e12a8b06/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=59,264)


32\.  In the details page of the selected appliance, notice there are five main tabs available to click: **Capacity, Performance, Alerts, Ports, and Components**. The Capacity and Performance tabs are similar to the Capacity and Performance pages on the main Dashboard, but are specific to the selected appliance. Feel free to check those tabs out. The Alerts tab will be investigated in a future module so let's skip that for now.

When ready, click on the **Components** tab.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/6567a6cf-461b-4401-a1a7-52667d4e488f/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=945,140)


33\. On the **Components** tab, the **Appliance Drive Summary** page is selected by default. This page shows a table with the total count of drives on the system divided by drive type including the drive size.

Click **"BaseEnclosure"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/98be16e4-e1ad-42c1-b110-20478f75aa6e/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=85,311)


34\. This page shows a graphical illustration of the front of the system with a left hand navigation pane listing all of the available drive slots. If there are attached expansion enclosures, the left hand navigation pane would list the expansion enclosure drive slots as well. Feel free to browse it.

Expand the Base Enclosure to see the full list of drives.

Select **"Drive_0_0_3"** drive slots to view more details for that drive.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/bc561065-dab4-46fd-962f-309eafc1ae4f/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=93,410)


Tip: **Note:** You can optionally select the NVMe Expansion Enclosure and view the drive slots and drives that are populated.


35\. As you can see in the details pane below the graphical illustration, there are additional details for the selected drive including:

- State
- Slot
- Type
- Capacity
- Part Number
- Serial Number
- Firmware
- Encryption Status

Also, notice there is a button called **Blink LED** which will blink the LED for the selected drive for easy identification in a physical data center. If no drive is selected, the **Blink LED** button will blink the LEDs for all the drives and other appliance LEDs for the appliance. This is helpful in cases where a system needs to be identified among many similar looking systems in the same rack.

When ready, click on the **Rear View** tab.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/34f6d4c1-8473-4802-bc58-addb92ddb583/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=120,136)


36\. The **Rear View** page allows the user to view hardware components from the back of the PowerStore system. This page shows a graphical illustration of the back of the system with a left hand navigation pane listing all of the components which can be individually selected.

Click on the **4PortCard** on **Node A** (bottom node) in the graphical illustration to get more information about that component. Note that the same component can be selected from the left-hand navigation pane.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/3b438348-79ac-4c28-9770-191258da2e98/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=370,291)


37\. As you can see, more details are shown for the selected component in the below details pane. Any alerts associated with the particular component would show up to the right as well.

Feel free to click on other components in this view. You can even click on individual ports to view additional details as needed.

When ready to move on, click on **Internal View** tab

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/5ad5a51e-1fc0-4621-8728-b440195bc915/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=220,134)


38\. The **Internal View** page allows the user to view internal hardware components of each PowerStore node (Node A and Node B). This page shows a graphical illustration of the internals of each node with a left hand navigation pane listing all of the components which can be individually selected.

Notice in the details of Node A that it shows the CPU information and total memory amount of that node which is helpful for reference.

Since Node A is already selected, click on **More Actions**.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/34666a55-5edc-4d9d-a11d-a67462898cca/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=51,168)


39\. Notice that a drop-down menu appears with two options: **Reboot** and **Power Down**. These service actions are useful when troubleshooting is required or graceful shutdown is needed. 

Click on **Power Down** to see the resulting dialog window.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/d0c9f216-845a-420e-81d6-7106750382e3/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=53,229)


40\. The resulting **Power Down Node** dialog window shows a warning that a service action is about to be performed and explains that the process may take several minutes to complete. There is also a link to instructions on Online Help for when the node needs to be powered back on. Notice that the service password is required when want to perform a power down action.

Being a demo simulator we will NOT power down the node.

Click **Cancel**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/34f23a1a-ec42-4ddc-9faf-c59acffa148e/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=603,512)


41\. Click on one of the fan modules in the graphical illustration to see more information about that particular component.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/943ee618-02b8-4c8f-82c6-676130736121/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=509,271)


42\. Similar to the other click-able components in the other tabs, more information is shown for the selected component. In this case, it shows the state of the fan module as well as the slot number and part number. All this information is helpful in the event the component becomes faulted and requires replacement.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-04-10/ae83d106-fb30-42e8-a4d6-fcda41d07241/File.jpeg?tl_px=0,0&br_px=1366,762&force_format=jpeg&q=100&width=1120.0)


43\. Congratulations! You have reached the end of this particular module.

Click **Close** in the top left corner of this script to return to the demo guide.
