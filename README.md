
<?xml version="1.0" encoding="utf-8"?>

<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="150dp"
        android:background="#F8F8FF"
        android:padding="10dp"
        android:src="@drawable/foto121" />

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_weight="1"
        android:background="#000000"
        android:gravity="center"
        android:padding="10dp"
        android:text="Home"
        android:textColor="#FFFFFF"
        android:textSize="25sp"
        />
    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Bayu Sofiadi"
        android:background="#FFFFFF"
        android:textColor="#000000"
        android:gravity="center"
        android:padding="10dp"
        android:layout_weight="1"
        android:textSize="25sp"
        />
    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="181103442"
        android:background="#000000"
        android:textColor="#FFFFFF"
        android:gravity="center"
        android:padding="10dp"
        android:layout_weight="1"
        android:textSize="25dp"
        />
    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="bayusofian9@gmail.com"
        android:background="#FFFFFF"
        android:textColor="#000000"
        android:gravity="center"
        android:padding="10dp"
        android:layout_weight="1"
        android:textSize="25dp"
        />
    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="A4"
        android:background="#000000"
        android:textColor="#FFFFFF"
        android:gravity="center"
        android:padding="10dp"
        android:layout_weight="1"
        android:textSize="25dp"
        />
    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="STMIK PONTIANAK"
        android:background="#FFFFFF"
        android:textColor="#000000"
        android:gravity="center"
        android:padding="10dp"
        android:layout_weight="1"
        android:textSize="25dp"
        />
    <Button
        android:id="@+id/pindah2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Pemograman Mobile"
        android:layout_gravity="center_horizontal"
        android:onClick="Pemograman"/>
</LinearLayout>
