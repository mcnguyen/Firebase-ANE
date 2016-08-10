Every release of Firebase ANEs will work with specific versions of Dependency ANEs and Frameworks. This document will tell you what dependencies and frameworks should be used in your project if you are building your project using different versions of Firebase ANEs.

**Note1**: Always try to use the latest releases because we won't be able to provide support on older versions.  
**Note2**: Always try to use the latest AdobeAir SDK. Doing this will automatically solve a lot of weird error messages.  
**Note3**: Firebase ANEs will not run on simulators. make sure you are building on a real device.  

# V1.1.0 #
Find the Android dependencies on [this branch](https://github.com/myflashlab/common-dependencies-ANE/tree/d2e6ca60f511ca4baf219a67de57ebda90d56772). *The master branch may have newer versions of these files but if you are building for the specified version number, you will need this specific branch.* And download the iOS frameworks [from here](https://dl.google.com/firebase/sdk/ios/3_4_0/Firebase.zip).

**firebaseCore.ane**
On the Android side:
* androidSupport.ane V23.4.0
* firebase_common.ane V9.4.0
* firebase_iid.ane V9.4.0
* googlePlayServices_base.ane V9.4.0
* googlePlayServices_basement.ane V9.4.0
* googlePlayServices_tasks.ane V9.4.0

On the iOS side:
* FirebaseAnalytics.framework V3.4.0
* FirebaseInstanceID.framework V3.4.0
* GoogleInterchangeUtilities.framework V3.4.0
* GoogleSymbolUtilities.framework V3.4.0
* GoogleUtilities.framework V3.4.0

**firebaseAuth.ane**
On the Android side:
* firebaseCore.ane V1.1.0
* + other ANEs required for the Core
* firebase_auth.ane V9.4.0
* firebase_authCommon.ane V9.4.0
* firebase_authModule.ane V9.4.0

On the iOS side:
* firebaseCore.ane V1.1.0
* + other frameworks required for the Core
* FirebaseAuth.framework V3.4.0
* GoogleNetworkingUtilities.framework V3.4.0
* GoogleParsingUtilities.framework V3.4.0

**firebaseDatabase.ane**
On the Android side:
* firebaseCore.ane V1.1.0
* + other ANEs required for the Core
* firebase_database.ane V9.4.0
* firebase_databaseConnection.ane V9.4.0

On the iOS side:
* firebaseCore.ane V1.1.0
* + other frameworks required for the Core
* FirebaseDatabase.framework V3.4.0

**firebaseRemoteConfig.ane**
On the Android side:
* firebaseCore.ane V1.1.0
* + other ANEs required for the Core
* firebase_config.ane V9.4.0

On the iOS side:
* firebaseCore.ane V1.1.0
* + other frameworks required for the Core
* FirebaseRemoteConfig.framework V3.4.0
* GoogleIPhoneUtilities.framework V3.4.0

**firebaseAnalytics.ane**
On the Android side:
* firebaseCore.ane V1.1.0
* + other ANEs required for the Core
* firebase_analyticsImpl.ane V9.4.0
* firebase-analytics.ane V9.4.0

On the iOS side:
* firebaseCore.ane V1.1.0
* + other frameworks required for the Core