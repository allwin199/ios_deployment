# Flutter Ios deployment steps

Step1: Change app Icon

Step2: Change app name
```
Open Xcode -> Open project -> <project> -> ios -> Runner.xcworkspace -> Runner -> Identity(General Tab) -> Display Name
```

Step3: Create an app store developer account
```
https://developer.apple.com/programs/ -> Enroll (top right)
```

Step4: 
```
https://appstoreconnect.apple.com/login
```

Step5:
```
Naviagte to `MyApps` after logging in -> Click `+` icon -> New App
```

Step6: Register a new Bundle ID -> click on certificates, Identifiers and Profiles -> continue -> Register(top right)


Step7: Check whether the bundle Id is created
```
https://appstoreconnect.apple.com
```

Step8: Create SKU

Step9: Select  `Full access`

Step10:
```
Navigate to `MyApps` -> select the new app
```

Step11: Select `TestFlight` from the top -> fill all the necessary details -> save

Step12: 
```
open the project in Xcode and open the Runner.xcworkspace
```

Step13:
```
go to signing&capabilities -> Team -> slect the developer account
```

Step14:
```
select the bundle ID -> also check the Automatically manage singning
```

Step15:
```
On Top select `Any Ios device`
```

Step16:
```
Product(top menu) -> Archive
```

Step17:
```
once the archive is created -> Distribute App (to upload the app to App Store Connect) -> select App Store Connect -> click next -> click upload
```

Step18:
```
https://appstoreconnect.apple.com -> My Apps -> Select the app -> Test Flight
```

Step19:
```
Select our app -> Test Flight -> Test Information -> Add new Testers
```








