<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@color/material_dynamic_tertiary70"
    tools:context=".MainActivity">


<TextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:id="@+id/signuptitle"
    android:text="Sign Up"
    android:textSize="35dp"
    android:textStyle="bold"
    android:textColor="@color/white"
    android:gravity="center"
    android:layout_margin="25dp"/>

    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/username"
        android:layout_below="@id/signuptitle"
        android:background="#30ffffff"
        android:hint="Username"
        android:textColorHint="@color/white"
        android:layout_margin="18dp"
        android:padding="28dp"
        android:drawableLeft="@drawable/baseline_person_outline_24"
        android:drawablePadding="28dp"/>

    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/email"
      android:layout_below="@id/username"
        android:background="#30ffffff"
        android:hint="Email"
        android:textColorHint="@color/white"
        android:layout_margin="18dp"
        android:padding="28dp"
        android:drawableLeft="@drawable/baseline_email_24"
        android:drawablePadding="28dp"/>

    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/password"
        android:layout_below="@id/email"
        android:background="#30ffffff"
        android:hint="Password"
        android:textColorHint="@color/white"
        android:layout_margin="18dp"
        android:padding="28dp"
        android:drawableLeft="@drawable/baseline_info_24"
        android:drawablePadding="28dp"/>

    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/ConfirmPassword"
        android:layout_below="@id/password"
        android:background="#30ffffff"
        android:hint="Confirm Password"
        android:textColorHint="@color/white"
        android:layout_margin="18dp"
        android:padding="28dp"
        android:drawableLeft="@drawable/baseline_info_24"
        android:drawablePadding="28dp"/>
    
    <com.google.android.material.button.MaterialButton
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/signupbtn"
        android:layout_below="@id/ConfirmPassword"
        android:layout_centerHorizontal="true"
        android:hint="REGISTER"
        android:textSize="25dp"
        android:textColorHint="@color/white"
        android:backgroundTint="@color/design_default_color_secondary"
            android:layout_margin="20dp"/>

</RelativeLayout>
