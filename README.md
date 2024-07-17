# Download MS Office 365 Apps for Enterprise 

## Download Office Deployment Tool[^1]
 
1. ```Download Zip``` as shown below
2. Extract the Downloaded Zip i.e. ```Microsoft-main.zip```
3. Open the Extracted Folder i.e. ```Microsoft-main```
4. Open ```Office``` Folder

![download (1)](https://github.com/user-attachments/assets/360ed6b7-6cbd-45c8-99b9-b254fe9d0a6d)

### Selecting Additional Office Apps (Optional)[^2]

>[!Note]
>If you want to Download Only Classic Office Apps i.e Word,Excel & Powerpoint then Skip this Step

1. Right Click on the ```Configuration.xml``` File
2. Select Open With
3. Select ```Notepad```
4. Remove the Desired App i.e. ```<ExcludeApp ID="AppName" />``` you want to Download <br> For e.g. I want to Download OneDrive then I removed the ```<ExcludeApp ID="OneDrive" />```

![download](https://github.com/user-attachments/assets/38b789ea-4a1a-430c-8322-2874b6f3c044)

## Download Office

1. Click on the ```File Explorer``` Address Bar and type ```cmd``` and hit ```Enter```
2. This will Open the ```Command Prompt```
3. Paste this Below text in ```Command Prompt``` and hit ```Enter```

  		setup /configure configuration.xml
4. There Will be a Windows Pop-up ```We're getting things ready...```
5. After 5-15 Seconds there will be Another Pop-up which will show the Status of Download <br> This will also show the App's Logo Which will Download
6. After Successful Download there will be Another Pop-up stating Office is Installed

![download](https://github.com/user-attachments/assets/3d73b399-1adb-46ce-b14c-bf70f87d72c7)

## Activating Office[^3]

1. Open ```Powershell```
2. Paste this below text in ```Powershell``` and hit ```Enter```

       irm https://get.activated.win | iex
3. After some time ```Command Prompt``` will open
4. Press ```2```
5. Press ```1```
6. After sometime there will be a Message ```Office is Permanently Activated```
7. Close the ```Command Prompt```

![download](https://github.com/user-attachments/assets/157345b4-7d1d-4e27-aae1-eb3c08fe6428)

## Footnotes

[^1]:https://www.microsoft.com/en-us/download/details.aspx?id=49117
[^2]:https://config.office.com/deploymentsettings
[^3]:https://massgrave.dev/
