# hse_hw3_chromhmm

__Ссылка на google-collab:__

https://colab.research.google.com/drive/1Qb4_MSa3iocx9ktCTXT-aLDosvK8lvtM#scrollTo=7yuCmmw-gsFC

## Часть №1

Ввиду того, что выбранная в домашнем задании клеточная линия OCI-LY3 не содержится в представленном списке, то была произведена замена на клеточную линию HUVEC.

![image](https://user-images.githubusercontent.com/71905847/160262657-7530c261-5b86-45d7-b9c2-889178b686b8.png)

### __"Результат работы ChromHMM"__

![image](https://user-images.githubusercontent.com/71905847/160262709-d4e6f130-1302-4474-9daa-e7cbd0a2512f.png)

![image](https://user-images.githubusercontent.com/71905847/160262715-467a11f0-337e-44c5-a227-cf09e1233f9d.png)

![image](https://user-images.githubusercontent.com/71905847/160262723-9dd14d3a-9689-4416-a21d-374722abf85f.png)

![image](https://user-images.githubusercontent.com/71905847/160262728-a15d8ffe-d32e-4fed-a7f9-226b120104ea.png)

![image](https://user-images.githubusercontent.com/71905847/160262735-0ceb5c78-a237-40ce-924a-905704cc52da.png)

### __"Список 10-ти гистоновых меток и соответсвующих файлов, для которых был сделан анализ"__
| Гистоновая метка: | bam-файл | 
| :---: | :---: |
| H2AFZ | H2azAlnRep2.bam |
| H3K27ac | H3k27acStdAlnRep2.bam |
| H3K27me3 | H3k27me3StdAlnRep2.bam |
| H3K36me3 | H3k36me3StdAlnRep2.bam |
| H3K4me1 | H3k4me1StdAlnRep2.bam |
| H3K4me2 | H3k4me2StdAlnRep2.bam |
| H3K4me3 | H3k4me3StdAlnRep2.bam |
| H3K79me2 | H3k79me2AlnRep2.bam |
| H3K9ac | HuvecH3k9acStdAlnRep2.bam |
| H3K9me1 | H3k9me1StdAlnRep2.bam |


### __"Эпигенетические типы"__

| State: | Эпигенетический тип: | Встречаемость в гистоновых метках: | Краткая характеристика (ассоциировано с): | Полученное изображение (пример выделенного участка): |
| :---: | :---: | :---: | :---: | :---: |
| 1 | Insulator | H3K27me3 | RefSeqTes, laminB1lads | ![image](https://user-images.githubusercontent.com/71905847/160287879-7e33edf6-dfba-47d2-89ab-40072f37e0a8.png) |
| 2 | Insulator | Почти не встречается | laminB1lads | ![image](https://user-images.githubusercontent.com/71905847/160288633-1c714918-ccc0-4212-942e-60ddf5c0f6fa.png) |
| 3 | Weak transcribed | Очень слабо в H3K79me2, H3K36me3 | RefSeqGene, RefSeqTes, RefSeqExon | ![image](https://user-images.githubusercontent.com/71905847/160288993-f7cb82a3-5b0c-4e33-9726-0e24b258b1ab.png) |
| 4 | Inactive/poised Promoter | Сильный сигнао в H3K79me2 | RefSeqGene | ![image](https://user-images.githubusercontent.com/71905847/160289289-1c0409a3-213a-4129-8187-f2b3dd9706ae.png)|
| 5 | Transcribed | Сильные сигналы в  H3K4me2, H3K27ac, H3K4me1 | RefSeqGene, RefSeqTes, RefSeqTSS2kb, RefSeqExon | ![image](https://user-images.githubusercontent.com/71905847/160289393-29521724-7c57-4daf-9f37-5a2e6fb371f0.png) |
| 6 | Transcribed |  Сильные сигналы в H2AFZ, H3K4me2, H3K9ac, H3K27ac, H3K4me1 | RefSeqTes, RefSeqGene, laminB1lads | ![image](https://user-images.githubusercontent.com/71905847/160289958-6b22949a-0111-4a86-8110-29f476cbd6b3.png)|
| 7 | Active Promoter | Относительно сильные сигналы в H2AFZ, H3K4me1 | RefSeqTes, laminB1lads, RefSeqGene | ![image](https://user-images.githubusercontent.com/71905847/160290044-a85cd54f-b926-4917-8045-e9a9fa5b6390.png) |
| 8 | Strong enhancer | Очень слабо в H2AFZ | laminB1lads | ![image](https://user-images.githubusercontent.com/71905847/160290189-b90a5764-b97a-43ee-8145-e77125a3ea1d.png) |
| 9 | Weak/poised enhancer | Сильные сигналы в H3K4me2, H2AFZ, H3K4me3, H3K4me1, H3K27me3 | CpGIsland, RefSeqExon, RefSeqTes, RefSeqTSS, RefSeqTSS2kb, laminB1lads | ![image](https://user-images.githubusercontent.com/71905847/160290331-2fa38ac9-69e2-440c-a766-7e3cb73b86c7.png) |
| 10 | Inactive/poised Promoter | Сильные сигналы практически во всех, кроме H3K27me3, H3K9me1 и H3K36me3 | Все, кроме laminB1lads (очень слабо) | ![image](https://user-images.githubusercontent.com/71905847/160290544-ac26b257-0cf7-484a-bdff-a943775d670f.png) |

Заметим однак, что при увеличении "разрешения" мы можем увидеть больше участков с выделенными эпигенетическими типами.

![image](https://user-images.githubusercontent.com/71905847/160290975-ff356516-9cc7-4195-91b0-0917708fe832.png)

