# Fenrir VK GooglePlay
# Новый репозиторий https://github.com/umerov1999/Fenrir-for-VK
Первый языческий

<b>Языки: Русский, английский</b>

<b>Скриншоты:</b>
<img src="Fenrir_VK.jpg"/>

<b>Инструкция по сборке:</b>
Требуется:
  1) Android Studio Hedgehog (2023.1.1) или выше. Kotlin 1.9.*
  2) Android SDK 34
  3) Android NDK 26.0.10404224
  
  Если не работает музыка в Fenrir Kate, обновите kate_receipt_gms_token в app.build_config.
  Взять токен можно из Kate Mobile Extra Mod
  
<b>Компиляция:</b>

  1) Для релизных сборок вам нужен сертификат.
        keytool -genkey -v -keystore Fenrir.keystore -alias fenrir -storetype PKCS12 -keyalg RSA -keysize 2048 -validity 10000
  2) Выберите тип сборки (fenrir_vk_full) Debug или Release и соберите apk :)

Локальный медиа сервер https://github.com/umerov1999/FenrirMediaServer/releases

# FileGallery
Просмотр фото, видео, аудио, тэги

<b>Языки: Русский</b>

<b>Скриншот:</b>
<img src="FileGallery.jpg"/>
