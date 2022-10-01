# SOTP-SYNC OTP

## Objective
Nobody likes to take hands out of their keyboard and Open SMS to entre OTP on PCsSoo we ASHSYNCER's are making it effortless to get OTPs on PC browsers without touching phone in daily use.

## Implementation
An App on your smartphone which will read the OTPs that you recived and send it to your PCs browser, You can use it on the particular site you were trying to access it. Smooth, Secure and effortless

## Working
### Stack

We will be using the APP which will be built on React Native which has permission to read Messages and then encrypt the OTP locally on the app, the SERVER comes in Node/Express and then the CHROME-EXTENSION on the brower will get the encrypted message from backend which will be locally decrypted and user gets the OTP. We will implement Websockets with extension so that the server can send data to the extension.

### Security

End to Encryption will happen with the Advanced Encryption Standard(AES-128). The common private keys will be available to the extension and the app but not the server, This will happen with the Diffie Hillman Key Exchange.

The keys will be changing after every few minutes.We wont be sending the site adress or the username or the source, so that the OTP remains anonymous.The extension after getting the OTP will have the option to copy. If Multiple OTPs are to be used, we will be using the order of the OTPs we recived in time and then access it in order in our extension.

### Linking between app and extension

We will be Implementing One time QR code Scanning, The Extension will show the QR code and we scan it in phone and both are linked. The app can only be Linked with One extension, so that nobody else can use your OTPs on their Web extension. 

## Applications
When most people are Lazy to open phone while using PCs, we make it easy for them to use OTPs while they are on browser in one click with our extension.Traders, Investors, Developers, Students, Bankers, common people etc has to enter OTPs often while you are on Internet in PCs, whether you are Paying your bills, Ordering something, Accessing 2 Factor Auth, To Change your passwords, the use cases are endless.

## Later Improvements
We will be extending our Project to access OTPs/Verification codes sent on Mails.Insted of opening your mail in new tab and copy pasting it to the website, The Extension/App will read the mail and send Show the OTP on the website you are using with just one click which be secure and effortless. Also we will be making the OTP transfer using Bluetooth/Wifi-Hotspot/LAN so that the DATA doesnt have to go through the internet or the phone to have internet connection 24*7

and Lot of other Improvements in Future to make the Project reach millions and trust ASHSYNCER's.
