# 🌿 Sterownik szklarni – system automatyki oparty na mikrokontrolerze

## 📌 Opis projektu
Sterownik szklarni to projekt systemu automatyki mikroklimatu, który umożliwia pomiar i kontrolę warunków w szklarni. Urządzenie mierzy temperaturę, wilgotność powietrza oraz wilgotność gleby, a następnie steruje wentylacją i nawadnianiem za pomocą przekaźników. Informacje są prezentowane na wyświetlaczu LCD.

Projekt został zaprojektowany z myślą o zastosowaniach hobbystycznych i półprofesjonalnych w ogrodnictwie.

## 🧠 Funkcje
- Pomiar temperatury i wilgotności powietrza (czujnik DHT22)
- Pomiar wilgotności gleby (czujniki analogowe)
- Sterowanie wentylacją (przekaźnik)
- Sterowanie nawadnianiem (przekaźnik)
- Wyświetlacz LCD (I2C) do prezentacji danych
- 4 wyjścia przekaźnikowe do sterowania urządzeniami
- Możliwość rozbudowy o dodatkowe czujniki i funkcje
- Zegar RTC (I2C)

## 🛠️ Technologie
- **Mikrokontroler**: Arduino
- **Czujniki**: DHT22, pojemnościowe czujniki wilgotności gleby
- **Komunikacja**: UART, I2C
- **Wyświetlacz**: LCD 16x2 z konwerterem I2C
- **Sterowanie**: Moduły przekaźnikowe 5V
- **Projekt PCB**: KiCad
- **Programowanie**: C/C++ (Arduino IDE)




