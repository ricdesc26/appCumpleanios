# appCumpleanios

## DESCRIPCIÓN

Está app está diseñada para ser una tarjeta de regalo electrónica mostrada a través de un aplicación móvil. (Para mostrar así, el uso de algunos de los elementos usados en Android, tales como TextView, ImageView, y algunas de sus propiedades

## MUESTRA FINAL

![Preview de la app](previewAppCumple.PNG "Preview")

## CÓDIGO XML
~~~
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#344955"
    tools:context=".MainActivity">

    <RelativeLayout
        android:orientation="horizontal"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content">

        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:scaleType="centerCrop"
            app:srcCompat="@drawable/androidparty" />

        <TextView
            android:id="@+id/textView"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="HAPPY BIRTHDAY, FRANCISCO!!"
            android:textColor="#ffffff"
            android:textSize="30sp" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="FROM RICARDO!!"
            android:textColor="#ffffff"
            android:textSize="30sp"
            android:layout_marginStart="150dp"
            android:layout_marginTop="550dp"/>

    </RelativeLayout>

</android.support.constraint.ConstraintLayout>
~~~
Se usa un relative Layout para poder acomoder los elementos a placer
Se pone primero la ImageView para que los textos no sean tapados por la imagen
A la imagen se le pone la propiedad scaleType:"centerCrop" para que ocupe toda la pantalla

## IMAGEN USADA DE FONDO

![Imagen de fondo](androidparty.jpg "Fondo")
