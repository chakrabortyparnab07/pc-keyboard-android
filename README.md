<resources xmlns:tools="http://schemas.android.com/tools">
    <style name="Theme.PcKeyboardApp" parent="Theme.MaterialComponents.DayNight.NoActionBar">
        <item name="colorPrimary">@color/purple_500</item>
        <item name="colorPrimaryVariant">@color/purple_700</item>
        <item name="colorSecondary">@color/teal_200</item>
    </style>

    <style name="KeyboardKeyStyle" parent="Widget.MaterialComponents.Button">
        <item name="android:layout_width">0dp</item>
        <item name="android:layout_height">40dp</item>
        <item name="android:layout_weight">1</item>
        <item name="android:layout_margin">2dp</item>
        <item name="android:backgroundTint">#3B82F6</item>
        <item name="android:textColor">#FFFFFF</item>
        <item name="android:textSize">12sp</item>
    </style>

    <style name="KeyboardKeyStyleWide" parent="KeyboardKeyStyle">
        <item name="android:layout_width">0dp</item>
        <item name="android:layout_weight">2</item>
    </style>
</resources>
