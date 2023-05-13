# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
Program to print the text “Hello World”.
## Activity_main.xml:
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

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

## MainActivity.java:
package com.example.myapplication;


import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);


    }
    protected void onStart() {
        super.onStart();
        Toast toast = Toast.makeText(getApplicationContext(),"on Create Called",Toast.LENGTH_LONG);
        toast.show();
    }
    @Override
    protected void onRestart() {
        super.onRestart();
        Toast toast = Toast.makeText(getApplicationContext(),"on Restart Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onPause() {
        super.onPause();
        Toast toast = Toast.makeText(getApplicationContext(),"on Pause Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onResume() {
        super.onResume();
        Toast toast = Toast.makeText(getApplicationContext(),"on Resume Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStop() {
        super.onStop();
        Toast toast = Toast.makeText(getApplicationContext(), "on Stop Called", Toast.LENGTH_LONG);
        toast.show();
    }
        protected void onDestroy() {
        super.onDestroy();
        Toast toast = Toast.makeText(getApplicationContext(),"on Destroy Called",Toast.LENGTH_LONG);
        toast.show();
    }
}

Developed by: Aishwarya.T.M
Registeration Number : 212221220002


## OUTPUT
![Screenshot (160)](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/cca92ea7-bd47-40cd-b258-fe366cd5bbef)

![Screenshot (163)](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/e5d7dc83-a09c-453e-acac-7e40deb47b22)

![Screenshot (169)](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/dd55a9fe-937c-4f86-9df2-7d37f72d2471)

![Screenshot (157)](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/037aacef-6407-409c-9edd-1c44652113f2)

![Screenshot (156)](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/7f10800f-33e5-48eb-9178-c7ed5682ea24)

![Screenshot (159)](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/fc495bad-5d25-438c-8b5f-37d850d4b92d)

![Screenshot (164)](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/1efe57a7-4436-4d2d-8034-4cb88d389e74)

![Screenshot (165)](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/7b67825f-f837-4796-b2b4-a363b0efd38b)

![Screenshot (166)](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/407ca2bc-15f6-4358-979a-fc8935d8e856)

![Screenshot (167)](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/1584d887-843b-4a44-9313-1098e696c2c8)

![Screenshot (168)](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/b10ef102-78dd-4d76-9261-124d5d5bb39f)

![4](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/623b2ac5-3cdf-453b-a771-e4dd59fdad13)

![6](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/fd9498aa-4631-4079-81f5-a2a94ba1e0c6)

![5](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/86e8703c-791f-4834-b90e-451576844e94)

![2](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/985ec39b-1e96-4ffc-a034-5fc6a1317f9f)

![1](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/2352a219-4670-45db-ba17-1529b171631e)

![3](https://github.com/suryacse05/Mobile-Application-Development/assets/127846109/887f2164-3c89-4dc2-adb2-e565412802d5)


## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
