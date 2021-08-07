# Competition App

# **Flutter**
- Dart + Flutter
- compiled to native apps but not compile to Android/IOS UI components ( higher customization )
- other method : 
  - React ( FB )
  - Ionic ( Ionic ) : WebView hosted app
  - 
### Resources
- [ Tutorial ](https://www.youtube.com/watch?v=x0uinJvhNxI)
- [ Docs ](https://flutter.dev/docs/get-started/install)

### Android Studio
- AVD Manager
  - Android Virtual Device Manager
  - Android 9
- Select project -> select virtual device -> select image -> select graphic accelerate ( Hardware - GLES 2 )
- How to use
  - Select and active emulator
  - run in cmd : `
  - ```fluter=
    flutter run --enable-software-rendering
    ```

### IDE - Visual Studio

### What to work on
- [ 專題報告書 ](https://docs.google.com/document/d/1iIcWiJ6qVtjkYpUWrtz1eQjkjdJaXDp5zse60UG6JLg/edit)
- ![](https://i.imgur.com/QneKB7i.png)

### Desktop support
- ![](https://i.imgur.com/ikcnJ2A.png)

---

## **Ionic**
- [ Ionic Web ]( https://ionicframework.com/ )
- Learning Source :
  - [ 2Hrs Tutorial ](https://www.youtube.com/watch?v=mQ4zmFy4d7Y)
- Usage :
  - created an app on official website
  - link it with github and establish repo automatically
  - ```cmd=
    npm install -g @ionic/cli cordova-res
    git clone https://github.com/allchangechallenge/ionic-first.git ionic-first
    cd ionic-first && npm install && ionic serve
    ```
- Technology
  - Providing UI components
  - A lot like web developing
  - Work with React.js / Vue.js / Angular.js
  - **Capacitor** 
    - Wrap a web app into a native mobile app 
    - What Ionic is using to wrap its web app into mobile app
  - Wrote in TypeScript
  - Change to JavaScript
    ```cmd=
    npm uninstall --save typescript @types/jest @typescript-eslint/eslint-plugin @typescript-eslint/parser @vue/cli-plugin-typescript @vue/eslint-config-typescript
    ```
