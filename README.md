# Android-Push-Notification-Using-Firebase
Android Push Notification using Google Firebase 

Add This Service in the Android Manifest File 

        <service android:name=".common.MyFirebaseMessagingService">
            <intent-filter>
                <action android:name="com.google.firebase.MESSAGING_EVENT" />
            </intent-filter>
        </service>
        
        <service android:name=".common.MyFirebaseInstanceIDService">
            <intent-filter>
                <action android:name="com.google.firebase.INSTANCE_ID_EVENT" />
            </intent-filter>
        </service>
