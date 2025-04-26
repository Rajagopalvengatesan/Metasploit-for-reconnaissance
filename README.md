# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

### Step1:Identify the Attacker’s IP Address
Determine the IP address of the attacker's system.
![Screenshot 2025-04-11 061101](https://github.com/user-attachments/assets/0322259a-0d67-435d-a23f-1a064b180102)


### Step2:Launch the Metasploit Console
Invoke the **msfconsole**.
![Screenshot 2025-04-11 061335](https://github.com/user-attachments/assets/da3a8e4f-2e14-433e-a42a-0bfaf5dbcb55)



To view available commands, enter **"?"**.
![image](https://github.com/user-attachments/assets/82414691-fe15-474e-a768-c3c19e2719f8)


### Step3:Generate Payload Using msfvenom

Execute the following command to generate a Windows Meterpreter reverse shell payload.
![Screenshot 2025-04-11 062300](https://github.com/user-attachments/assets/503c77b1-743f-4aef-b804-c5bcc08b2d57)


### Step4:Set Up an HTTP Server
Once the payload file is created, navigate to the home directory.
Right-click and select **"open terminal here"**.
![image](https://github.com/user-attachments/assets/42e1fa87-7501-47ec-ba81-4c4b7e3a263d)




Run the Python command to establish an HTTP server for file distribution.
![Screenshot 2025-04-11 062640](https://github.com/user-attachments/assets/6180fd69-5f76-4db8-92e6-12d0905d5baf)


### Step5:Distribute the Payload
Share the .exe file with the target system via any medium or the HTTP server.

Once the victim downloads and executes the file, the exploit is triggered.

**VICTIM DEVICE:**
![image](https://github.com/user-attachments/assets/f1367f96-a535-4f37-913d-905b943a104a)

![image](https://github.com/user-attachments/assets/06791d66-20f3-424a-9518-bcf6c7778242)


### Step6:Establish a Connection
On Kali Linux, reopen the terminal and invoke **"msfconsole"**.
Follow the necessary steps to establish a connection with the victim’s device.
![image](https://github.com/user-attachments/assets/772a8153-000e-4a06-b24d-b9c3d804b50a)


Once exploited, a session is created, allowing remote access without the victim’s awareness.

### Step7:List commands
Use the help command to list available operations.
![image](https://github.com/user-attachments/assets/cbaff802-7245-4504-b28a-b160ef69bd50)



### Step8:
For example, the **"screenshot"** command captures the victim’s screen and saves it in the attacker's home directory.

![image](https://github.com/user-attachments/assets/64cca92a-3e49-41aa-96f9-2e90fcc4f910)


![WhatsApp Image 2025-04-07 at 11 03 10_cd03e798](https://github.com/user-attachments/assets/b2bd93b8-20cc-4105-8bda-09e37e51533c)




### Step9:Terminate the Connection
After completing the intended operations, close the session securely.

#### RESULT:
The Metasploit framework for reconnaissance is  examined successfully.
