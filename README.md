<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.android.helloandroid.MainActivity"
    
        android:layout_weight="14"
        android:background="#0062ff"
        android:orientation="vertical">

        <ImageView
            android:layout_width="match_parent"
            android:layout_height="160dp"
            android:layout_weight="8"
            android:adjustViewBounds="false"
            android:cropToPadding="false"
            android:src="@drawable/udacity"
            android:visibility="visible" />

        <ImageView
            android:layout_width="match_parent"
            android:layout_height="60dp"
            android:layout_weight="3"
            android:src="@drawable/uda" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:fontFamily="sans-serif-light"
            android:paddingEnd="08dp"
            android:paddingLeft="16dp"
            android:paddingRight="16dp"
            android:paddingStart="16dp"
            android:paddingTop="08dp"
            android:text="Udacity "
            android:textColor="@android:color/white"
            android:textSize="24sp"
            android:textStyle="bold"
            />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:fontFamily="sans-serif-light"
            android:paddingEnd="08dp"
            android:paddingLeft="16dp"
            android:paddingRight="16dp"
            android:paddingStart="16dp"
            android:paddingTop="08dp"
            android:text="2465 Latham St, Mountain View, CA 94043"
            android:textColor="@android:color/white"
            android:textSize="20sp"
            android:textStyle="bold" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:fontFamily="sans-serif-light"
            android:paddingEnd="16dp"
            android:paddingLeft="16dp"
            android:paddingRight="16dp"
            android:paddingStart="16dp"
            android:paddingTop="08dp"
            android:paddingBottom="05dp"
            android:text="650-555-5555"
            android:textColor="@android:color/white"
            android:textSize="18sp"
            android:textStyle="bold" />

    </LinearLayout>

