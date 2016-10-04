![](.guides/img/25.png)

Let’s look again at the `showAsAction` attribute in the menu resource code. Notice how the `showAsAction` attribute is prefixed with `app:` not `android:`

![](.guides/img/24.png)

Earlier in the chapter, you saw how our project had a dependency on the v7 appcompat library. The v7 appcompat library doesn’t include `showAsAction` in the android namespace.

**If your project has a dependency on the v7 appcompat library**, `showAsAction` must be prefixed with `app:`, and the `<menu>` attribute must include an attribute of:

`xmlns:app="http://schemas.android.com/apk/res-auto"`

**If your project has** *no* **dependency on the v7 appcompat library**, `showAsAction` must be prefixed with `android:`, not `app:`. You can also omit the attribute

`xmlns:app="http://schemas.android.com/apk/res-auto"` 

from the `<menu>` element.
