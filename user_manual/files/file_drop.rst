========================
Making anonymous uploads
========================

You may create your own special upload directories so that other people can upload
files to you without logging in to the server or having a Nextcloud account.
Uploaders cannot see the contents of the directory or make any changes. This is
an excellent alternative to sending large attachments via email, using an FTP
server, or using commercial file-sharing services.

Setting up your own file drop
-----------------------------

In the Files app, create or choose the folder to receive anonymous uploads, then click
the **Share** icon on that folder to open the sharing panel:

.. image:: ../images/anonym_click_sharing.png
   :alt: Sharing settings panel for a folder

Click **Share link** to create a public link, then open its **...** menu and select the
**File drop (upload only)** permission:

.. image:: ../images/sharing_public_folder.png
   :alt: Public folder share options with the File drop permission selected

With **File drop**, uploaders cannot see, download, or modify files that are already in
the folder — they can only add new files to it.

Now you can send the link to the upload folder manually or by using the
Nextcloud send function, if your administrator has enabled it.


Uploading files
---------------

Using the anonymous upload function is simple. You receive a link to the upload
folder, click the link, and then you'll see a Nextcloud page with a "**Click to
upload**" button:

.. image:: ../images/anonym_upload.png
   :alt: Anonymous upload page with a click to upload button

This opens a file picker, and you select the file or directory you want to
upload. You can also drop files into the window.

When your upload is completed, the filenames are listed:

.. image:: ../images/anonym_uploaded_files.png
   :alt: List of successfully uploaded files
