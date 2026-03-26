# Uber Clone 🚖📱

An Android application project that replicates the core functionality of Uber.  
This project demonstrates ride-hailing features such as user registration, driver tracking, Google Maps integration, and payment handling. It is built with **Java, Firebase, and Google APIs**, and follows a step-by-step tutorial series.

---

## 🚀 Live Demo
Check out the live version here:  
👉 [Uber Clone Website](https://md-moklesar-rahman-bappy.github.io/UberClone/)

---

## 📂 Repository
GitHub Repository: [UberClone](https://github.com/Md-Moklesar-Rahman-Bappy/UberClone)

---

## ✨ Features
- Rider and driver registration/login via Firebase  
- Real-time location tracking with Google Maps API  
- Ride request and acceptance flow  
- Firebase integration for authentication and storage  
- PayPal integration for payouts and payments  
- Responsive and scalable Android app design  

---

## 🛠️ Technologies Used
- **Java (Android Studio)** – Core app development  
- **Firebase** – Authentication, database, and storage  
- **Google Maps API** – Location and route tracking  
- **Google Places API** – Autocomplete for addresses  
- **Geofire** – Location queries in Firebase  
- **Glide** – Image loading and caching  
- **Node.js** – PayPal payout functions  

---

## 📦 Installation & Setup

### 1. Project Setup
1. Clone the repository:
```bash
   git clone https://github.com/Md-Moklesar-Rahman-Bappy/UberClone.git
```
2. Open the project in Android Studio.
3. Important: Change the package name. [Guide here](https://stackoverflow.com/questions/16804093/rename-package-in-android-studio).

---

### 2. Firebase Setup
1. Create a Firebase project: [Firebase Console](https://console.firebase.google.com/).
2. Import google-services.json into your project.
3. Change Pay Plan to Flame or Blaze.
4. Enable Email Authentication in Firebase.
5. Enable Firebase Storage.

---

### 3. Google Maps Setup
1. Add your project to the [Google API Console](https://console.cloud.google.com/).
2. Enable Google Maps API and Google Places API.
3. Add your API key to res/values/strings.xml under google_maps_key.

---
 
### 4. PayPal Integration
1. Install Node.js.
2. Create a PayPal developer app and enable payouts.
3. Add PayPal credentials to your Node.js project.
4. Set payout fee percentage in index.js.
5. Deploy the Node.js project.
6. In Android Studio, update PayPalConfig.java with:
- PAYPAL_CLIENT_ID from PayPal developer panel
- PAYPAL_PAYOUT_URL from Firebase Functions

---

## 📸 Screenshots
Add screenshots or GIFs of your Uber Clone app here for better presentation.

---

## 📚 Resources
- [Full Video Tutorial Playlist](https://www.youtube.com/playlist?list=PLxabZQCAe5fgXx8cn2iKOtt0VFJrf5bOd)
- [Lesson: Import Project](https://www.youtube.com/watch?v=2TkNZ-Vael4)
- [Uber Firebase Functions](https://github.com/SimCoderYoutube/uberFirebaseFunctions)
- [Glide](https://github.com/bumptech/glide)
- [Google Directions Android](https://github.com/jd-alexander/google-directions-android)

## 🤝 Contributing
Contributions are welcome!
If you’d like to improve this project:
1. Fork the repository
2. Create a new branch (feature-xyz)
3. Commit your changes
4. Open a Pull Request

---

## 📜 License
This project is licensed under the MIT License – feel free to use and modify it.

---

## 👤 Author
Md Moklesar Rahman (Bappy)
- GitHub: @Md-Moklesar-Rahman-Bappy
- Live Demo: UberClone

---

✅ This README integrates the **repo details, tutorial links, Firebase/Google Maps setup, and PayPal integration guide**.  

👉 Would you like me to also add a **workflow diagram** (showing Rider → Request → Driver → Payment → Firebase) so the README visually explains the app flow?

