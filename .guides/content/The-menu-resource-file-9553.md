When you create a project containing an activity, Android Studio creates a default menu resource file for you. We told Android Studio to call this file *menu_main.xml*, and it created it in the *app/src/main/res/menu* folder. All menu resource files go in this folder.

![](.guides/img/22.png)

Here’s the menu resource file Android Studio created for us. It describes a single Settings action item that appears in the action bar overflow:

![](.guides/img/23.png)

Each menu resource file has a `<menu>` element at its root. A menu resource file defines a single menu, or set of items to be added to the action bar. Your app can contain multiple resource files, and this is useful if you want different activities to have different items on their action bars.
