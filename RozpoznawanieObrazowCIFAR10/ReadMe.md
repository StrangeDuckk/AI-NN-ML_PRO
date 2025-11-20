Projekt 1 Rozpoznawanie obrazów CIFAR10
Termin: 24 listopada 2025 18:00
Instrukcje
Zaprojektuj, wytrenuj i przetestuj model konwolucyjnej sieci neuronowej dla zbioru CIFAR-10.
Możesz skorzystać z szablonu `mmajew/PRO1/Projekt_01/template.ipynb`. Dowolna architektura sieci NN.

Punktacja zależy tylko od wartości funkcji straty na zbiorze testowym:
0.00 < val_loss < 0.63, projekt otrzymuje 10 pkt
0.63 < val_loss < 0.70, projekt otrzymuje 9 pkt
0.70 < val_loss < 0.80, projekt otrzymuje 8 pkt
0.80 < val_loss < 0.90, projekt otrzymuje 7 pkt
0.90 < val_loss < 1.30, projekt otrzymuje 6 pkt
1.30 < val_loss , projekt jest niezaliczony.

Aby zaliczyć projekt należy osobiście przedstawić i omówić:
- kod źródłowy (`.ipynb` lub `.py`) omawiając architekturę sieci NN oraz hiperparametry,
- interpretację wyników w plikach graficznych PNG: funkcja straty i precyzja vs epoki, oraz macierz pomyłek.
Przedstawienie kodu wpływa na liczbę punktów.

Po przekroczeniu terminu obrony (24.11) otrzymują Państwo połowę należnych punktów.
---------------------------------------
Przykładowe zagadnienia:
- One-hot encoding co znaczy
- batch size jaka wartość? Jakie są graniczne wartości?
- learning rate
- callbacks jakie zastosowano, jakie parametry mają
- funkcja straty loss jaką zastosowano?
- warstwy użyte w Twojej NN, przykładowo: Input, Conv2D, BatchNormalization, Activation, MaxPooling2D, GlobalAveragePooling2D, Flatten, Dense, Dropout, itd. Tylko takie, które używasz. Mniej używasz, mniej do nauki.
- funkcje aktywacji użyte w Twojej NN
- inne parametry, np. inicjalizatory wag, w Twojej NN jeśli użyto
- na jakiej podstawie wybrał program finalne wagi NN?
- czym różni się val_loss od accuracy?
- jak interpretować macierz pomyłek? Co jest na osi X i Y? Jakie znaczenie ma przekątna macierzy pomyłek? Co znaczą liczby poza przekątną?

Uwaga - można mieć ze sobą notatki lub komentarze w kodzie, które odpowiadają na w/w zagadnienia, ale należy je wcześniej przeczytać i zrozumieć.