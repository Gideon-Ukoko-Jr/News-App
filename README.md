# NewsAppV2
An android news app built with Java on Android Studio which implements the JSON News API. The app allows the user to open, search and view news headlines with the accompanying details(News Agency, Author, Date and Headline Image) and to read them in a built in webview.

Dependencies I used:
implementation 'androidx.appcompat:appcompat:1.2.0'
    implementation 'com.google.android.material:material:1.2.1'
    implementation 'androidx.constraintlayout:constraintlayout:2.0.4'
    testImplementation 'junit:junit:4.+'
    androidTestImplementation 'androidx.test.ext:junit:1.1.2'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.3.0'
    implementation 'com.google.android.material:material:1.2.1'

    //Retrofit
    implementation 'com.squareup.retrofit2:retrofit:2.4.0'
    implementation 'com.squareup.retrofit2:converter-gson:2.2.0'

    //Date/Time
    implementation 'org.ocpsoft.prettytime:prettytime:4.0.1.Final'

    //Picasso for image url
    implementation 'com.squareup.picasso:picasso:2.5.0'

    implementation "androidx.swiperefreshlayout:swiperefreshlayout:1.1.0"
