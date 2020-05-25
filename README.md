# Webhook template deploy

With the following steps you will deploy a simple Logic Apps workflow to expose a webhook endpoint, which will response status 202 immediately and call the calback uri after 2 minutes.

<b>1) First of all download the repository in your local machine and decompress into a local folder:</b> <BR>
![Download files.png](/.attachments/Download-files.png)

<b>2) Click on the below button "Deploy to Azure":</b> <BR>
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template)

<b>3) In the custom deployment page, click on "Build your own template in the editor":</b> <BR>
![Build tamplate.png](/.attachments/Build-template.png)

<b>4) In the edit template page, click on "Load file" and select the "Template.json" fom the local folder where you downloaded the repository in step 1:</b> <BR>
![Load file.png](/.attachments/Load-file.png)
  
<b>5) In the edit template page, click on "save":</b> <BR>
![Save.png](/.attachments/Save.png)
  
<b>6) In the custom deployment page, fill all fields properlly and click on "Review + create":</b> <BR>
![Create.png](/.attachments/Create.png)
  
<b>7) Check in your Resource Group the Logig Apps created and which is the trigger url in "Logic app designer > HTTP POST URL":</b> <BR>
![Resource.png](/.attachments/Resource.png)
