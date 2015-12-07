
Fetchr API for OpenCart
---
Fetchr API extension for Opencart creates connectivity between your OpenCart website and Fetchr to share order information. 

### Target Audience

This documentation contains overview information on the solution level and very detailed technical information. The target audience consists of the following persons:

- Technology consultants
- System administrators


## Download
You can download the _official_ Fetchr API opencart extension file from here:  
[http://support.fetchr.us/hc/en-us/articles/205732391-Opencart-Extension-V1.0.0][download]

## Installation 

1. Extract the file to your local machine.
2. Login as Admin.
3. Go to Extensions > Extensions Installer > Upload file (fetchr.ocmod.xml).
4. Go Extensions > Modifications > Click Refresh button.
5. Extensions > Extensions Installer > Upload file (fetchr_api_1.1.0.ocmod.zip).
6. Go Extensions > Modules, find Fetchr API module and Click install button.
7. After installing Fetchr OpenCart extension, Click edit button to configure.

## Configuration

    Caution:
    ALWAYS remember to make a full database/files backup before installing any new modules!
    
    Note:
    In this interface you find 2 type of services.

### Account Type
- **Staging** if you are testing 
- **Live** if you are ready to use Fetchr for your orders

### Service Type
- **Fulfillment + Delivery** for warehouse and delivery service.
- **Delivery** Only for delivery services.

### Username & Password
Your login credentials as provided by Fetchr.

Enter the details, then Click Save button, as shown in the following figure.

![Image of API](http://support.fetchr.us/hc/en-us/article_attachments/202249402/image00.png)

## Push Order

    Caution:
    Test Fetchr in staging mode before go to live.
    
1. Go to Sales > Orders, Click view order. In order history section, change status from pending to **Ready for Pick up**.
2. Go to Extensions > Modules > Fetchr API > Click Edit button.
3. Click Push Order.
4. Go to Order view page > History section > Click Tracking URL to continue the order.


[download]: http://support.fetchr.us/hc/en-us/articles/205732391-Opencart-Extension-V1-0
[documentation]: http://support.fetchr.us/hc/en-us/article_attachments/202237701/OpenCart-API-Extension_InstallationGuide_V1.0.pdf
    

