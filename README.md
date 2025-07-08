# 🏠 Smart Home Simulation (CODESYS + HOME IO)

Projekt przedstawia symulację inteligentnego domu zrealizowaną w środowisku **CODESYS 3.5.16** z wykorzystaniem **HOME IO**. Projekt umożliwia sterowanie m.in. bramą garażową, oświetleniem, wizualizacją pogodową oraz monitorowaniem zużycia energii.

---

## 🔧 Zastosowane funkcje

- ✅ Sterowanie bramą garażową (z wizualizacją)
- 🔐 Logowanie użytkowników
- 🌡️ Regulator PID temperatury w salonie i innych pomieszczeniach
- 📊 Monitoring zużycia energii (program i wizualizacja)
- 📅 Harmonogram pracy urządzeń (czasowy)
- 🌤️ Panel prognozy pogody (ikony + wizualizacja)
- 📅 Pobieranie aktualnej daty i godziny
- 🌐 Wizualizacja webowa (przez przeglądarkę)

---

## 💻 Wymagania

- CODESYS v3.5.16
- Dodatek: Connect IO
- Symulacja: HOME IO

---

## 📁 Struktura projektu

Zawiera:
- Folder `Application` z programem głównym
- Konfigurację zadań (Task Configuration)
- Panel logowania, panel sterowania, harmonogram, PID
- Komunikacja przez Modbus TCP
