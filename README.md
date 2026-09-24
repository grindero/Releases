# 📦 Publiczne Wydania (Public Releases) — grindero

Oficjalne, publiczne repozytorium dystrybucji wydań binarnych, paczek instalacyjnych i aplikacji autorstwa **grindero**.

---

## 📱 Dostępne Projekty i Aplikacje

| Aplikacja / Projekt | Platforma | Najnowsza wersja | Bezpośrednie pobranie | Dokumentacja i Changelog |
| :--- | :---: | :---: | :---: | :---: |
| [**MeteoNum**](./MeteoNum) | Android (APK) | **v1.0.1** | [📲 Pobierz APK (v1.0.1)](./MeteoNum/MeteoNum-v1.0.1-release.apk)<br/>[⚡ Zawsze najnowsza wersja](./MeteoNum/MeteoNum-latest.apk) | [📖 Zobacz opis i changelog](./MeteoNum) |

---

## 🏗️ Struktura Repozytorium

Repozytorium jest zorganizowane modułowo z myślą o publikacji wielu niezależnych aplikacji i narzędzi:
* Każda aplikacja posiada dedykowany podkatalog (np. `MeteoNum/`), zawierający:
  * Pliki instalacyjne danej wersji (`*-vX.Y.Z-release.apk`, `*-latest.apk` itp.).
  * Własny plik `README.md` ze szczegółowym opisem, historią zmian (changelog), zrzutami ekranu i sumami SHA-256.
* Główny spis wydań w tym pliku jest automatycznie aktualizowany przez procesy CI/CD poszczególnych projektów po publikacji nowej wersji.

---

## 🔒 Bezpieczeństwo i weryfikacja

Wszystkie paczki publikowane w tym repozytorium są budowane i podpisywane w bezpiecznym środowisku CI/CD (GitHub Actions) oraz weryfikowane sumami kontrolnymi SHA-256.
Szczegółowe informacje o każdym wydaniu oraz historia wersji znajdują się w podkatalogu danej aplikacji lub w zakładce [**Releases**](https://github.com/grindero/Releases/releases).
