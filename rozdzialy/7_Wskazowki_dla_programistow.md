# Wskazówki dla programistów

## Overflow-y

Z poziomu klawiatury powinny być dostępne wszystkie elementy. W sytuacji użycia **overflow** (CSS) i pojawienia się suwaka należy pamiętać o możliwości obsługi takiego pola z poziomu klawiatury. 
Użycie **tabindex="0"** dla całej zawartości (np. długiego regulaminu) może spowodować, że czytnik ekranu się zawiesi. Lepszym rozwiązaniem jest zastosowanie **tabindex="0"** na elemencie tekstu np. tytule regulaminu.

## Outline

Użycie w CSS-ach zapisu **outline:none** dla focusa jest [poważnym problemem związanym z dostępnością - artykuł w języku angielskim](http://www.outlinenone.com/). Powoduje to zniknięcie fokusa i zdezorientowanie użytkownika korzystającego wyłącznie z klawiatury.

## [Wróć do spisu treści](../README.md)
