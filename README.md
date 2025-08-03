# Privacy-Scanner-Application-On-Android
Privacy scanner for Android
A privacy scanner android app. That scans through all your android system and show privacy status.

Some screenshots attached here for ref.

Fig: 1.1 Splash Screen with customized icon
![splash-screen](https://github.com/user-attachments/assets/f4792071-f46f-4176-ba48-73647817c85a)

Fig: 1.2 Scan Screen
![scan-screen](https://github.com/user-attachments/assets/f68c9102-fb5a-4853-8ae8-9c846cdf2302)

Fig: 1.3 Home screen after finish scanning
![home-screen](https://github.com/user-attachments/assets/5a25a69e-2592-4f24-b9e9-47e20d6d29a3)

Features of the application

    User Installs the application

    User taps on the app icon.

    The app starts immidiately showing a scan screen

    This scanning process doesn't block the UI process. You can see the spinning animation without breaking.

    After scanning the whole system, the application shows all the applications in a LazyList view.

    User can tap on any application to see it's details.

    User can minimize the application and the state will still be hold by the lifecycle aware view model.

    All the heavy computational tasks are carried out by the Kotlin Coroutine where necessary.

    Taping on scan again button will allow user to scan the whole system again.

    The share button let's user share a small summary as text with any app that supports text sharing.
