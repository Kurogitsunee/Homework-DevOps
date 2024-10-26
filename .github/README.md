<p align="center">
  <img alt="Files hero image" src="./assets/ReadmeHero.png" />
</p>

Files - это современный файловый менеджер, который помогает пользователям организовывать их файлы и папки. Цель Files - создать лучший файловый менеджер для Windows, и команда разработки рада работать над проектом в открытую, чтобы каждый смог принять участие в процессе. Пользовательские отзывы помогают при добавлении новых возможностей, а сообщения об ошибках на GitHub позволяют сделать Files более надёжной программой. Созданный и поддерживаемый open-source сообществом, Files предоставляет невероятный опыт мультизадачности, файловых меток, глубоких интеграций и интуитивно понятный дизайн.

## Системные требования

- Windows 10 версии 19041.0 или более поздней
- 373,9 МБ свободного места

## Установка и запуск Files

Files - это проект, разрабатываемый сообществом, рост и развитие которого зависят от вашей поддержки. Пожалуйста, приобретите Files в Microsoft Stor или поддержите проект на [GitHub](https://github.com/files-community/Files), если собираетесь использовать классический установщик.

<p align="left">
  <!-- Store Badge -->
  <a style="text-decoration:none" href="https://apps.microsoft.com/detail/9NGHP3DX8HDX?launch=true&mode=full">
    <picture>
      <source media="(prefers-color-scheme: light)" srcset="./assets/StoreBadge-dark.png" width="220" />
      <img src="./assets/StoreBadge-light.png" width="220" />
  </picture></a>
  &ensp;
  <!-- Classic Installer Badge -->
  <a style="text-decoration:none" href="https://files.community/appinstallers/Files.stable.appinstaller">
    <picture>
      <source media="(prefers-color-scheme: light)" srcset="./assets/ClassicInstallerBadge-dark.png" width="220" />
      <img src="./assets/ClassicInstallerBadge-light.png" width="220" />
    </picture></a>
</p>

## Сборка из исходных файлов

### 1. Подготовка

Для сборки Files из исходных файлов необходимы:

- Visual Studio 2022 со следующими компонентами:
    - Windows 11 SDK (10.0.22621.0)
    - .NET 8 SDK (версия 8.0.303)
    - MSVC v143 - VS 2022 C++ x64/x86 или ARM64 build tools (последней версии)
    - C++ ATL for latest v143 build tools (x86 & x64 or ARM64)
    - Git для Windows
- Windows App SDK 1.5

### 2. Клонирование репозитория

В командной строке введите одну из ниже приведённых команд:

`git clone https://github.com/files-community/Files`

`git clone https://github.com/Kurogitsunee/Homework-DevOps`

Эта команда создаст локальную копию репозитория на вашем устройстве.

### 3. Развернуть проект в Visual Studio

Для сборки приложения в режиме разработки откройте sln-файл в Visual Studio (Files.sln) и установите проект Files.Packages, как входную точку, нажав правой кнопкой мыши на `File.Packages` в окне обозревателе решений (Solution explorer) и выберите пункт "Установить как входную точку" ("Set as Startup item").

На панели инструментов выберите ахритектуру вашей системы и укажите `Debug`. Теперь вы можете начинать сборку.

Также инструкция по самостоятельной сборке приложения находится на [сайте с документацией](https://files.community/docs/contributing/building-from-source).

___

[Основной репозиторий проекта](https://github.com/files-community/Files)


