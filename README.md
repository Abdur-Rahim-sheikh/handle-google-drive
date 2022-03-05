# handle-google-drive
# 1 unzip drive file
if your drive has large zipped file containing thousands of file then extracting it is painfull.
time lengthy, does not works as wanted but more importantly
**your data has to be extracted through third party so literally your data is stolen. So i built below script for myself
(and opened for you now)
my unzip_drive_file.ipynb script will take path (like abir/images/mine.zip) where the file is located
next it will take a path (like abir/collection) the destination and put everything in (abir/collection/mine) creating mine folder there and if there is already mine folder it will ask you permission too.

# 2 delete_drive_trash_permanently

We all know google provides us 15GB of free space to keep files.
And when we delete anyfile it goes to trash and takes 30days to completely removed. or we can forcefully delete them permanently

But what if we had to upload 5GB+ data with thousands of file then it's pain in the ass to permanently delete them.
You should know that if we click empty bin it does not work in google drive it stills occupies the memory. but selecting and deleting manually works

so i built the (permanently deleting from drive.ipynb) script it will delete all trash one by one.
load this script to your google colab and run last 2 cell
then give permission it asks for (totally safe as no third party included all handled by google colab)

But if you want to delete a directry and empty the trash then run all cell there is some guidline in the script too.