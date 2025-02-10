# AwakenSdkDistribution

Source: 
https://www.talentica.com/blogs/publish-your-android-library-on-jitpack-for-better-reachability/
https://medium.com/student-beans/publishing-a-library-as-a-aar-package-55ed725fa638

Additional doc: Jitpack.yml

To obtain the 3 files 
open gradle -> publishing -> publishReleasePublicationToMavenLocal
OR
./gradlew publishToMavenLocal 
RESULT: Files located in ~ [C:\Users\HP\.m2\repository\com\awakenmobile\awakensdk\1.0]

Usage: 
    implementation 'com.github.Patel-Preet:AwakenSdkDistribution:1.0'

Automatically import awaken dependencies using POM file using Jitpack
Source:
https://stackoverflow.com/a/46866517/10330317
https://stackoverflow.com/a/67071394/10330317

Transitive Deps Resolution
https://jeroenmols.com/blog/2020/11/11/library-dependencies/

For Jitpack private: https://docs.github.com/en/organizations/restricting-access-to-your-organizations-data/approving-oauth-apps-for-your-organization
