---
title: "Data Access"
date: "2022-03-04"
---

  
_Datasets_ are displayed on the left hand-side of the _Experiment/Object_ form, as shown below.

![](https://openbis.ch/wp-content/uploads/2019/09/Screenshot-2020-02-27-at-11.47.31.png)

To navigate and open data registered in openBIS via Finder or Explorer, open the _Dataset_ folder and click on the drive icon next to the Dataset type name_._ If SFTP has been configured by a system admin, you will be provided with a link to copy/paste in an application such as [Cyberduck](https://cyberduck.io/) or other.

Please check our documentation for SFTP server configuration: [Installation and Administrators Guide of the openBIS Data Store Server](https://unlimited.ethz.ch/display/openBISDoc2010/Installation+and+Administrators+Guide+of+the+openBIS+Data+Store+Server#InstallationandAdministratorsGuideoftheopenBISDataStoreServer-ExampleSFTPclientconfiguration)

For native access through Windows Explorer or Mac Finder we recommend the following:

- Windows 10: [https://www.nsoftware.com/sftp/netdrive/](https://www.nsoftware.com/sftp/netdrive/)
- Mac OS X Yosemite and higher: [https://mountainduck.io](https://mountainduck.io/)
- Kubuntu: Default Dolphin File Manager with SFTP support

##   
Example of SFTP Net Drive connection:

1\. open SFTP Net Drive and click on **New**:

![](https://openbis.ch/wp-content/uploads/2022/03/win-sftp-1.png)

2\. Edit the drive with the following info, as shown below:

     a. **Drive name**: choose any name you want. Can be the same as your openBIS server, but does not have to be.

     b. **Remote Host**: the name of your openBIS. For example, if the url of your openBIS is https://openbis- demo.ethz.ch/openbis/webapp/eln-lims, then openbis-demo.ethz.ch is the name you want to enter.

    c. **Remote por**t: enter 2222.

    d. **Authentication type**: Password (this is selected by default).

    e. **Username**: the username you use to login to openBIS.

    f. **Password**: the password you use to login to openBIS.

    g. **Root folder on server**: you can leave the default, User's home folder.

    h. Press **OK** after filling in all the information above. 

![](https://openbis.ch/wp-content/uploads/2022/03/win-sftp-2.png)

3\. After saving the drive, select it in the drivers' window and click **Connect**.

![](https://openbis.ch/wp-content/uploads/2022/03/win-sftp-3.png)

3\. openBIS will now appear as a drive in your Explorer window. Click on the **ELN-LIMS** folder and navigate to the folder containing the data you want to access.

![](https://openbis.ch/wp-content/uploads/2022/03/win-sftp-4.png)

## Example of Cyber Duck configuration

Create a new connection in cyberduck:

1. select **SFTP (SSH File Transfer Protocol)**
2. **Nickname**: the name you want to use for the server
3. **Server**: the name of the server you want to connect to. In the example below openbis-training.ethz.ch. Replace this with the name of your own openBIS server.
4. **Port**: 2222 
5. **Username**: this is the username with which you connect to your openBIS
6. **Password**: this is the password you use to connect to your openBIS
7. **SSH** private Key: none

![](https://openbis.ch/wp-content/uploads/2022/03/cyberduck-config.png)

Save the specifications and connect to the server.

You will see the folders of your own openBIS in the Cyberduck window and you can navigate to your data from there.

![](https://openbis.ch/wp-content/uploads/2022/03/cyberduck-navigation.png)

## Example of  Dolphin File Manager configuration

![](https://openbis.ch/wp-content/uploads/2019/01/dolphin.png)

To access the Dataset form and edit the Dataset metadata, click on the Dataset code or Name (if provided).

## SFTP access via session token

To access via session token (for example when using SSO authentication) you need to provide the following credentials:

**Username: ?**

**Password: session token**.

The session token can be copied from the **User Profile** under **Utilities** in the main menu, as shown below.

![](https://openbis.ch/wp-content/uploads/2019/09/Screenshot-2021-10-26-at-13.23.13-1.png)
