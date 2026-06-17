# Teoria: Miary statystyki opisowej

Statystyka opisowa pozwala na zwięzłe podsumowanie i opisanie zebranych danych za pomocą odpowiednich miar.

## 1. Miary położenia
Wskazują one "środek" lub typową wartość dla danej zbiorowości:

* **Średnia arytmetyczna**: Klasyczna miara przeciętna. Dla szeregu prostego wyraża się wzorem: $\overline{x}=\frac{1}{m}\Sigma_{i=1}^{m}x_{i}$.
* **Mediana**: Wartość środkowa. Jeśli liczba obserwacji jest nieparzysta, jest to wartość dokładnie w środku posortowanego zbioru, a dla parzystej – średnia z dwóch środkowych. Dla szeregu z przedziałami stosuje się wzór: $$M_{e}=x_{0k}+\frac{h_{k}}{n_{k}}(\frac{N}{2}-\sum_{i=1}^{k-1}n_{i})$$.
* **Kwantyl rzędu p**: Wartość, dla której p% elementów próby jest mniejszych bądź równych od niej, a (100-p)% większych bądź równych.
* **Dominanta (moda)**: Wartość występująca w próbie najczęściej. Dla szeregu z przedziałami: $$d=x_{od}+\frac{n_{d}-n_{d-1}}{(n_{d}-n_{d-1})+(n_{d}-n_{d+1})}*h_{d}$$.

## 2. Miary rozproszenia
Określają, jak bardzo dane są zróżnicowane (rozrzucone) wokół średniej:

* **Wariancja** ($s^2$): Dla szeregu prostego obliczana jako: $s^{2}=\frac{1}{n}\Sigma_{i=1}^{n}(x_{i}-\overline{x})^{2}$.
* **Odchylenie standardowe** ($s$): Pierwiastek kwadratowy z wariancji: $s=\sqrt{s^{2}}$.
* **Współczynnik zmienności** ($V$): Względna miara zróżnicowania: $V=\frac{s}{\overline{x}}*100\%$. Im wyższy wynik, tym silniejsza zmienność danych.

## 3. Miary asymetrii
Pozwalają ocenić, czy dane rozkładają się symetrycznie:

* **Moment centralny rzędu 3** ($M_3$): Jeśli $M_3 = 0$, rozkład jest symetryczny; jeśli $M_3 > 0$ to prawostronnie asymetryczny; jeśli $M_3 < 0$ to lewostronnie asymetryczny.
* **Współczynnik asymetrii** ($A_s$): Wyrażany wzorem: $A_{s}=\frac{M_{3}}{s^{3}}$.

## 4. Miary koncentracji
Opisują skupienie wartości wokół średniej:

* **Kurtoza** ($K$): Obliczana ze wzoru: $K=\frac{M_{4}}{s^{4}}$. Wskazuje na możliwe nierównomierne rozdysponowanie wartości cechy.
* **Eksces**: To kurtoza pomniejszona o 3, co ułatwia interpretację (zależy od znaku). Wyróżniamy rozkłady leptokurtyczne ($Ex>0$), mezokurtyczne ($Ex=0$) oraz platokurtyczne ($Ex<0$).