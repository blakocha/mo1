# Wykorzystanie metod optymalizacyjnych do modelowania empirycznych krzywych ROC dla bankowych modeli scoringowych za pomocą wybranych funkcji teoretycznych

Idea

Nazwa krzywej ROC (receiver operating curve) pochodzi z dziedziny rozpoznawania sygnałów. Krzywa jest używana, żeby oceniać jakość klasyfikatorów binarnych w wielu dziedzinach (oprócz przetwarzanie sygnałów, medycyna, credit scoring, inne obszary wykorzystania uczenia maszynowego) 

Istnieje kilka (albo i kilkanaście) formuł na rysowanie teoretycznej krzywej ROC. Przykłady to krzywe określane angielskimi terminami normal, binormal, bifractal, bibeta, bigamma, etc.  Konieczność modelowania w kontekście biostatystycznym najczęściej wynika z braku dużej liczby obserwacji i potrzeby wyznaczania np. przedziałów ufności dla miar opartych na ROC (np. pole powierzchni pod krzywą ROC: AUROC, lub częściej w przypadku scoringu współczynnik Giniego: Gini=2⋅AUROC-1). W kontekście kredytów bankowych (credit scoring) konieczność modelowania wynika z innych powodów – np. chęć symulowania krzywej ROC dla modelu, który jeszcze nie istnieje. 

Zadaniem projektu jest wykorzystanie metod optymalizacji dostępnych w bibliotekach Julia, Python lub R do dopasowania wybranych modelowych krzywych  do empirycznych danych ROC. 
