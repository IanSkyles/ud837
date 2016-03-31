# ud837
Udacity's Android Development for Beginners
##Lesson 1
###Tips and Tricks
####Useful Links
* [Material Design color palette](http://www.google.com/design/spec/style/color.html#color-color-palette)
* [Common android views](https://drive.google.com/file/d/0B5XIkMkayHgRMVljUVIyZzNmQUU/view)
* [Typography](http://www.google.com/design/spec/style/typography.html#typography-styles)
* [XML Visualizer](http://labs.udacity.com/android-visualizer/#/android/text-color)
####Useful Code
* set the background color, text color, and text apperance (dynamically size text based on android and other apps.
```
<TextView
    android:text="Excited for the gift you'll surprise me with."
    android:background="#F44336"
    android:textColor="#FFFFFF"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:textAppearance="?android:textAppearanceLarge"/>
```
* Set up and image view. Replace `scaleType="center"` with `scaleType="centerCrop` to make the image fit the view.
```
<ImageView
    android:src="@drawable/cake"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:scaleType="center"/>
```
