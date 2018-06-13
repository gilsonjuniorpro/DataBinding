# DataBinding

Android DataBinding provides a way to tie the UI with business logic allowing the UI values to update automatically without manual intervention. This reduces lot of boilerplate code in your business logic that you usually write to sync the UI when new data is available. DataBinding is one of the android architecture components suggested by android.

<b>Enabling DataBinding</b>
-------------

To get started with DataBinding, you need to enable this feature in your android project first. 
Open the build.gradle located under app and enable dataBinding under android module. 
Once enabled, Sync the project and you are good to go.

app/build.gradle
-------------
```gradle
android {
    dataBinding {
        enabled = true
    }
 
    compileSdkVersion 28
 
    //..
}
```



