To get the share action provider to share content, you pass it an intent. The intent you pass it defines the content you want to share, and its type. As an example, if you define an intent that passes text with an `ACTION_SEND` action, the share action will offer you a list of apps on your device that are capable of sharing this type of data.

**1) Your activity creates an intent and passes it to the share action provider.**
The intent describes the content that needs to be shared, its type, and an action.

![](.guides/img/39.png)

**2) When the user clicks on the share action, the share action uses the intent to present the user with a list of apps that can deal with it.**
The user chooses an app, and the share action provider passes the intent to the app’s activity that can handle it.

![](.guides/img/40.png)