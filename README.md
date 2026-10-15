# Ballu-Air-Master-2-Home-Assistant-Integration

Прошивка на ESP32 для локального управления бризером Ballu Air Master 2 BMAC-300 локально в Home Assistant с помощью интеграции ESPHome. Команды разобраны с оригинального Wi-Fi модуля путем захвата через Logic Analyser, прошивка скомпилена через Claude AI. В бризере завышено напряжение на TX и RX, поэтому стоит запаивать резисторы по схеме ниже, чтобы напряжение держалось в пределах 3.3 Вольта. Все протестировано, работает.

<img width="1000" height="640" alt="wiring" src="https://github.com/user-attachments/assets/05ed5b53-13d7-4154-baa2-0904187707d1" />
