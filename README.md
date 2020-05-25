# Webhook-sample

With the following steps you will deploy a simple Logic Apps workflow to expose a webhook endpoint, which will response status 202 immediately and callback the calback uri after 2 minutes.

1) First of all download the repository in your local machine and decompress into a local folder: <BR>
![Download files.png](/.attachments/Download-files.png)

2) Click on the below button "Deploy to Azure": <BR>
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template)

3) In the custom deployment page, click on "Build your own template in the editor": <BR>
![Build tamplate.png](/.attachments/Build-template.png)

4) In the edit template page, click on "Load file" and select the "Template.json" fom the local folder where you downloaded the repository in step 1: <BR>
![Load file.png](/.attachments/Load-file.png)
  
5) In the edit template page, click on "save": <BR>
![Save.png](/.attachments/Save.png)
  
6) In the custom deployment page, fill all fields properlly and click on "Review + create": <BR>
![Create.png](/.attachments/Create.png)
  
7) Check in your Resource Group the Logig Apps created and which is the trigger url in "Logic app Designer > HTTP POST URL": <BR>
![Resource.png](/.attachments/Resource.png)
