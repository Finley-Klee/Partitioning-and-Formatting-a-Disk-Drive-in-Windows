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
  <img src="https://github.com/user-attachments/assets/d2f1bdda-a819-4035-a321-7ba0e8ec1078" height="80%" width="80%" alt="image one"/>
  <br />
  <br />
 While in the control panel, I navigate to System and Security, then Administrative Tools.<br />
  <img src="https://github.com/user-attachments/assets/f0470358-55ac-43da-b12a-77c2f7df52e8" height="80%" width="80%" alt="image two"/>
  <br />
  <br />
  In the administrative tools menu, I click on Computer Management.<br />
  <img src="https://github.com/user-attachments/assets/e71f96f6-2352-497f-90f6-ebbec9c11706" height="80%" width="80%" alt="image three"/>
   <br />
  <br />
  Then, in the left panel under Storage, I select Disk Management.<br />
  <img src="https://github.com/user-attachments/assets/e16be77e-61d6-486d-926b-698af62c5d00" height="80%" width="80%" alt="image four"/>
</p>
<br />
<br />

- <b>Mounting and Partitioning the Disk</b>
<p>Now that I have navigated to Disk Management from the control panel, I'm ready to mount the new disk drive and create a new partition on the disk.</p>
<br>
<p align="center">At the bottom of the Disk Management screen I can see two disks, one of which contains unallocated space, and is labeled "offline". To mount this disk, I right click on the left part of the disk and select "online". <br/>
  <img src="https://github.com/user-attachments/assets/07eb7190-f735-4974-a3bc-47008dcfc51e" height="80%" width="80%" alt="image one"/>
  <br />
  <br />
  The disk is mounted and automatically assigned the next letter available, in this case D:\ <br />
  <br />
  <br />
 To create a new partition, I first need to shrink the volume by right clicking on the disk and selecting "shrink volume"<br />
  <img src="https://github.com/user-attachments/assets/5947cf62-fb09-4210-8a91-20e71503e998" height="80%" width="80%" alt="image three"/>
   <br />
  <br />
 I want to split the disk into two partitions, one of 30GB and one of 20GB, so in the box for listing the size to shrink the disk I enter 20480MB, and click "shrink"<br />
  <img src="https://github.com/user-attachments/assets/df1b7bb7-8372-4987-bf2d-4afa17868e70" height="80%" width="80%" alt="image four"/>
   <img src="https://github.com/user-attachments/assets/303d1105-112e-48c5-9738-55239b6a08cc" height="80%" width="80%" alt="image four"/>
   <br />
  <br />
  Now to create the partition I right click on the new unallocated space and select "new simple volume"<br />
  <img src="https://github.com/user-attachments/assets/462ba6b8-b33a-4e8a-8b72-93bb13f108e6" height="80%" width="80%" alt="image five"/>
  <br />
  <br />
  The control panel brings up the simple volume wizard dialogue and I progress through the dialogue leaving the defaults<br />
  <img src="https://github.com/user-attachments/assets/1d5ca50a-2b86-4281-a8ed-d2ac20bee856" height="80%" width="80%" alt="image six"/>
  <img src="https://github.com/user-attachments/assets/9eb79d7a-f30d-4fcc-aa55-667cec8ed11e" height="80%" width="80%" alt="image seven"/>
  <img src="https://github.com/user-attachments/assets/9dafaa6a-cc19-4404-afb4-4293538914b9" height="80%" width="80%" alt="image eight"/>
  <br />
  <br />
  Now the disk partition is completed, and the new partition is assigned the letter E:\<br />
</p>

- <b>Navigating to Disk Management</b>
<p>Lastly, I'm going to format the new partition to a different file system, FAT32.</p>
<br>
<p align="center">To format the partition E: to a different file format, I right click on it and select "Format"<br/>
  <img src="https://github.com/user-attachments/assets/4cb9ef96-40a3-4b5f-b962-731e06b526dd" height="80%" width="80%" alt="image one"/>
  <br />
  <br />
 In the file system formating dialogue I select FAT32 from the file system drop down menu, and then click "OK"<br />
  <img src="https://github.com/user-attachments/assets/ba71063e-990e-42fb-b06f-d3543517d5ab" height="80%" width="80%" alt="image two"/>
  <br />
  <br />
A confirmation alert with a warning reminds me that reformating the drive will destroy any data currently on the drive. I click "OK" to continue<br />
  <img src="https://github.com/user-attachments/assets/01cf77ef-c3a8-4273-a96c-0b2240eea410" height="80%" width="80%" alt="image three"/>
   <br />
  <br />
 The partition is formated to the new file system type of FAT32 and the final disk configuration is ready.<br />
</p>
