# 📸 PhotoEditor Android App

An Android application built in Java that allows users to edit images using the **DS Photo Editor SDK**. The app provides filters, overlays, stickers, and other powerful image editing features.

---

## 🚀 Features

- ✨ Image filters and effects
- 🖼️ Crop, rotate, and draw on photos
- 🎨 Add text, stickers, and frames
- 📁 Pick image from gallery or camera
- 🧩 Integrated with DS Photo Editor SDK v10

---

## 📦 Dependencies

- DS Photo Editor SDK v10 (bundled as `.aar` in `app/libs`)
- [ImagePicker](https://github.com/Dhaval2404/ImagePicker) (`com.github.dhaval2404:imagepicker:2.1`)
- RxJava / RxAndroid
- Glide
- Dexter (for permission handling)

---

## 🛠️ Setup Instructions

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/PhotoEditor.git
   cd PhotoEditor
````

2. **Open in Android Studio**

3. **Add SDK file**

   * Make sure `ds-photo-editor-sdk-v10.aar` is placed in:

     ```
     app/libs/ds-photo-editor-sdk-v10.aar
     ```

4. **Sync Gradle**

   * Android Studio will auto-sync, or do it manually via `File > Sync Project with Gradle Files`

5. **Build and Run the app**

   * Connect a device or use emulator, then hit **Run**

---

## 📸 Screenshots

| Home Screen                 | Editor Screen               |
| --------------------------- | --------------------------- |
| *(Insert screenshots here)* | *(Insert screenshots here)* |

---

## 📂 Project Structure

```
PhotoEditor/
 ├── app/
 │    ├── libs/                  # Contains .aar file
 │    ├── src/                   # Java source files
 │    ├── res/                   # Layouts and resources
 │    └── build.gradle.kts       # App build config
 ├── settings.gradle.kts
 └── build.gradle.kts
```

---

## 🙋‍♀️ Author

**Nishtha Parashar**
*M.Tech | AIML*
Feel free to connect or suggest improvements!
Some files were hidden files so have not uploaded them.
---

## 📄 License

This project is for educational purposes.
DS Photo Editor SDK is proprietary software — used here under its original license for integration demonstration.

The DS Photo Editor sdk is removed by the admin but there is a reference video for getting that sdk if needed or else you can use different sdks as well.
[https://youtu.be/ZUf1PE9cZvY?feature=shared]
(https://youtu.be/ZUf1PE9cZvY?feature=shared)

