# 👗 Fashion Advisor - Kotlin Android App

A lightweight Android app built using **Kotlin** that allows users to manage fashion data using **local storage** — no database or internet required. It runs completely offline and is ideal for learners exploring Android app development with Kotlin.

---

## ✨ Features

- 🔒 **Offline Storage** – All data is saved locally using Android storage
- 📱 **USB Debugging Ready** – Easily tested on real devices via Android Studio
- 🎨 **Custom Fashion Screens** – Includes multiple fashion-related views/layouts
- ⚡ **Fast & Simple** – No external dependencies or APIs

---

## 📂 Project Structure

```text
FashionAdvisor/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/project/fashion/
│   │   │   │       ├── Dashboard.kt
│   │   │   │       ├── Signup.kt
│   │   │   │       └── Dao_Impl, DataBaseView_Impl etc.
│   │   │   ├── res/
│   │   │   │   └── drawable, layout, mipmap, values/
│   ├── build.gradle.kts
├── build.gradle.kts




🧑‍💻 How to Run
Clone the Repository

git clone https://github.com/Sasi173/FashionAdvisor-Kotlin.git

Open in Android Studio

Go to: File → Open → select FashionAdvisor folder

Enable USB Debugging on your Android phone

Connect phone & run the app using ▶️ in Android Studio

After Successful Instalation in your Mobile you can use disconnect with android studio.

you can use it as normal mobile app after installation.

⚙️ Built With
Kotlin

Android Studio

XML Layouts

Local Device Storage



🧠 Gemini API Usage Note
This app uses Google Gemini AI via an API key from Google AI Studio to provide intelligent fashion suggestions. Under the free tier, each API key supports approximately 1,500 requests.

⚠️ After reaching this limit, the app will stop generating responses until the API key is changed.

🔧 How to Continue Using the App
To continue using the app after the request limit is hit:

Visit https://https://ai.google.dev/aistudio

Generate a new Gemini API key

Open the app and go to the API Key input  (<>strings.xml) section.

Paste the new key

You're done — no rebuild is required

The App is ready to use again.


🏷️ Tags
#Kotlin #Android #LocalStorage #FashionApp #OfflineApp


🙋‍♂️ Author
Ajay Kumar
GitHub: @Ajay Kumar
