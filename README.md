# Mobile-Application-Development
# Ex.No:1
To create a HelloWorld Activity using all lifecycles methods to display messages.
# AIM:
To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

# EQUIPMENTS REQUIRED:
Latest Version Android Studio

# ALGORITHM:
Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

# PROGRAM:
Program to print the text “Hello World”.

# Activity_main.xml:
```
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android" xmlns:app="http://schemas.android.com/apk/res-auto" xmlns:tools="http://schemas.android.com/tools" android:layout_width="match_parent" android:layout_height="match_parent" tools:context=".MainActivity">

<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:textSize="40dp"
    android:text="Hello World!"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent" />
</androidx.constraintlayout.widget.ConstraintLayout>
```
# MainActivity.java:
```
package com.example.helloworld;
import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
import android.util.Log;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    private static final String TAG = "HelloWorldActivity";

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Log.d(TAG, "onCreate: ");
        Toast.makeText(this, "onCreate", Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onStart() {
        super.onStart();
        Log.d(TAG, "onStart: ");
        Toast.makeText(this, "onStart", Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onResume() {
        super.onResume();
        Log.d(TAG, "onResume: ");
        Toast.makeText(this, "onResume", Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onPause() {
        super.onPause();
        Log.d(TAG, "onPause: ");
        Toast.makeText(this, "onPause", Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onStop() {
        super.onStop();
        Log.d(TAG, "onStop: ");
        Toast.makeText(this, "onStop", Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onDestroy() {
        super.onDestroy();
        Log.d(TAG, "onDestroy: ");
        Toast.makeText(this, "onDestroy", Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Log.d(TAG, "onRestart: ");
        Toast.makeText(this, "onRestart", Toast.LENGTH_SHORT).show();
    }
}
```
Developed by: Roseline .B Registeration Number : 212221220046
# OUTPUT
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/8c4e6e52-ee80-4a2b-944a-ebe1183f3d10)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/ce97a24c-1935-4d3d-95fd-e38ebb456cab)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/f5be2c45-7a8c-4eeb-9e46-e57235b19ee7)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/19d961a3-48dd-405d-b609-33ecfffa911c)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/7829092a-f6c1-4edc-a645-34b1c29d7d4e)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/bc3966c6-75e7-4c9f-98cc-7e5792bcd7f3)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/ad4d37e8-c93b-45e5-8a92-d8d10056e3ea)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/7cfe6100-254b-4507-8f61-0b7f36ca3e83)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/7228a04b-c8d5-4b48-a7de-d88dfda24d10)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/a3994413-21bd-406f-b238-a5edc8b39ed4)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/e4080ee8-a58b-48d3-95f3-4a9a484ee8ea)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/a14a47a3-c3df-4f0a-b364-b914c1fc3e0d)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/c29e7346-1b69-4b54-b798-08dc90d730ce)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/8c63c112-e47e-4c4e-9126-7a70dd55720f)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/a4044ced-9f25-451a-922d-d9cbd0412318)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/162716a2-1850-4429-9f71-4b5e5c651a0e)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/3f4b4b6b-06b4-41ea-a953-8000a845ae87)
# RESULT:
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
