+++
author = "Maciej Nasinski"
title = "Mercator w drodze na ziemię?"
date = "2022-01-02"
description = ""
tags = [
    "analiza techniczna"
]
categories = [
    "analizy rynkowe"
]
series = ["Themes Guide"]
aliases = ["stooq_log_scale"]
+++

> Od kilku lat na rynku analitycznym zrobiło sie głośno o wizualizacjach ktore wprowadzaja w błąd. 
> Powstały nawet konkursy na najgorsze wizualizacje roku.
> W tym wpisie chce wam zademonstrować wykres z serwisu stooq zawarty w artykule o tytule ["Mercator w drodze na ziemię"](https://stooq.pl/mol/?id=23558&search=mercator).
> W mojej ocenie mamy tu do czynienia z nieodpowiedzialnym przekazywaniem informacji innym uczestnikom rynku inwestycyjnego. Zgodnie z [dobrą praktyka użycie](https://en.wikipedia.org/wiki/Misleading_graph) skali logarytmicznej powinno być jasno zakomunikowane na wykresie. Na wykresie zawartym w tymże artykule, relatywnie jeszcze bardzo daleka droga do wspomnanej "ziemi". Jest to spowodowane zastosowaniem właśnie skali logartymicznej na osi y, która nie została właściwie oznaczona. Wspomniany wykres to notowania społki Mercator z ostatnich 2 lat.
> Zaprezentowane niżej wykresy są identyczne poza skalą na osi y, liniowa vs logarytmiczna. 
> Szczególnie zwrócie uwagę na odstępy między wartosciami na osi y, oraz nachylenie linii trendu.

> Wykres na skali liniowej:

![skala liniowa](/img/stooq_log2.png)

> Wykres na skali logarytmicznej:

![skala logarytmiczna](/img/stooq_log.png)

> Łatwo zauważyć jak bardzo różnią się od siebie te 2 wizualizacje. Warto wspomniec ze skala logarytmiczna jest używana na szeregach czasowych w których wielokrotnie wystąpił eksponencjalny trend, np. kurs Bitcoin-a. Dzieki temu można dostrzec jakąkolwiek zmienność z lat poprzednich. Najważniejsze aby użycie skali logarytmicznej zawsze było właściwie komunikowane.
> Polecam przemyśleć tą kwestie i w przyszłości zwrócić na nią uwagę.