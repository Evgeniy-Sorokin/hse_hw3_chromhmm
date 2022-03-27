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

### __"Эпигенетические типы"__

| State | Эпигенетический тип | Встречаемость в гистоновых метках | Краткая характеристика | Полученное изображение |
| :---: | :---: | :---: | :---: | :---: |
| 1 | Insulator | H3K27me3 | RefSeqTes, laminB1lads | ![image](https://user-images.githubusercontent.com/71905847/160287879-7e33edf6-dfba-47d2-89ab-40072f37e0a8.png) |
| 2 | Insulator | Почти не встречается | laminB1lads | ![image](https://user-images.githubusercontent.com/71905847/160288633-1c714918-ccc0-4212-942e-60ddf5c0f6fa.png) |
| 3 | Weak transcribed | Очень слабо в H3K79me2, H3K36me3 | RefSeqGene, RefSeqTes, RefSeqExon | ![image](https://user-images.githubusercontent.com/71905847/160288993-f7cb82a3-5b0c-4e33-9726-0e24b258b1ab.png) |
| 4 | Inactive/poised Promoter | H3K79me2 | RefSeqGene | ![image](https://user-images.githubusercontent.com/71905847/160289289-1c0409a3-213a-4129-8187-f2b3dd9706ae.png)|
| 5 | Transcribed | H3K4me2, H3K27ac, H3K4me1 | RefSeqGene, RefSeqTes, RefSeqTSS2kb, RefSeqExon | ![image](https://user-images.githubusercontent.com/71905847/160289393-29521724-7c57-4daf-9f37-5a2e6fb371f0.png) |
| 6 | Transcribed | H2AFZ, H3K4me2, H3K9ac, H3K27ac, H3K4me1 | RefSeqTes, RefSeqGene, laminB1lads | ![image](https://user-images.githubusercontent.com/71905847/160289958-6b22949a-0111-4a86-8110-29f476cbd6b3.png)|
| 7 | | | | |
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |
