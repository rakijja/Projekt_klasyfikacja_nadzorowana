# W tym projekcie wykonano przewidywanie pozostania lub odejścia pracownika z pracy
Dane znajdują się w trzech różnych zbiorach powiązanych między soba kolumną EmployeeNumber.
Przygotowanie danych oparto na:
1. złączeniu zbiorów df_1, df_2 oraz target,
2. usunięciu niepotrzebnych kolumn,
3. odfiltrowaniu danych odstających poprzez usunięcie wierszy zawierających anomalie,
4. wykonanie One Hot Encodnigu na zbiorze oraz usunięcie kolumn zawierających zduplikowane informacje

Do wykonania klasyfikacji wykorzystano modele:
1. Decision Tree,
2. Random Forest,
3. Bagging
4. AdaBoost
