---
title: "Data upload via dropbox"
date: "2022-02-25"
---

Web upload of data files is only suitable for files of limited size (few GB). To upload larger data, openBIS uses dropbox scripts that run in the background (see [Dropboxes](https://unlimited.ethz.ch/display/openBISDoc2010/Dropboxes)). A default dropbox script is provided with the openBIS ELN-LIMS plugin, and the dropbox folder needs to be set up by a _system admin_.

If this is available, users need to organise their data in a specific way:  

Folder 1

     Folder 2

        data (can be single files or folders)  

Folder 1 needs to have a specific name that encodes the information of where the data should be uploaded to openBIS.

Folder 2 can be named as wished by the user. If this folder is called "default" it will not be shown in the user interface, after upload.

The name of Folder 1 can be generated from the ELN interface.

From the page where you want to upload data, select **Dataset upload helper tool for eln-lims dropbox** from the **More...** dropdown and follow the instructions on screen.

Place the correctly named Folder 1 containing your data in the eln-lims-dropbox folder. openBIS continuously monitors this folder and when data are placed here, they are **moved** to the final storage. The move happens after a predefined (and customisable) inactivity period on the eln-lims-dropbox folder.  

![](images/dataset-uploader.png)

### Dropbox with markerfile

  In case of uploads of data >100GB we recommend to configure the **eln-lims-dropbox-marker**. The set up and configuration need to be done by a _system admin_. The process of data preparation is the same as described above, however in this case the data move to the openBIS final storage only starts when a markerfile is placed in the eln-lims-dropbox-marker folder. The marker file is an empty file with this name: **.MARKER\_is\_finished\_<folder-to-upload-name>.** Please note the "." at the start of the name, which indicates that this is a hidden file. This file should also not have any extension. For example, if the folder to be uploaded has the following name:   E+PBHOUMIK\_PBHOUMIK+INTRA\_BREED\_GENETIC\_VARIABILITY\_OF\_DOGS+INTRA\_BREED\_GENETIC\_VARIABILITY\_OF\_DOGS\_EXP\_1+ATTACHMENT+my-data   The marker file should be named:   .MARKER\_is\_finished\_E+PBHOUMIK\_PBHOUMIK+INTRA\_BREED\_GENETIC\_VARIABILITY\_OF\_DOGS+INTRA\_BREED\_GENETIC\_VARIABILITY\_OF\_DOGS\_EXP\_1+ATTACHMENT+my-data  

#### **How to create the Marker file in Windows**

  You can create the Marker file in Windows using a text editor such as **Editor**. Any other text editor will  also work.  

1. open **Editor.**
2. Save the file with a name such as _.MARKER\_is\_finished\_E+PBHOUMIK\_PBHOUMIK+INTRA\_BREED\_GENETIC\_VARIABILITY\_OF\_DOGS+INTRA\_BREED\_GENETIC\_VARIABILITY\_OF\_DOGS\_EXP\_1+ATTACHMENT+my-data._
3. The file is automatically saved with a ".txt" extension. This needs to be removed.
4. Use the _Rename_ option to remove the extension from the file.

#### **How to create the Marker file on Mac**

  If you are not familiar with the command line, you can create a create an empty text file using for example the **TextEdit** application in a Mac. Any other text editor will also work.  

1. Open the **TextEdit** application and save an empty file with a name such as _.MARKER\_is\_finished\_E+PBHOUMIK\_PBHOUMIK+INTRA\_BREED\_GENETIC\_VARIABILITY\_OF\_DOGS+INTRA\_BREED\_GENETIC\_VARIABILITY\_OF\_DOGS\_EXP\_1+ATTACHMENT+my-data_.
2. Save to any format.
3. You will get a message to say that files starting with "." are reserved for the system and will be hidden. Confirm that you want to use "."
4. To show these hidden files, open the Finder and press **Command + Shift + . (period)**.
5. The file you saved before has an extension, that needs to be removed. If the extension is not shown in your Finder, go to Finder > Preferences menu, select the Advanced tab, and check the "Show all filename extensions" box.
6. Remove the extension from the file.

### Registration of metadata for datasets via dropbox

  Starting from openBIS version 20.10.2, the default eln-lims dropbox supports the registration of metadata for datasets. The metadata needs to be provided in a file called **metadata.json.** This file should be placed inside the folder with the openBIS-generated name described above, together with the folder containing the data. This is shown in the example below.  O+DEFAULT\_LAB\_NOTEBOOK+DEFAULT\_PROJECT+EXP1+ATTACHMENT+test-metadata is the folder with the openBIS-generated name. Inside this folder there is the metadata.json file and a folder called _default_ which contains the data (in this case one single file) to upload to openBIS.   ![](images/metadata-for-datasets.png)   For example, the metadata.json file for the default RAW\_DATA dataset type would be: { "properties" : { "$NAME" : "my raw data", "NOTES" : "This is a test for metadata upload via dropbox" } }   It is possible to download the template metadata.json file for each dataset type from the Tools Section under the Main menu. ![](images/ELN-Tools.png)   ![](images/Select-dataset.png)

The **Show available storage space** button, will feature the available storage space for data upload. This is helpful in calculating how much space one might require for future data upload, especially large data. 

![](images/Screenshot-2022-02-25-at-13.36.21-1024x514.png)
