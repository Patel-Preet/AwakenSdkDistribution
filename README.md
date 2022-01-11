# AwakenSdkDistribution

Source: https://www.talentica.com/blogs/publish-your-android-library-on-jitpack-for-better-reachability/
Additional doc: Jitpack.yml

To obtain the 3 files open gradle -> publishing -> publishReleasePublicationToMavenLocal -> Files located in ~ [C:\Users\HP\.m2\repository\com\awakenmobile\awakensdk\1.0]

Usuage: 
    implementation 'com.github.Patel-Preet:AwakenSdkDistribution:1.0'

Additional dependencies:
    implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
    implementation(platform("com.squareup.okhttp3:okhttp-bom:4.9.0"))
    implementation("com.squareup.okhttp3:logging-interceptor")
    api 'com.github.bumptech.glide:glide:4.11.0'
    annotationProcessor 'com.github.bumptech.glide:compiler:4.11.0'
    api group: 'com.amazonaws', name: 'aws-android-sdk-sns', version: '2.19.1'
    api 'com.google.android.exoplayer:exoplayer-ui:2.12.0'
    api 'com.google.firebase:firebase-messaging:21.0.0'
    api "com.google.android.gms:play-services-location:17.1.0"
