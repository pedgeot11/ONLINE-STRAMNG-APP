<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#23232456"
    android:orientation="vertical"
    android:padding="10dp"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="10dp"
        android:layout_marginBottom="5dp"
        android:text="choose category"
        android:textColor="@color/cardview_dark_background"
        android:textSize="16sp"
        android:textStyle="bold"></TextView>

    <Spinner
        android:id="@+id/action_bar_spinner"
        android:layout_width="match_parent"
        android:layout_height="24dp"></Spinner>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="@android:color/background_light">

    </LinearLayout>

    <Button
        android:id="@+id/openAudioFiles"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="upload songs"
        android:textSize="16sp"></Button>

   

    <Button
        android:id="@+id/buttonUpload"
        android:layout_width="163dp"
        android:layout_height="170dp"
        android:layout_marginTop="10dp"
        android:text="upload"
        android:textStyle="bold"></Button>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <ProgressBar
            android:id="@+id/progressbar"
            style="@style/Widget.AppCompat.ProgressBar.Horizontal"
            android:layout_width="match_parent"
            android:layout_height="34dp"
            android:layout_marginTop="10dp"></ProgressBar>

        <TextView
            android:id="@+id/title"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="title"
            android:textStyle="bold"></TextView>

        <TextView
            android:id="@+id/album"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="album"
            android:textStyle="bold"></TextView>

        <TextView
            android:id="@+id/artist"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="artist"
            android:textStyle="bold"></TextView>

        <TextView
            android:id="@+id/dataa"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="dataa"
            android:textStyle="bold"></TextView>

        <TextView
            android:id="@+id/duration"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="duration"
            android:textStyle="bold"></TextView>

        <ImageView
            android:id="@+id/imageview"
            android:layout_width="150dp"
            android:layout_height="150dp"

    </LinearLayout>

    <Button
        android:id="@+id/openimageuploadactivity"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="open uploadactivity"></Button>

    <TextView
        android:id="@+id/textViewSongsFilesSelected"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginStart="10dp"
        android:gravity="center"
        android:text="no Files Selected"></TextView>

    <Button
        android:id="@+id/button"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Button" />


</LinearLayout>
