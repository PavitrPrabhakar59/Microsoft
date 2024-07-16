# Download Office

 **Step 1.** ```Download Zip``` as shown below
 
![download](https://github.com/user-attachments/assets/90f6282c-fb7a-4446-9328-d3ef0b728b0b)

**Step 2.**
- Extract the Downloaded Zip i.e. ```Microsoft-main.zip```
* Open the Extracted Folder i.e. ```Microsoft-main```
+ Open ```Office``` Folder

![download](https://github.com/user-attachments/assets/56b10bcf-b738-41c6-a2c4-8a57c34d71c6)

<hr>

>[!Note]
>If you want to Download Only Classic Office Apps i.e Word,Excel & Powerpoint then Skip this Step i.e. Step 3

**Step 3.**
- Right Click on the ```Configuration.xml``` File
* Select Open With
+ Select Notepad
+ Remove the Desired App i.e. ```<ExcludeApp ID="AppName" />``` you want to Download <br> For e.g. I want to Download OneDrive then I removed the ```<ExcludeApp ID="OneDrive" />```

![download](https://github.com/user-attachments/assets/38b789ea-4a1a-430c-8322-2874b6f3c044)

<hr>

**Step 4.** 
- Click on the File Explorer Address Bar and type ```cmd``` and hit ```Enter```
- This will Open the Command Prompt
- Paste this Below text in Command Prompt and hit ```Enter```

  		setup /configure configuration.xml
- There Will be a Windows Pop-up ```We're getting things ready...```
- After 5-15 Seconds there will be Another Pop-up which will show the Status of Download <br> This will also show the App's Logo Which will Download
- After Successful Download there will be Another Pop-up stating Office is Installed

![download (1)](https://github.com/user-attachments/assets/f7bf36d6-136b-450e-bf04-4665d7552634)
