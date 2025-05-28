# Regresinės analizės ir algoritmų tyrimas

Šio projekto tikslas – išanalizuoti ir palyginti įvairių regresijos algoritmų efektyvumą prognozuojant nekilnojamojo turto kainas. Naudojant realius duomenis, buvo įvertinti skirtingų modelių tikslumo rodikliai ir nustatyta, kurie metodai geriausiai tinka šiai užduočiai.

## Projekto aprašymas
Naudoti metodai

* Tiesinė regresija
* Polinominė regresija
* Sprendimų medis
* Atsitiktinių miškų regresija
* Rekursinis neuroninis tinklas

Kiekvienas modelis buvo įvertintas pagal šiuos kriterijus:
* MAE (Vidutinė absoliutinė paklaida)
* MSE (Vidutinė kvadratinė paklaida)
* R² (Determinacijos koeficientas)


## Naudotos technologijos
* Python 3.10
* Google Colab/Jupyter/VSCode – Python notebooks (.ipynb) palaikančios platformos
* Pandas, NumPy – duomenų apdorojimui
* Tensorflow – neuroninių tinklų modelių kūrumui
* Scikit-learn – modelių kūrimui ir vertinimui
* Matplotlib – rezultatų vizualizacijai

## Projekto paleidimas
1. Atsisiųskite [treniravimo duomenis](https://www.kaggle.com/datasets/anthonypino/melbourne-housing-market?resource=download).

2. Susiinstaliuokite reikalingas bibliotekas:
```bash
pip install -r requirements.txt
```

3. Jei naudojate Jupyter:
```bash
jupyter notebook main.ipynb
```

## Pastabos
* Duomenų paruošimas apima trūkstamų reikšmių tvarkymą, kategorinių kintamųjų kodavimą ir skaitinių kintamųjų standartizavimą.
* Modelių hiperparametrų derinimas buvo atliktas siekiant optimizuoti jų veikimą.
