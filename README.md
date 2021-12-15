# Food-delievery-app
This is an Android app .
It is used for ordering food and getting it delivered at your door step.
It has been completely made on ANDROID STUDIO using XML and KOTLIN.


# Project Directory Layout
.app
├── manifests 
    |---AndroidManifest.xml
├── java
    |---com.Deliciouspoint.Delicious
                 |---Activity
                          |---CartActivity
                          |---Dashboard
                          |---LoginRegisterActivity
                          |---OrderHistoryActivity
                          |---OrderPlacedActivity
                          |---ProfileActivity
                          |---RestaurantMainActivity
                          |---SplashActivity
                 |---Adapter
                          |---CartAdapter
                          |---DashboardFragmentAdapter
                          |---OrderHistoryAdapter
                          |---RestaurantMainAdapter
                 |---Database
                          |---Entities.kt
                          |---RestaurantDao
                          |---RestaurantDatabase
                 |---Fragment
                          |---DashboardFragment
                          |---FaqsFragment
                          |---FavouriteRestaurantFragment.kt
                          |---ForgotPasswordFragment
                          |---ForgotPasswordInputFragment
                          |---LoginFragment
                          |---ProfileFragment
                          |---RegisterFragment          
                 |---Model
                          |---CartItems
                          |---OrderHistoryRestaurant
                          |---Restaurant
                          |---RestaurantMenu
                 |---Utils
                          |---ConnectionManager
      |---com.Deliciouspoint.Delicious(/*androidTest*/)
                 |---ExampleInstrumentedTest
      |---com.Deliciouspoint.Delicious(/*test*/)
                 |---ExampleUnitTest
├── java(/*generated*/)
    |---com.Deliciouspoint.Delicious
                 |---BuildConfig
    |---com.Deliciouspoint.Delicious.database
                 |---RestaurantDao_lmpl
                 |---RestaurantDatabase_lmpl
├── res
    |---anim
          |---top_animation.xml
    |---drawable
          |---applogo.png
          |---ic_back_arrow.png
          |---ic_current_user.png
          |---ic_rating
    |---font
          |---aclonica.xml
    |---layout
          |---activity_cart.xml
          |---activity_dashboard.xml
          |---activity_profile.xml
          |---activity_splash.xml
    |---menu
          |---drawer_menu.xml
          |---menu_dashboard.xml
    |---mipmap
          |---applogo.png
    |---values
          |---colors.xml
          |---string.xml
          |---styles.xml
    |---xml
          |---network_security_confiq.xml
|---Gradle Scripts
          |---build.gradle(/*project:Delicious*/)
          |---build.gradle(/*Module:Delicious.app*/)
          |---graddle-wrapper.properties
          |---proguard_rules.pro
          |---build.gradle
          |---gradle.properties
          |---settings.gradle
          |---local.properties
                
                
 # How to Run
 
 After Cloning the Code Files on Your Android Studio
 ---> Wait until and unless the gradle sync takes place.
 
 If there happens to be a fail in gradle sync try using an external gradle source.
 ---> Settings -> Build,execution,Deployment -> Build tools -> Gradle.
 
 Look forward if there happens to be any pop-up message in Android studio related to updates please update it to the latest version.
 
 Setup the emulator by clicking on AVD manager and then create Virtual Device.
 
 # App Demo
 
 
 
