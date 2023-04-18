<h1>Steganography Practice</h1>


<h2>Description</h2>
In this lab, I will show how data can be extracted from images. I will conceal a secret message in an image file and extract it into files using Steghide.<br/>

<h2>Tools Used</h2>

- <b>VMware</b> 
- <b>Kali Linux</b>
- <b>Steghide</b>


<h2>Program walk-through:</h2>

- First we need to install Steghide in our Kali Linux.
- Open a terminal in Kali and run this command: <b>sudo apt install steghide</b>
- Next you will need to choose an image where you will conceal a message. You can download it using a browser that you have in your Kali Linux or by dragging your image from your host machine to Kali desktop. 
 
<p align="center">
Check the image properties to analyze its size and dimensions: <br/>
 <img width="1024" alt="Screenshot 1" src="https://user-images.githubusercontent.com/54782834/232651077-3793cbab-6c31-40c5-ae1c-0f70cbe3768b.png">

 - Now we will create a file containg a message.  
 <p align="center">
 Create a .txt file using nano command. Use cat command to view your message.<br/>
  <img width="1225" alt="Screenshot 2" src="https://user-images.githubusercontent.com/54782834/232655547-a1dbe531-2a44-435c-9091-afee506ad8c1.png">

<p align="center">
 Hide a secret message into the chosen image using embed command: <br/>
  <img width="1260" alt="Screenshot 3" src="https://user-images.githubusercontent.com/54782834/232659213-f471fd48-ed61-4c65-bede-2dfd67f56745.png">
 
<p align="center">
 Check again the size and the properties of the image: <br/>
 <img width="1072" alt="Screenshot 2023-04-17 at 8 15 21 PM" src="https://user-images.githubusercontent.com/54782834/232661964-a81f6a5a-95cb-4ff6-9009-d72697618dc2.png">

 

   

  
<br />
<br />
Select the disk:  <br/>

<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

