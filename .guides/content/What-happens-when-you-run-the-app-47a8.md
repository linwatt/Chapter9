**1) When you run the app, Android sees that it needs to apply the theme described by @style/AppTheme.**

![](.guides/img/18.png)

**2) If the app’s running on API level 21, it uses the style called AppTheme in the values-21 folder.**
The style specifies a theme of `Theme.Material.Light`, so it applies this theme.

![](.guides/img/19.png)

**3) If the app’s running on an API level below 21, it uses the style called AppTheme in the values folder.**
The style specifies a theme of `Theme.Holo.Light`, so this theme is applied instead.

![](.guides/img/20.png)



