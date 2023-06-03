# Ex.No:10 To create a option menu to display menu items.


## AIM:

To create a option menu to display menu items using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:
Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as optionmenu and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout using UI components in activity_main.xml.

Step 6: Display the calculator operation in MainActivity file.

Step 7: Save and run the application.


## PROGRAM:
```
/*
Program to print the text “optionmenu”.
Developed by:B.Roseline
Registeration Number :212221220046
*/
```
# Activity_main.xml:
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
```
              xmlns:tools="http://schemas.android.com/tools"
          
android:layout_width="match_parent"
          
android:layout_height="match_parent"
          
android:orientation="vertical"
          
android:padding="16dp"
          
tools:context=".MainActivity">

<TextView
    android:id="@+id/messageTextView"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:text="Select an option from the menu"
    android:textSize="25dp" />
  ```
  # MainActivity.java:
  package com.example.optionmenu;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

import android.view.Menu;

import android.view.MenuItem;

import android.widget.TextView;

import android.widget.Toast;

public class MainActivity extends AppCompatActivity {
  ```
  private TextView messageTextView;

@Override
protected void onCreate(Bundle savedInstanceState) {

    super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_main);

    messageTextView = findViewById(R.id.messageTextView);
}

@Override
public boolean onCreateOptionsMenu(Menu menu) {

    getMenuInflater().inflate(R.menu.options_menu, menu);
    return true;
}

@Override
public boolean onOptionsItemSelected(MenuItem item) {
    int itemId = item.getItemId();

    switch (itemId) {
        case R.id.menu_item_1:
            messageTextView.setText("Option 1 selected");
            return true;
        case R.id.menu_item_2:
            messageTextView.setText("Option 2 selected");
            return true;
        case R.id.menu_item_3:
            messageTextView.setText("Option 3 selected");
            return true;
        default:
            return super.onOptionsItemSelected(item);
    }
}
  ```
  # Option_View.xml:
  ```
  <item
    android:id="@+id/menu_item_1"
    android:title="Option 1"
    android:textSize="25dp"/>
<item
    android:id="@+id/menu_item_2"
    android:title="Option 2"
    android:textSize="25dp"/>
<item
    android:id="@+id/menu_item_3"
    android:title="Option 3"
    android:textSize="25dp"/>
  ```
  
## OUTPUT

# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/feffc18e-7b58-4534-9a52-77385e76d238)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/f3d7be88-c44d-417a-b7a5-2be3d70b36e8)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/784c3f3b-e0b8-4e8c-912a-5471a057d981)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/d3b81058-ab21-4cc2-8553-4a71b1257b68)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/1f2d90e9-88eb-4c2c-98bb-0aa675479bec)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/30ff0c46-2ecc-48f7-86a6-7ff5b04cfccf)



## RESULT
Thus a Simple Android Application to create a option menu to display menu items using Android Studio is developed and executed successfully.


