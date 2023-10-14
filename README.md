This repository has a small snippet for using Polarion OSLC service with support OAuth dance. 
You should use Postman >= 9.15.2.

There are variables at the collection level to configure this fragment.

![image](https://github.com/Krusty84/Polarion_OSLC_OAuth_1.0a/assets/44873126/5b7e8495-efee-4073-9e78-6506238d6833)

Run **1.Get_RootServices**  
Afterwards, go through OAuth 1.0 hell starting with **2.1.Get_Consumer_Key**  
Please note that steps **2.2.Approve_Consumer_Key** and **2.4.Authorize_Requested_Token** require user interaction, please refer to the Visualize tab for links to open them in the browser

![image](https://github.com/Krusty84/Polarion_OSLC_OAuth_1.0a/assets/44873126/9d75f209-fb0b-4c8f-9f91-1200568a6d13)

![image](https://github.com/Krusty84/Polarion_OSLC_OAuth_1.0a/assets/44873126/6a8d49bb-8eb8-4bdf-a64d-627c8e31dd6f)

After receiving the access token, go to step **3.1.Get_Servcie_Provider_Catalog** and then enjoy your journey through the Polarion OSLC resources

![image](https://github.com/Krusty84/Polarion_OSLC_OAuth_1.0a/assets/44873126/a8a9cb2b-55a1-4f8b-b58d-af8053228238)
