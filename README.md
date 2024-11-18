# 📍Intro
NewPass is a secure password management application designed to generate and store strong passwords locally on your device. With NewPass, you can create highly secure passwords for your accounts and services without the need to remember them.
> ⚠️ Please refrain from storing your passwords in NewPass at the moment, as it is currently undergoing active development and may not be completely secure. It's advisable to use NewPass solely for testing purposes and contributions until its security has been thoroughly vetted. ⚠️

## 🗝️ Key Features:
- **Password Generation**: NewPass provides a robust password generator that allows you to create complex and secure passwords tailored to your specific requirements. You can customize the length and the character set (Uppercase, Numbers and Special).

- **Local Storage**: Your passwords are stored locally on your device, ensuring complete privacy and control over your data. NewPass does not store any passwords on external servers, minimizing the risk of unauthorized access (If you uninstall the app, your password are lost!).

- **AES Encryption**: NewPass encrypts all stored passwords using Advanced Encryption Standard (AES) with [Galois/Counter Mode](https://en.wikipedia.org/wiki/Galois/Counter_Mode) (GCM) to ensure integrity and confidentiality before saving them in the local database.

- **SQLite Cipher**: NewPass utilizes SQLite Cipher, an extension for SQLite databases, to bolster security further by encrypting entirely the database, ensuring robust protection against unauthorized access. The encryption key is chosen by the user upon the first launch of the app, and it remains saved and encrypted in an EncryptedSharedPreferences. It is then requested every time the app is launched. 

- **User-Friendly Interface**: NewPass features an intuitive and user-friendly interface, making it easy to generate, view, and manage your passwords. The app offers convenient options for copying passwords to the clipboard and securely sharing them with other applications.
<br>

## 🧱 Build
1. First you need to get the source code of NewPass.
```
git clone https://github.com/Veolinan/NewPass.git
```
2. Open the project in [Android Studio](https://developer.android.com/studio).
3. When you click the `▶ Run` button, it will be built automatically.
4. Launch NewPass.
<br>

## 🫱🏻‍🫲🏼 Contributions and Development
If you wish to contribute to the NewPass project or report bugs, see the Instructions in [CONTRIBUTING.md](https://github.com/6eero/NewPass/blob/master/CONTRIBUTING.md).

### Contact us Securely
If you discover a security vulnerability, please inform us promptly. We prioritize investigating all legitimate reports and are committed to resolving issues promptly. For secure communication, encrypt messages using [NewPass's GPG key](https://github.com/6eero/NewPass/blob/master/public_key.asc) and send it to 
 `fmorara@kabarak.ac.ke`.
 
I accept and appreciate community contributions to continually improve the application.


## ⚒️ Future work
- [ ] Add option to autofill.
- [ ] Add an optional place holder in the add/update menu.
- [x] Allow exporting/importing backups.
- [x] Add an option to change the app password.
- [x] Implement login to NewPass with device lock screen credentials.
- [x] Add a vibration feedback.
- [x] Implement dark theme.
- [x] Add support for more languages.
<br>



<div align="right">
<table><td> 
<a href="#start-of-content">👆 Scroll to top</a>
</td></table> 
</div>
