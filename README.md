# Inspection_Administration

Inspection Administration إدارة التفتيش

```cmd
python -m venv inspection_administration_virtual_environment
```

```cmd
inspection_administration_virtual_environment\Scripts\activate

```

###### 🔧 Install Django 🦄

```cmd
pip install django
pip install djangorestframework
pip install djangorestframework-simplejwt
pip install django-allauth
pip install django-cors-headers
pip install pillow
pip install django-geoposition
pip install django-leaflet
pip install django-channels
pip install channels-redis
pip install folium
pip install geopy
pip install reportlab
pip install xlsxwriter

pip install firebase-admin

django-admin startproject inspection_administration_django
cd inspection_administration_django
```

### 👤 Create Django App Account

```cmd
حساب المستخدم
python manage.py startapp user_account
خط سير
python manage.py startapp itinerary
الفنيين
python manage.py startapp technician
السواقين
python manage.py startapp driver
الإشعارات والتنبيهات
python manage.py startapp notification
محادثة
python manage.py startapp chat
أجهزة الصراف الآلي
python manage.py startapp atm
التفتيش والتقارير
python manage.py startapp inspection
الشكاوى والمخالفات
python manage.py startapp complaint
```

```cmd
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
python manage.py runserver 0.0.0.0:8000
```

---

---

---

---

---

---

---

---

### 🌊 Run Vue

```cmd
npm install
npm run format
npm run build
npm run dev
npm run dev -- --host
```

```
npm i tailwindcss-primeui
npm install -D postcss-import
npm install -D tailwindcss@latest postcss@latest autoprefixer@latest
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

```

# ? Firebase

```
npm install firebase
npm install -g firebase-tools
firebase login
firebase init
LearnCodingEasy/Inspection-Administration
firebase deploy
firebase deploy --only hosting

firebase.js
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyAfR8wXTY0uVrgSVCVZcAGXX934BWh7sTo",
  authDomain: "inspection-administratio-10.firebaseapp.com",
  projectId: "inspection-administratio-10",
  storageBucket: "inspection-administratio-10.firebasestorage.app",
  messagingSenderId: "51270244227",
  appId: "1:51270244227:web:71e4c41ce7b5d89d4f88b6",
  measurementId: "G-QRBR5HFYRC"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
```

---

---

---

---

---

---

---

---

# Github

```
.gitignore
git status
git add *
git commit -m "Commit Explain Code"
git push origin main

```
