How to Setup:
1. Create an EAS account
2. Open Command line and execute:
eas update:configure
3. Login to your account and the project will be set up accordingly

How to Use:
1. Create a first build to your prefered channel
ex: eas build --platform [android/ios] --profile [channel]
2. Install release build to emulator or test device
3. To trigger update execute:
eas update --platform [android/ios] --branch [channel] --message [update message]
4. Re-open the app and the update toast message should pop up and it will automatically install
