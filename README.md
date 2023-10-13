# PRPM_notebooks
Jupyter Notebooky v jazyce Python3 pro předmět Přetváření a porušování materiálů, 132PRPM




## Obsah:

```
  PRPM_notebooks
  |
  |-- viscoelasticity - funkce poddajnosti a relaxační funkce pro jednoduchá reologická zapojení, 
  |         výpočet dotvarování a smršťování podle norem.
  |
  |-- plasticity - tbd
```



## Viskoelasticita

### Funkce poddajnosti a dotvarování
* Maxwell_unit_compliance_interact.ipynb = funkce poddajnosti Mawellova článku, vývoj deformace pružiny a tlumiče

* Kelvin_unit_compliance_interact.ipynb = funkce poddajnosti Kelvinova článku, přerozdělení napětí mezi pružinou a tlumičem

* Kelvin_unit_compliance_plot.ipynb = vykreslední funkce poddajnosti Kelvinova článku

* Kelvin_chain_compliance_interact.ipynb = funkce poddajnosti Kelvinova řetězce se třemi jednotkami a pružinou, zobrazení experimentálních dat


### Relaxační funkce

* Maxwell_unit_relaxation_interact.ipynb = relaxační funkce Mawellova článku, přerozdělení deformace mezi pružinou a tlumičem


* Poynting-Thomson_relaxation_interact.ipynb = relaxační funkce modelu Poynting-Thomson, přerozdělení deformace mezi pružinou a Kelvinovým článkem


### Dotvarování podle norem

* creep_shrinkage_fib_MC2010_interact.ipynb = funkce poddajnosti a relaxační funkce podle fib MC 2010 (fib Bulletin 65, 2012), vývoj celkové deformace včetně nesilové složky, přesnost predikce dle fib pro dotvarování a smršťování


## Spuštění notebooku

Pro zobrazení, spuštění a editaci notebooku mohou být použity různé programy, některé z nich vyžadují instalaci, jiné lze spustit online. Volba vývojového prostředí má vliv na nastavení vnitřní proměnné na začátku scriptu "```online = True```" nebo "```online = False```". Důvodem je potřeba načtení knihovny ipywidgets.

Doporučujeme:

* [JupyterLab-Desktop](https://github.com/jupyterlab/jupyterlab-desktop) je příjemné vývojové prostředí, které se nezobrazuje v prohlížeči a vyžaduje instalaci (```online = False```)

* [Google Colab](https://colab.research.google.com) vyžaduje účet u Google (```online = False```)


* [Jupyter Notebook nebo Lab](https://jupyter.org) vyžaduje instalaci, zobrazuje se v prohlížeči, což nemusí každému vyhovovat (```online = False```)


* [Zkušební prostředí Jupyterlite](https://jupyterlite.github.io/demo/lab/index.html) nevyžaduje registraci ani instalaci (```online = True```)


## Authors
[Petr Havlásek](mailto:petr.havlasek@cvut.cz), [ORCID: 0000-0002-7128-3664](https://orcid.org/0000-0002-7128-3664)<br/>


