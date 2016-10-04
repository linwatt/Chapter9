To get the share action to share content when it’s clicked, you need to tell it what to share in your activity code. You do this by passing the share action provider an intent using its `setShareIntent()` method. Here’s how you’d get the share action to share some default text when it’s clicked:

![](.guides/img/44.png)

You need to call the share action provider’s `setShareIntent()` method whenever the content you wish to share has changed. As an example, if you’re flicking through images in a photo app, you need to make sure you share the current photo.


