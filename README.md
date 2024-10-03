# Dependencies

##   hilt viewModel
    implementation("androidx.hilt:hilt-navigation-compose:1.2.0")

##   Gemini - Generative AI
    implementation("com.google.ai.client.generativeai:generativeai:0.9.0")

##    Navigation
    implementation("androidx.navigation:navigation-fragment-ktx:2.8.0")
    implementation("androidx.navigation:navigation-ui-ktx:2.8.0")
    implementation("androidx.navigation:navigation-compose:2.8.0")

##    Retrofit for handling API requests
    implementation("com.squareup.retrofit2:retrofit:2.9.0")
    implementation("com.squareup.retrofit2:converter-gson:2.9.0")

##   Picasso for loading images from URLs
    implementation("com.squareup.picasso:picasso:2.8")
    implementation("com.github.bumptech.glide:glide:4.16.0")

##   Dagger hilt
    implementation("com.google.dagger:hilt-android:2.50")
    implementation("androidx.hilt:hilt-navigation-compose:1.2.0")
    kapt("com.google.dagger:hilt-compiler:2.50")

##   CardView
    implementation("androidx.cardview:cardview:1.0.0")

##   Room db
    implementation("androidx.room:room-common:2.6.1")
    implementation("androidx.room:room-ktx:2.6.1")
    kapt("androidx.room:room-compiler:2.6.1")

#   Work manager
    implementation("androidx.work:work-runtime-ktx:2.9.0")


#  plugins
 
    id("com.android.application")
    id("org.jetbrains.kotlin.android")
    id("org.jetbrains.kotlin.kapt")
    id("dagger.hilt.android.plugin")
    id("kotlin-kapt")

    id("com.google.dagger.hilt.android") version "2.48.1" apply false
    id("com.google.gms.google-services") version "4.4.0" apply false
    id("com.google.firebase.crashlytics") version "2.9.9" apply false
    id("com.google.devtools.ksp") version "1.9.0-1.0.13" apply false
