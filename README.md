# Cloud-Engineer-Internship
Cloud Engineer Internship
1. Create a Storage Account
I started by creating a storage account in Azure to host my website.

Steps:
Logged into the Azure Portal.
Clicked on Create a resource > Storage Account.
Chose an existing Resource 
Filled in the required details:
Performance: Standard.
Redundancy: Locally-redundant storage (LRS).
Clicked Review + Create to deploy the storage account.
<img width="949" alt="image" src="https://github.com/user-attachments/assets/5708122e-4ec0-4575-926b-3a57ac75df87">


2. Enable Static Website Hosting
To configure the storage account for website hosting, I enabled the static website feature.
Steps:
Navigated to the Storage Account in the Azure Portal.
I selected the Static website under the Data Management section.
I enabled the Static website toggle.
<img width="743" alt="image" src="https://github.com/user-attachments/assets/ad6ccb16-be1f-4c80-b4a4-f32ebf816b39">

Entered the following:
Index document name: index.html.
Error document path: 404. html.
Saved the settings, which provided a Primary Endpoint URL for the website.
![image](https://github.com/user-attachments/assets/9688c38d-0858-4e71-afd5-f2fb26d4deb5)



3. Upload Website Files
Next, I uploaded the files for the website.

Steps:
Went to Containers in the storage account.
Created a container named \$web (this is the default container for static websites).
Uploaded my website files (e.g., index.html, styles.css, and script.js) to the \$web container.
![image](https://github.com/user-attachments/assets/1ead8cb3-7bb4-486e-98eb-8e161e4da87a)
![image](https://github.com/user-attachments/assets/71ca3647-e07d-487a-913e-8a747085d418)
![image](https://github.com/user-attachments/assets/e50026ee-bcb7-4560-be48-99373d159822)



4. Verify the Website
Once everything was set up, I verified that the website was live.
https://dist12.z6.web.core.windows.net/
link above to my static website
Steps:
Opened the Primary Endpoint URL provided in the static website settings.
Confirmed that the website loaded correctly with all assets (HTML, CSS, and JavaScript).
