# EnosixGOSAttachment
Documentations for EnosixGOSAttachment through Connect
Navigate to your Connect environment. Create a new project. Add your SAP Connection. Create a SAP BTP application. Configure your SAP Connection either by using Service Account or SAP Cloud. Select ‘Passthrough’ for your API Authentication. Add both Detail and Search APIs for ‘EnosixGOSAttachment’. Create and Publish a package with both APIs. Open Swagger using the link created with the 2 APIs. Click the Authorize button with the lock and enter your SAP system credentials. For EnosixGOSAttachment Detail, Open POST Create option. Click the 'Try it out' button. Populate the following information with your own SAP details. 

{  
  "objectType": "EXT",  
  "filename": "text.pdf",  
  "mimeType": "application/pdf",  
  "typeID": "BUS2032",  
  "instanceID": "16634",  
  "base64String": "JVBERi0xLjMNCi..." 
  }
  
  Click the 'Execute' button. Verify you get a 'Success' result. Navigate to SAP. Use TCode 'VA03'. Enter the order number. In the top left corner, Hover over the 'Services for Object' button. Click the arrow on the button. Click on 'Attachments List' PDF should be displayed in the list. Double Click on the PDF, new browser tab will open with the attached PDF displayed.
