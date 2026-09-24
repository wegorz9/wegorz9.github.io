METRONOM STUDIO WAV v12

1. Skopiuj własne pliki Samantha WAV do katalogu audio/.
2. Uruchom z katalogu projektu: python3 -m http.server 8080
3. Na iPhonie otwórz adres Maca w Safari.

Zmiany v12:
- naprawiono Tap Tempo; oblicza BPM ze średniej maksymalnie 6 ostatnich odstępów, a przerwa ponad 2,5 s rozpoczyna nową serię,
- usunięto przyciski TEST i komunikat diagnostyczny WAV,
- dołączono pełny manifest, Service Worker, wake.mp4 i ikony,
- katalog audio pozostawiono do podmiany.
