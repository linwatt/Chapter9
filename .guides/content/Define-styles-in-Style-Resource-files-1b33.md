A **style resource file** holds details of any themes you want to use.

When you create a project in Android Studio, the IDE creates a default style resource file for you called *styles.xml* located in the *app/src/main/res/values* folder. It will look something like this:

![](.guides/img/10.png)

The style resource file contains one or more styles. Each style is defined using the `<style>` element.

Each style must have a name, which you define with the `name` attribute. The style must have a name so that the `android:theme` attribute in *AndroidManifest.xml* can refer to it. In our case, the style has a name of `"AppTheme"`, so *AndroidManifest.xml* can refer to is using `"@style/AppTheme"`.

The `parent` attribute specifies where the style should inherit its properties from. In the case above, this is "`Theme.AppCompat.Light.DarkActionBar`".

You can also use the style resource file to customize the look of your app by modifying the properties of an existing theme. To do this, you add an `<item>` element to the `<style>` that describes the modification you want to make. 

As an example, here’s how you’d modify the theme so that all the activities have a red background:

![](.guides/img/11.png)
