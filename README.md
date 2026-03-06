# QUICK START GUIDE

1. DOWNLOAD: Get the .aar file from releases.
2. COPY: Paste the file into your project
3. GRADLE: Add this to app/build.gradle.kts:

dependencies {
    implementation(files("libs/ailurustheme-releaseXXX"))
}

4. MANIFEST: Add this to your AndroidManifest.xml and the icons targets to the "ic_ailurus(_round)":

<application
    android:theme="@style/Theme.Ailurus"
    ... >
</application>
