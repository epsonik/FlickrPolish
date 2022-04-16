# FlickrPolish
This repository includes the Flickr30k and Flickr8k captions translated to Polish language, with usage of [Azure Translator](https://azure.microsoft.com/pl-pl/services/cognitive-services/translator/#overview).
Captions were generated and used for the research purposes, described in paper:

[Generating image captions in Polish – experimental study](https://ieeexplore.ieee.org/document/9538664)

## Few mentions
 - Translations for Flicktr8k and Flicktr30k were created separately, in different dates.
 - Different dates of translation for both datasets, can cause little differences in translations for the pictures that occur both in Flicktr8k and      Flicktr30k.
 
## Flickr8k Dataset
Date of translation:
03.3.2021
- descriptions_flickr8k_translated.csv - file in csv format, that consists all captions from Flickr8k dataset translated to Polish language

File descriptions_flickr8k_translated.csv structure header:
- image_name
- caption

Data delimiter
- |

## Flickr30k Dataset
Date of translation: 14.05.2022
- descriptions_flickr30k_translated.csv - file in csv format, that consists all captions from Flickr30k dataset translated to Polish language

File descriptions_flickr30k_translated.csv structure header:
- image_name
- comment

Data delimiter
- |

## Reference
If you find this repo helpful, please consider citing:
```
@InProceedings{Bartosiewicz2021Generating,
  author    = {Bartosiewicz, Mateusz and Krupińska, Izabela and Bany, Maciej and Konieczna, Anna and Ostrowski, Mateusz and Zalewski, Maciej and Iwanowski, Marcin},
  title     = {Generating image captions in Polish – experimental study},
  booktitle = {2021 14th International Conference on Human System Interaction (HSI)},
  year      = {2021},
  pages     = {1-6},
  doi       = {10.1109/HSI52170.2021.9538664},
}
```

# FlickrPolish
W repozytorium umieszczone zostały podpisy do obrazów ze zbiorów Flickr30k i Flickr8k przetłumaczone na język Polski przy użyciu [Azure Translator](https://azure.microsoft.com/pl-pl/services/cognitive-services/translator/#overview).
Podpisy zostały wygenerowane dla badań opisanych w artykule

[Generating image captions in Polish – experimental study](https://ieeexplore.ieee.org/document/9538664)

## Uwagi
- Oba zbiory zostały przetłumaczone oddzielnie, w różnym czasie.
- W związku z różnymi datami tłumaczenia, zdjęcia wystepujące zarówno w zbiorze Flicktr8k, jak i Flicktr30k mogą mieć drobne różnice w tłumaczeniu.

## Zbiór Flickr8k
Data tłumaczenia:
03.3.2021
- descriptions_flickr8k_translated.csv - plik w formacie csv zawierający wszystkie podpisy dla zbioru Flickr8k przetłumaczone na język Polski

Struktura nagłówka pliku descriptions_flickr8k_translated.csv
- image_name
- caption

Separator danych
- |

## Zbiór Flickr30k
Data tłumaczenia: 14.05.2022
- descriptions_flickr30k_translated.csv - plik w formacie csv zawierający wszystkie podpisy dla zbioru Flickr30k przetłumaczone na język Polski

Struktura nagłówka pliku descriptions_flickr30k_translated.csv
- image_name
- comment

Separator danych
- |

## Odnośniki
Jeżeli wykorzystałeś repozytorium, proszę umieść niniejsze cytowanie
```
@InProceedings{Bartosiewicz2021Generating,
  author    = {Bartosiewicz, Mateusz and Krupińska, Izabela and Bany, Maciej and Konieczna, Anna and Ostrowski, Mateusz and Zalewski, Maciej and Iwanowski, Marcin},
  title     = {Generating image captions in Polish – experimental study},
  booktitle = {2021 14th International Conference on Human System Interaction (HSI)},
  year      = {2021},
  pages     = {1-6},
  doi       = {10.1109/HSI52170.2021.9538664},
}
```



Version:1.0
