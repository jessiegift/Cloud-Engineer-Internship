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
2. Enable Static Website Hosting
To configure the storage account for website hosting, I enabled the static website feature.

Steps:
Navigated to the Storage Account in the Azure Portal.
Selected Static website under the Data Management section.
Enabled the Static website toggle.
Entered the following:
Index document name: index.html.
Error document path: 404. html.
Saved the settings, which provided a Primary Endpoint URL for the website.
3. Upload Website Files
Next, I uploaded the files for the website.

Steps:
Went to Containers in the storage account.
Created a container named \$web (this is the default container for static websites).
Uploaded my website files (e.g., index.html, styles.css, and script.js) to the \$web container.
![image](https://github.com/user-attachments/assets/1ead8cb3-7bb4-486e-98eb-8e161e4da87a)


![image](https://github.com/user-attachments/assets/519135be-8d94-4db7-9845-5e64f83ae150)

4. Verify the Website
Once everything was set up, I verified that the website was live.

Steps:
Opened the Primary Endpoint URL provided in the static website settings.
Confirmed that the website loaded correctly with all assets (HTML, CSS, and JavaScript).
