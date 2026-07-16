# AniPulse

Нативное Android-приложение (Kotlin, Jetpack Compose, Material 3) для просмотра аниме с русской озвучкой — свой каталог, свой плеер (Media3 ExoPlayer), мини-соцсеть (чат, комментарии, друзья).

## Стек

- Kotlin, Jetpack Compose, Material 3
- Hilt (DI), Room (локальная база), Retrofit + kotlinx.serialization
- Media3 ExoPlayer
- EncryptedSharedPreferences для локального хранилища аккаунта

## Сборка

```
set JAVA_HOME=<путь к JDK 17>
gradle assembleDebug
```

Перед первой сборкой скопируйте `gradle.properties.example` в `gradle.properties` и заполните нужные значения (прокси не обязателен, если сеть открыта напрямую).

## Политика конфиденциальности и для правообладателей

- [Политика конфиденциальности](https://5-42-99-195.sslip.io/privacy)
- [Для правообладателей](https://5-42-99-195.sslip.io/for-right-holders)
