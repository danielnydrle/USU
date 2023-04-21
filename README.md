# Podklady pro předmět Strojové učení

Úlohy jsou připravené ve formě jupyter notebooků jazyka Python 3.x především s využitím knihoven numpy a matplotlib.

## Instalace

Nejjednodušší cesta, jak vše zprovoznit na vlastním počítači s Windows 10 či Linuxem, je:

1. Instalace: [64-bitová 3.9 verze distribuce Miniconda](https://docs.conda.io/en/latest/miniconda.html)
	- Při instalaci nevolte přidání spustitelných skriptů Anacondy do standardních cest. Po instalaci spusťte Anaconda Prompt a zadejte příkaz conda init, aby bylo možné ji používat i z běžného příkazového řádku (cmd.exe). V opačném případě bude pro práci vždy nutné spouštět Anaconda Prompt, která všechny potřebné cesty již obsahuje.
	- Neinstalujte do adresáře obsahujícího v cestě slova s diakritikou.
  - Před instalací odstraňte předchozí verze Pythonu.
2. Vytvoření prostředí pro předmět USU v běžné příkazové řádce: conda create -n usu python=3.9
3. Aktivace vytvořeného prostředí: conda activate usu
4. Instalace modulů ze seznamu závislostí do vytvořeného prostředí:
   - jako conda balíky příkazem `pip install <balik>`,
   - pip install torch
   - pip install notebook   
   - pip install numpy   
   - pip install matplotlib
5. Spuštění jupyter notebooku v příkazové řádce: jupyter notebook (v případě problémů: python -n notebook)

## Podmínky zápočtu

- Pro získání zápočtu je nutné samostatně vypracovat a odevzdat v uvedeném termínu všechny úlohy nebo jejich části, které nejsou označeny jako bonusové.
- Za vypracování bonusových úloh nebo bonusových částí povinných úloh je možné získat plusové body ke zkoušce. Ty mohou významně zlepšit výslednou známku.
- **Neodevzdání úlohy v termínu stejně jako zcela či z podstatné části zkopírovaná úloha má za následek ztrátu nároku na zápočet.

## Jednotlivá cvičení

Soubory odevzdávejte mailem pojmenované ve tvaru Prijmeni_cislo.ipynb, např. Cerva_02.ipynb

### 1. Úvod 
- Seznamení se s prostředím jupyter notebook:
- Rychlý úvod [youtube](https://www.youtube.com/watch?v=HW29067qVWk)
- Seznámení se s knihovnou NumPy:
- Rychlý úvod [numpy.org](https://numpy.org/doc/stable/user/quickstart.html) až do začátku části "Splitting one array into several smaller ones". 
- Rozdíly mezi Numpy a Matlabem [numpy.org](https://numpy.org/doc/stable/user/numpy-for-matlab-users.html)
- Notebook: [USU_01_INTRO_CZ.ipynb](USU_01_INTRO_CZ.ipynb)
- **deadline: 7.3.2023 7:59**
 
### 2. Regrese analyticky
- Notebook: [USU_02_LR_LSE_CZ.ipynb](USU_02_LR_LSE_CZ.ipynb)
- Bonusová část: podúloha na exponenciální regresi
- **deadline: 14.3.2023 7:59**

### 3. Regrese metodou největšího spádu
- Notebook: [USU_03_LR_SGD_CZ.ipynb](USU_03_LR_SGD_CZ.ipynb)
- **deadline: 21.3.2023 7:59**

### 4,5. Klasifikace metodou nejbližšího souseda
- Notebook: [USU_04_KNN_CZ.ipynb](USU_04_KNN_CZ.ipynb)
- Bonusová část: za úlohu lze získat až 2 bonusové body. Hodnotí se efektivita implementace (čím méně cyklů for tím lépe) a zodpovězení závěrečné otázky na složitost jednotlivých metod.
- **deadline: 4.4.2023 7:59**

### 6. Logistická regrese
- Notebook: [USU_06_BLR_CZ.ipynb](USU_06_BLR_CZ.ipynb)
- **deadline: 11.4.2023 7:59**

### 7. Softmax
- Notebook: [USU_07_SOFTMAX_CZ.ipynb](USU_07_SOFTMAX_CZ.ipynb)
- **deadline: 25.4.2023 7:59**

### 8,9. SVM
- Notebook: [USU_08_SVM_CZ.ipynb](USU_08_SVM_CZ.ipynb)
- Bonusová část: za vypracování řešení v maticovém tvaru (tzn. bez použití cyklu for přes jednolitvé vzorky data) lze získat bonusový bod.
- **deadline: 9.5.2023 7:59**

### 10. Neuronová síť typu MLP
- Notebook: [USU_10_NN_CZ.ipynb](USU_10_NN_CZ.ipynb)
- Bonusová část: Pro získání bonusového bodu je potřeba dosáhnout s ReLU aktivační funkci úspěšnosti > 90%. Pro tento účel je nutné odladit hodnotu parametru $\alpha$
- **deadline: 16.5.2023 7:59**

### 11. Bayesovský klasifikátor
- Notebook: [USU_11_BC_CZ.ipynb](USU_11_BC_CZ.ipynb)
- **deadline**

### 12. Metody transformace příznaků
- Notebook: [USU_12_PCA_LDA_CZ.ipynb](USU_12_PCA_LDA_CZ.ipynb)
- Bonusová část: implementace metody LDA
- **deadline**
