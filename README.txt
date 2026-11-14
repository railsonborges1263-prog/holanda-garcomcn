HOLANDA GARÇOM ONLINE - projeto Android (WebView)
1. Abra esta pasta no Android Studio (Open).
2. Aguarde o Gradle sincronizar.
3. Menu Build > Build Bundle(s) / APK(s) > Build APK(s).
4. O APK debug fica em app/build/outputs/apk/debug/app-debug.apk.
O HTML 3.0 está em app/src/main/assets/index.html.
O app exige internet para Firebase.
Antes de uso real, revise e restrinja as regras do Firebase RTDB; não use regras .read/.write apenas auth != null.
