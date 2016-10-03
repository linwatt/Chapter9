you can use different folder structures to get your app to use different resources at runtime. As an example, you saw how to get your app to use different layout files depending on the size of the device screen.

Here, we need the app to use a different style resource depending on the API level the app’s running on. To get the app to use a particular resource if the app’s running on API level 21, we can create a new values-v21 resource file and add the resource to this folder.

To do this, create a new folder in the app/src/main/res folder called values-v21. Then copy the file styles.xml from the values folder, and paste it in the values-v21 folder.
