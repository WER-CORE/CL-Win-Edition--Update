<div align="center">

# Clegendary Launcher

**Український лаунчер для Minecraft: Java Edition**

[![Останній реліз](https://img.shields.io/github/v/release/WER-CORE/CL-Win-Edition--Update?label=Реліз&style=flat-square)](https://github.com/WER-CORE/CL-Win-Edition--Update/releases/latest)
[![Завантаження](https://img.shields.io/github/downloads/WER-CORE/CL-Win-Edition--Update/total?label=Завантаження&style=flat-square)](https://github.com/WER-CORE/CL-Win-Edition--Update/releases)
[![Український проєкт](https://img.shields.io/badge/Зроблено_в-Україні-0057b7?style=flat-square)](https://github.com/WER-CORE/CL-OpenSource)

[**Офіційний сайт**](https://cl-launcher.app/) · [**Документація**](https://wiki.cl-launcher.app/) · [**Завантажити**](https://github.com/WER-CORE/CL-Win-Edition--Update/releases/latest) · [Вихідний код](https://github.com/WER-CORE/CL-OpenSource) · [Повідомити про проблему](https://github.com/WER-CORE/CL-OpenSource/issues) · [Discord](https://discord.gg/RhyZjACs2U)

**Мови README:** [Українська](README.md) · [English](README_Translate/README_en_US.md)  
Переклади іншими мовами: [долучитися на Crowdin](https://uk.crowdin.com/project/clegendary-launcher)

</div>

---

> [!NOTE]
> Це репозиторій **релізів та оновлень** Clegendary Launcher. Вихідний код і матеріали для розробників розміщено в [CL-OpenSource](https://github.com/WER-CORE/CL-OpenSource).

## Про лаунчер

**Clegendary Launcher (CL)** — відкритий український лаунчер для Minecraft: Java Edition. Він об'єднує запуск гри, керування версіями та модифікаціями в одному інтерфейсі.

Ми розвиваємо українське програмне забезпечення та прагнемо зробити його зручним для щоденного використання.

## Можливості

- **Версії Minecraft.** Встановлення та запуск підтримуваних версій гри.
- **Історичні версії.** Pre-Classic, Classic, Indev, Infdev, Alpha та Beta завдяки інтеграції з [BetaCraft](https://betacraft.uk/). Сумісність окремих збірок залежить від ОС і середовища Java.
- **Моди та контент.** Пошук і встановлення контенту з [Modrinth](https://modrinth.com/) та [CurseForge](https://www.curseforge.com/minecraft).
- **Завантажувачі модів.** Підтримка кількох екосистем, зокрема Forge, Fabric, Quilt і NeoForge; доступність конкретного завантажувача залежить від версії гри.
- **Авторизація.** Вхід через підтримувані способи авторизації, зокрема Microsoft Account і LittleSkin.
- **Налаштування.** Параметри запуску, оформлення та керування встановленими версіями.

## Інтерфейс

<div align="center">
<img width="750" alt="Інтерфейс Clegendary Launcher — скриншот 1" src="https://github.com/user-attachments/assets/4f4696dd-031d-4d5f-b564-2b5225a62ace" />
<img width="750" alt="Інтерфейс Clegendary Launcher — скриншот 2" src="https://github.com/user-attachments/assets/6d77eea0-c810-4a59-a42f-980b633d2ff1" />
</div>

## Завантаження та встановлення

1. Відкрийте [офіційний сайт](https://cl-launcher.app/) або сторінку [останнього релізу](https://github.com/WER-CORE/CL-Win-Edition--Update/releases/latest).
2. Перегляньте опис випуску та список доступних файлів.
3. Завантажте збірку для своєї операційної системи (усі офіційні збірки є self-contained — окремо встановлювати .NET Runtime не потрібно).
4. Встановіть або розпакуйте лаунчер відповідно до інструкцій у релізі.

### Linux (Flatpak-репозиторій)

Рекомендований спосіб встановлення на Linux (`x64`) — через власний GPG-підписаний Flatpak-репозиторій CL:

```bash
flatpak install --user -y https://wer-core.github.io/CL-OpenSource/cl.flatpakref
```

Оновлення через підключений репозиторій доступні командою `flatpak update io.github.wer_core.cl-opensource` (автоматичне встановлення оновлень залежить від налаштувань вашої системи та центру застосунків).

Як альтернативу на сторінці релізів також можна завантажити **AppImage** (`x64` / `arm64`) або офлайн-пакет **`CLegendaryLauncher-x64.flatpak`** для ручного встановлення.

> [!IMPORTANT]
> **Безпека завантаження**
>
> Завантажуйте Clegendary Launcher лише з офіційних джерел:
>
> - [Офіційний сайт Clegendary Launcher](https://cl-launcher.app/)
> - [GitHub Releases](https://github.com/WER-CORE/CL-Win-Edition--Update/releases/latest)
>
> Оскільки лаунчер наразі не має цифрового підпису, Windows SmartScreen може показувати попередження про невідомого видавця.
>
> Перед запуском переконайтеся, що файл завантажено з одного з офіційних джерел. Якщо маєте сумніви щодо його походження, не запускайте файл.

## Сумісність

| Wersja          | Windows | Linux | macOS | Статус                            |
| --------------- | :-----: | :---: | :---: | --------------------------------- |
| **CL Avalonia** |    ✓    |   ✓   |   ✓   | Актуальна кросплатформена версія  |
| **CL WPF**      |    ✓    |   —   |   —   | Історична версія лише для Windows |

Доступність окремих функцій може відрізнятися між платформами. Підтримка конкретної операційної системи не гарантує сумісності з усіма версіями Minecraft.

## Допомога та зворотний зв'язок

Знайшли помилку або маєте пропозицію? Створіть [issue у відкритому репозиторії](https://github.com/WER-CORE/CL-OpenSource/issues) або зверніться до [Discord-спільноти](https://discord.gg/RhyZjACs2U). Для повідомлення про помилку бажано додати версію CL, операційну систему та кроки відтворення.
Хочете допомогти з локалізацією? Перейдіть на [Crowdin](https://uk.crowdin.com/project/clegendary-launcher).

## Подяки та ліцензії

Дякуємо авторам бібліотек, сервісів та інструментів, на яких базується Clegendary Launcher, зокрема командам **Modrinth**, **CurseForge**, розробникам підтримуваних завантажувачів модів, а також авторам використаних UI-компонентів та іконок.

Окрема подяка **[BetaCraft](https://betacraft.uk/)** ([GitHub](https://github.com/betacraftuk)) за збереження історичних версій Minecraft, архів метаданих та інструменти сумісності. Інтеграція з BetaCraft зробила можливою підтримку історичних версій у CL. Clegendary Launcher — незалежний проєкт, не афілійований із BetaCraft.

Відомості про сторонні компоненти та їхні ліцензії дивіться у [вихідному коді](https://github.com/WER-CORE/CL-OpenSource) й супровідних файлах проєкту.

## Правова інформація

Clegendary Launcher не є офіційним продуктом Mojang Studios або Microsoft і не пов'язаний із ними. Minecraft та пов'язані торговельні марки належать їхнім правовласникам.

---

<div align="center">

**Свій до свого по своє. 🇺🇦**

Якщо CL став вам у пригоді, підтримайте проєкт зіркою на [GitHub](https://github.com/WER-CORE/CL-OpenSource).

</div>
