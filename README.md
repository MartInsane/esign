# How to install IPA files without PC (E-Sign method)


Do you want to install **any IPA file** on your iOS device **without PC**? You are at the right place!
**E-Sign** is a tool app which lets you sign and download any IPA file.

<p align="center">
<img width="1920" height="1080" alt="esign app icon" src="https://github.com/user-attachments/assets/0c9ad746-923b-40dc-a340-a9596574c0be" />


> [!WARNING]
> Apps installed via sideload certificates remain functional **as long as the signing certificate is valid**. Certificates are typically valid for up to **1 year**, but may be revoked earlier by Apple, which can cause the apps to stop opening. In this case, download another version of E-Sign or a new certificate.
> \
> \
> Be careful of which **IPA file** you are installing on your device. Even though E-Sign is not a **malware**, the IPAs you sign can be.

> [!NOTE]
> This is not a jailbreaking method but a sideloading one!


## Requirements
- iOS/iPadOS device
- An internet connection


# I. Installing the DNS profile

1. On your iOS/iPadOS device, download the [DNS profile](https://github.com/MartInsane/esign/releases/tag/DNS) (called esign-dns-profile.mobileconfig). It is mandatory to install it because without this profile, you won't be able to open E-Sign and your IPAs.
   
2. Allow GitHub to download the DNS profile:

<p align="center">
<img width="600" height="399" alt="dns profile allow" src="https://github.com/user-attachments/assets/5bf0ee5c-cb2c-4679-a741-6d9bfce52986" />

3. After that, go to: "Settings > General > VPN & Device Management", and click on "DNS VIP".

4. Click on "Install", enter your passcode, then confirm the installation again.


# II. Installing the certificates

1. On your iOS/iPadOS device, install the [E-Sign certificates](https://github.com/MartInsane/esign/releases/tag/Certs) (called ESignCert.zip). It is mandatory to download it because without these certificates, you cannot install IPAs with E-Sign. (Read the Warning tab)

2. Click on "Download":
   
<p align="center">
<img width="600" height="255" alt="certs download" src="https://github.com/user-attachments/assets/f0cfda6b-ebe4-4fab-89f3-5bd9438c95ec" />




# III. Installing E-Sign

Next, we can finally download E-Sign!

1. From your iOS/iPadOS device, install one of the **E-Sign** versions you can find on this page:

> [!WARNING]
> You have to remember which **version** of E-Sign you have installed on your device. For example, if I installed "**E-Sign Aramco Services Company**", I have to remember that the version of this app is "**Aramco Services Company**".

> [!TIP]
> While trying to open the E-Sign you just installed, you might see a pop-up saying:
> "**Unable to Install E-Sign** - This app cannot be installed because its integrity could not be verified.".
>
> If this pop-up appears on your device, delete your E-Sign version and try to install another one until it says:
> "**Untrusted Enterprise Developer**".
> This pop-up is normal, you're going to see it at the next step.
>
> Also if you tried installing all the versions and if all of them said "Unable to Install", well you cannot do the whole method for the moment 😭 You can try reinstalling it in a few hours/days.
