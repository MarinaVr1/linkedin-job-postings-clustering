# LinkedIn Job Postings Clustering

Projekat je razvijen u okviru predmeta **Istraživanje podataka 2** na Matematičkom fakultetu Univerziteta u Beogradu.

Cilj projekta je analiza i klasterovanje LinkedIn oglasa za posao kako bi se identifikovale grupe sličnih poslova na osnovu njihovih karakteristika. Korišćenjem metoda pripreme podataka, redukcije dimenzionalnosti i različitih algoritama klasterovanja istraženi su obrasci koji povezuju zanimanja, potrebne veštine, nivo iskustva, benefite i karakteristike kompanija.

Poseban fokus stavljen je na poređenje više algoritama klasterovanja i procenu kvaliteta dobijenih klastera kroz numeričke metrike i interpretaciju rezultata.

## Dataset

Korišćen je javno dostupan skup podataka sa Kaggle platforme:

https://www.kaggle.com/datasets/arshkon/linkedin-job-postings

Skup podataka sadrži informacije o:

- oglasima za posao,
- kompanijama,
- platama,
- industrijama,
- veštinama,
- benefitima,
- veličini kompanija i broju zaposlenih.

## Struktura projekta

```text
linkedin-job-postings-clustering
│
├── data/               # originalni i obrađeni skupovi podataka
│
├── models/             # sačuvane labele i rezultati najboljih modela
│
├── notebooks/
│   ├── preprocessing_data.ipynb
│   ├── data_analysis.ipynb
│   ├── clustering/
│   ├── analysis_no_title.ipynb
│   └── evaluation.ipynb
│
├── results/           # grafici, vizuelizacije i rezultati evaluacije
│
├── README.md
└── .gitignore
```
## Dokumentacija

Detaljan opis korišćenih metoda, eksperimenata i rezultata nalazi se u seminarskom radu:

**[Dokumentacija projekta]()**
## Tehnologije

Projekat je implementiran u Python-u korišćenjem sledećih biblioteka:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

Svi eksperimenti i analize realizovani su kroz Jupyter Notebook okruženje.
## Autor

**Marina Vračarić**

Matematički fakultet  
Univerzitet u Beogradu  
Istraživanje podataka 2
