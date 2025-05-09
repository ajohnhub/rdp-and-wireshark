![image](https://user-images.githubusercontent.com/109401839/230745596-57cee9bd-687c-427d-b0db-d1080df77f7e.png)


<h1>Remote Desktop & Wireshark</h1>
This walkthrough demonstrates how to use Remote Desktop within Windows and Linux Virtual Machines. I will also be demonstrating how to use Wireshark, an open-source network protocol analyzer used for capturing and analyzing network traffic within these VM's.
</br>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Wireshark

<h2>Operating Systems Used </h2> 

- Windows 10 (22H2)
- Linux

<h2>Walkthrough Steps</h2>

<p>
Log in to your Windows VM by connecting to Remote Desktop on your computer with your Windows VM's Public IP Address. 

<img src="https://github.com/user-attachments/assets/5bcf72e0-8bec-4d51-b67e-2bc4417b1674" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
</br>

<p> 
Once logged in, go to www.wireshark.org & download Wireshark for your device.
<img src="https://github.com/user-attachments/assets/5e8ccb00-7796-4a62-bbff-f4d4247fd7a4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/ff3f7af4-01e3-4abf-ae95-98352738d97c" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
</br>

<p>Open Wireshark and click the blue shark fin in the top left corner to begin packet capture.

<img src="https://github.com/user-attachments/assets/4a7e35b5-71ad-4d74-b8ba-7c1c6df16505" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/e3f5d014-6458-4928-9b9c-97b8d14ce2b5" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
</br>

<p> You can filter for specific traffic by using the search bar. (Ex: icmp)

<img src="https://github.com/user-attachments/assets/489c77bc-8fc9-4732-9e9c-8ac801a12ad7" height="80%" width="80%" alt="Disk Sanitization Steps"/>


</p>
</br>


<p>Retrieve the private IP address of the Ubuntu VM (linux-vm) and attempt to ping it from within the Windows 10 VM.

<img src="https://github.com/user-attachments/assets/60395029-4baa-4b60-a20f-7a04229f77c6" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</br>

<p> Observe ping requests and replies within Wireshark.

<img src="https://github.com/user-attachments/assets/7f1bf292-666e-48b7-83fa-1a304672b964" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  
</p>
</br>

