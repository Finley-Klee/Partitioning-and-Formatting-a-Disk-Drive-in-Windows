# Partitioning-and-Formatting-a-Disk-Drive-in-Windows
My work on the lab from the Google IT Support Specialist certification in module 4 of Operating Systems and You: Becoming a Power User

<h2>Description</h2>
In this lab, I learned how to partition and format a disk drive in Windows. Partitions are important because a file system can't function without one. When you acquire a new disk drive, at least one partition is required in order to be able to write files to the file system. Different partitions can then have different file formats, depending on their purpose. For example, a disk partition that acts as a swap for your main memory may have a different file format than the default user-facing file systems. Partitions, like those used for system recovery, may also have different file formats. 

<h2>Utilities Used</h2>

- <b>Windows Control Panel</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Project walk-through:</h2>

- <b>Navigating to Disk Management</b>
<p>In the Windows environment, I am using Disk Management to partition and format a new disk. First, I navigate to the Disk Management window from the Windows start menu.</p>
<br>
<p align="center">I start by clicking on the Windows start menu and selecting the control panel.<br/>
  <img src="https://github.com/user-attachments/assets/d2f1bdda-a819-4035-a321-7ba0e8ec1078" height="80%" width="80%" alt="A black homescreen background with the windows start menu in the bottom left corner."/>
  <br />
  <br />
 While in the control panel, I navigate to System and Security, then Administrative Tools.<br />
  <img src="https://github.com/user-attachments/assets/f0470358-55ac-43da-b12a-77c2f7df52e8" height="80%" width="80%" alt="the administrative tools option is highlighted lightly in blue at the bottom of a list of options including security and maintenance, windows defender firewall, system, and power options."/>
  <br />
  <br />
  In the administrative tools menu, I click on Computer Management.<br />
  <img src="https://github.com/user-attachments/assets/e71f96f6-2352-497f-90f6-ebbec9c11706" height="80%" width="80%" alt="in the administrative tools window, computer management is selected in light blue from a list of about 20 options."/>
   <br />
  <br />
  Then, in the left panel under Storage, I select Disk Management.<br />
  <img src="https://github.com/user-attachments/assets/e16be77e-61d6-486d-926b-698af62c5d00" height="80%" width="80%" alt="the disk management window is divided into several smaller sections. The the right and left of several middle panels, are vertical sections. The left section has a file tree for navigation, and the right section has actions. The middle sections are stacked from top to bottom. The top middle section lists the disks C, Disk 0 partition 2 and Disk 1 partition 2. The bottom two sections in the middle of the window are Disk 0 and Disk 1 showing their size and more information about the disks."/>
</p>
<br />
<br />

- <b>Mounting and Partitioning the Disk</b>
<p>Now that I have navigated to Disk Management from the control panel, I'm ready to mount the new disk drive and create a new partition on the disk.</p>
<br>
<p align="center">At the bottom of the Disk Management screen I can see two disks, one of which contains unallocated space, and is labeled "offline". To mount this disk, I right click on the left part of the disk and select "online". <br/>
  <img src="https://github.com/user-attachments/assets/07eb7190-f735-4974-a3bc-47008dcfc51e" height="80%" width="80%" alt="at the bottom of the middle section of the window a drop down menu with online selected in blow hovers over the Disk 1 section."/>
  <br />
  <br />
  The disk is mounted and automatically assigned the next letter available, in this case D:\ <br />
  <br />
  <br />
 To create a new partition, I first need to shrink the volume by right clicking on the disk and selecting "shrink volume"<br />
  <img src="https://github.com/user-attachments/assets/5947cf62-fb09-4210-8a91-20e71503e998" height="80%" width="80%" alt="a pop up window hovers over the bottom middle section with shrink volume highlighted in blue."/>
   <br />
  <br />
 I want to split the disk into two partitions, one of 30GB and one of 20GB, so in the box for listing the size to shrink the disk I enter 20480MB, and click "shrink"<br />
  <img src="https://github.com/user-attachments/assets/df1b7bb7-8372-4987-bf2d-4afa17868e70" height="80%" width="80%" alt="the shrink window with the third blank selected and the number 2048 in the box."/>
   <img src="https://github.com/user-attachments/assets/303d1105-112e-48c5-9738-55239b6a08cc" height="80%" width="80%" alt="back to the main disk management window, the bottom middle section showing disk 1 now has a section to the right of the info  with a black banner at the top of the box and with text that reads 20.00 GB Unallocated."/>
   <br />
  <br />
  Now to create the partition I right click on the new unallocated space and select "new simple volume"<br />
  <img src="https://github.com/user-attachments/assets/462ba6b8-b33a-4e8a-8b72-93bb13f108e6" height="80%" width="80%" alt="the unallocated box now has diagonal cross hatching, and there is a pop up window hovering above it with new simple volume selected in blue."/>
  <br />
  <br />
  The control panel brings up the simple volume wizard dialogue and I progress through the dialogue leaving the defaults<br />
  <img src="https://github.com/user-attachments/assets/1d5ca50a-2b86-4281-a8ed-d2ac20bee856" height="80%" width="80%" alt="the first window of the new simple volume wizard which has three lines for maximum and minimum disk size and then the third line has a field where you can enter the size you want to assign for the volume."/>
  <img src="https://github.com/user-attachments/assets/9eb79d7a-f30d-4fcc-aa55-667cec8ed11e" height="80%" width="80%" alt="the second window of the wizard, where you can choose between three radio button options. The top option automatically assigns the next available letter as the new volume name, the second option allows you to mount to an NTFS volume, and the third option is to not assign a dive letter or file path. The first option is selected in this case with the letter E assigned to the volume."/>
  <img src="https://github.com/user-attachments/assets/9dafaa6a-cc19-4404-afb4-4293538914b9" height="80%" width="80%" alt="the last window of the wizard shows a confirmation of the info and the option to finish the setup by clicking the button."/>
  <br />
  <br />
  Now the disk partition is completed, and the new partition is assigned the letter E:\<br />
</p>

- <b>Navigating to Disk Management</b>
<p>Lastly, I'm going to format the new partition to a different file system, FAT32.</p>
<br>
<p align="center">To format the partition E: to a different file format, I right click on it and select "Format"<br/>
  <img src="https://github.com/user-attachments/assets/4cb9ef96-40a3-4b5f-b962-731e06b526dd" height="80%" width="80%" alt="the new volume E, which is located at the bottom right of the middle section and was previously the unallocated space, has gray diagonal cross hatching and a pop up window floating above it. In the pop up window format is selected in blue."/>
  <br />
  <br />
 In the file system formating dialogue I select FAT32 from the file system drop down menu, and then click "OK"<br />
  <img src="https://github.com/user-attachments/assets/ba71063e-990e-42fb-b06f-d3543517d5ab" height="80%" width="80%" alt="In a smaller format window, the file system type is selectable from a drop down. The FAT32 option is selected in blue."/>
  <br />
  <br />
A confirmation alert with a warning reminds me that reformating the drive will destroy any data currently on the drive. I click "OK" to continue<br />
  <img src="https://github.com/user-attachments/assets/01cf77ef-c3a8-4273-a96c-0b2240eea410" height="80%" width="80%" alt="a pop up warning is displayed with a yellow triangle with an exclamation mark and the warning next to it reads formatting this volume will erase all data on it. Back up any data you want to keep before formatting. Do you want to continue? and at the bottom of the window there are ok and cancel buttons, and ok is selected."/>
   <br />
  <br />
 The partition is formated to the new file system type of FAT32 and the final disk configuration is ready.<br />
</p>
