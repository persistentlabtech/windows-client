# windows-client training

https://www.dropbox.com/scl/fo/uxbo7bycql61boamyetzp/h?dl=0&rlkey=sfmhqqpcighygfjzebm5ry7i7

1.https://learn.microsoft.com/en-us/training/paths/install-windows-client/

2. https://learn.microsoft.com/en-us/training/paths/configure-authorization-authentication/

3. https://learn.microsoft.com/en-us/training/paths/configure-post-installation-settings-personalization/

4. https://learn.microsoft.com/en-us/training/paths/configure-networking-windows-clients/

5. https://learn.microsoft.com/en-us/training/paths/configure-storage-windows-clients/

https://portal.azure.com


Are all of you know to create machines?

Subscription

Region

Operating System -

Virtual Machine name

admin user name

password

Machine Size

Virtual network - VNETSTUDENT01
[
**https://learn.microsoft.com/en-us/samples/azure/azure-quickstart-templates/active-directory-new-domain/**](https://learn.microsoft.com/en-us/samples/azure/azure-quickstart-templates/active-directory-new-domain/)


Create Windows10 and Windows 11 machiones and join to domain.. Ensure all machine use same VNET..

Check the login to windows 10 and windows 11 y using logging with Domain Account - Contoso\studentxx -- password..

Logon to AD Machine with  Contoso\studentxx -- password.. and then to Active Directory Users and Computers..

Create user account in ADUC anexample admin1 and admin2 and give passwords.. Add the users to Domain Admins and Eneterprise Admins Group

Create user account in ADUC an example  - user1 and user2 and give passwords..

Test login to windows10 and windows11 using then new accounts created..

SERVER -use AD Machine.



Task 1 -> Use your own la machines ..

Disable control panel for Windows 10

Group Policy --> Disable control panel

Windows 10 machine - see the effect of policy

AD
WINDOWS 10

AD --> Group Policy -->

Create OU - Windows 11

Create OU - Windows 10 --> create policy --> disable control panel - one setting.. apply this to Windows 10.

Windows 10 - gpupdate /force


Task 2 - labuser account - create windows 2022 server .. install hyper-v.

Create a Window 10 OS Machine..

 https://www.microsoft.com/en-us/software-download/windows10

Upgrade Windows 10 to Windows 11 - same hyper-v client..






