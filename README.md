# CityGuide-Java
A project for CIS 454.


firebase config

// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyB_XEM6x5YveXFN3wS2ORseyJTi8U2kEME",
  authDomain: "city-guide-app-d48a9.firebaseapp.com",
  projectId: "city-guide-app-d48a9",
  storageBucket: "city-guide-app-d48a9.appspot.com",
  messagingSenderId: "181799342059",
  appId: "1:181799342059:web:96dac38be767878b0693ae",
  measurementId: "G-XKSVWTR37T"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
