# Firebase_RealtimeDB
# https://www.youtube.com/watch?v=BOITPwChVP4&list=PLrb70iTVZjZMQGywkJ8nsXG7_ZyHc_rAV
# https://console.firebase.google.com/u/0/project/leroyclonerealtor/overview

## npm install firebase
# -------------------------------------Use npm ----------------------------------------

If you're already using npm and a module bundler such as webpack or Rollup, you can run the following command to install the latest SDK (Learn more):

npm install firebase
Then, initialize Firebase and begin using the SDKs for the products you'd like to use.

// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyBB0f4W6Si3SkqKJAc0w0-rkycVyESXEUA",
  authDomain: "leroyclonerealtor.firebaseapp.com",
  projectId: "leroyclonerealtor",
  storageBucket: "leroyclonerealtor.appspot.com",
  messagingSenderId: "520332600560",
  appId: "1:520332600560:web:42bf14a1da2faaf6358e35",
  measurementId: "G-F0HJGP17LY"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
# -------------------------------------Use a <script> tag  ----------------------------------------
<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/9.21.0/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/9.21.0/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyBB0f4W6Si3SkqKJAc0w0-rkycVyESXEUA",
    authDomain: "leroyclonerealtor.firebaseapp.com",
    projectId: "leroyclonerealtor",
    storageBucket: "leroyclonerealtor.appspot.com",
    messagingSenderId: "520332600560",
    appId: "1:520332600560:web:42bf14a1da2faaf6358e35",
    measurementId: "G-F0HJGP17LY"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>