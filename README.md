Sample: bluelist-base-android
===

The bluelist-base-android sample is the base version of BlueList, a simple grocery list application.  In bluelist-base-android, the items do not persist to a mobile backend. If you want to persist items to a mobile backend, use the bluelist-mobiledata-android sample.

This sample can be built upon to work with the Mobile Cloud, an application boilerplate that is available on [IBM Bluemix](https://www.ng.bluemix.net).  With this boilerplate, you can quickly incorporate pre-built, managed, and scalable cloud services into your mobile applications without relying on IT involvement. You can focus on building your mobile applications rather than the complexities of managing the back end infrastructure.

Creating the Mobile Cloud boilerplate application
---
1. Login to [IBM Bluemix](https://www.bluemix.net)
2. Click 'Catalog' or 'Create An App'
3. Under Boilerplates, select Mobile Cloud.
4. Enter in App Info & select 'Create'
5. You now have a mobile cloud backend, providing you with some mobile services on the cloud!

Downloading this sample
---
You can clone this sample from IBM DevOps Services with the following command:

    git clone https://hub.jazz.net/git/mobilecloud/bluelist-base

The bluelist-base-android sample will be located within the bluelist-base directory you just created.

Running this Android sample (bluelist-base-android)
---

After cloning you can then import the bluelist-android-base code into your Android development environment. Build and run this code in your android mobile emulator. Restart the application, and notice that the list items do not persist.

If you'd like to utilize the mobile data service, so that your items do persist, see the instructions in [Build an Android app using the Mobile Data cloud service](http://www.ibm.com/developerworks/library/mo-android-mobiledata-app/index.html).
