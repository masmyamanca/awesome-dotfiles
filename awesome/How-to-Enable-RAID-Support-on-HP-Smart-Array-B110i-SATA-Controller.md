## How to Enable RAID Support on HP Smart Array B110i SATA Controller

  
# How to Enable RAID Support on HP Smart Array B110i SATA Controller
  
If you have a HP ProLiant server with a Smart Array B110i SATA controller, you may want to enable RAID support for better performance and data protection. However, the controller is not enabled by default and requires a license key to activate the RAID functionality. In this article, we will show you how to obtain and install the license key, and how to configure an array using the controller.
 
## License Key Smart Array B110I Sata Raid


[**Download Zip**](https://www.google.com/url?q=https%3A%2F%2Fssurll.com%2F2tKpX4&sa=D&sntz=1&usg=AOvVaw0hkPTdvI_4bxr31ZApDzuZ)

  
## What is the Smart Array B110i SATA Controller?
  
The Smart Array B110i SATA controller is an embedded SATA controller that supports up to six 3G SATA hard disk drives. It supports RAID 0, 1 and 1+0 levels, and can create up to two logical drives. The controller is designed as a Smart Array and uses the Array Configuration Utility (ACU) and Option ROM Configuration for Arrays (ORCA) for creating and managing logical drives.
  
## How to Obtain the License Key?
  
The license key for the Smart Array B110i SATA controller is part of the HP Smart Array Hot Plug Advanced Pack (HP SAAP), which provides additional features and benefits for HP ProLiant servers. The HP SAAP is available as a free 60-day trial or as a paid product. You can download the trial version from the HP website (https://www.hpe.com/us/en/servers/smart-array-advanced-pack.html) or purchase the product from an authorized reseller.
  
To install the license key, you need to access the ACU on your server and enter the key in the License Management section. You can access the ACU either through the SmartStart CD or through the online version. For more information on how to use the ACU, see the HP Smart Array B110i SATA RAID Controller User Guide (https://community.hpe.com/hpeb/attachments/hpeb/hpsc-100/427/1/b110i%20user%20guide.pdf).
  
## How to Enable and Configure the Controller?
  
After installing the license key, you need to enable the controller and set it as the boot controller in the ROM-Based Setup Utility (RBSU). The steps may vary depending on your server model, but generally you need to do the following:
  
- Power up the server.
- When prompted during the start-up sequence, access RBSU by pressing the F9 or F10 key.
- Select Advanced Settings or Advanced.
- Select Embedded SATA RAID or SATA Configuration.
- Change SATA #1 to RAID.
- Return to the previous screen by pressing the Escape key.
- Select Boot Controller Order or Boot Menu.
- To assign the Smart Array B110i SATA controller as the boot controller, set Ctrl 1 to Smart Array B110i SATA RAID Controller.
- Press the F10 key to save the settings and exit RBSU.

Once you have enabled the controller, you can configure an array using either ORCA or ACU. ORCA is a simple utility that allows you to create a single logical drive with a default RAID level. ACU is a more advanced utility that allows you to create multiple logical drives with different RAID levels and settings. For more information on how to use ORCA and ACU, see the HP Smart Array B110i SATA RAID Controller User Guide (https://community.hpe.com/hpeb/attachments/hpeb/hpsc-100/427/1/b110i%20user%20guide.pdf).
  
## Conclusion
  
The Smart Array B110i SATA controller is a useful feature that can enhance your HP ProLiant server performance and data protection. However, it requires a license key to enable RAID support, which you can obtain from HP SAAP. After installing the license key, you need to enable and configure the controller using RBSU, ORCA or ACU. By following these steps, you can enjoy the benefits of RAID on your server.
 0f148eb4a0
