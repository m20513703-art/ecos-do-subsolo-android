# Ecos do Subsolo — Android

Protótipo Android do jogo em primeira pessoa, feito como aplicativo de tela cheia com WebView local (HTML, CSS e JavaScript empacotados no APK). Inclui imagem de logo e sprite do zumbi dentro do pacote; não depende da internet durante o jogo.

## Gerar APK de teste

O workflow em `.github/workflows/android.yml` compila um APK de depuração com Gradle/Android SDK, faz verificações mínimas e anexa o APK à release `v0.1.0`.

`./gradlew assembleDebug` ou `gradle assembleDebug` (com JDK 17 e Android SDK).
