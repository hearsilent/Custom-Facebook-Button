# Custom Facebook Button

An android custom facebook button.

## Screenshot
<img src="https://raw.githubusercontent.com/hearsilent/Custom-Facebook-Button/master/screenshots/device-2017-03-13-115743.png" height="500">

## Usage

### Don't need to clone this repo

1. Add the drawable res (found in the [drawable](/app/src/main/res/drawable) folder) to your project. Place the following files in the drawable folder:
    * [`Facebook Button`](app/src/main/res/drawable/button_facebook.xml)
    * [`Facebook Login Button`](app/src/main/res/drawable/button_facebook_login.xml)
    * [`Facebook Login Button Silver`](app/src/main/res/drawable/button_facebook_login_silver.xml)

2. Add the logo icon res (found in the [drawable (any dpi)](/app/src/main/res) folder) to your project. Place the following files in the drawable (any dpi) folder:
    * [`Facebook Logo`](app/src/main/res/drawable-xxxhdpi/ic_facebook_white_24dp.png) (`Facebook Button` or `Facebook Login Button`)
    * [`Facebook Logo Silver`](app/src/main/res/drawable-xxxhdpi/ic_facebook_silver_24dp.png) (`Facebook Login Button Silver`)

3. Customize your button.
 ```xml
<Button
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:background="@drawable/button_facebook_login"
    android:text="Facebook Login Button"
    android:textAllCaps="false"/>
```

## Compatibility

Android GINGERBREAD 4.0.3+

## Credits

Logos and Button drawables from [facebook/facebook-android-sdk](https://github.com/facebook/facebook-android-sdk/tree/master/facebook/src/main/res).
