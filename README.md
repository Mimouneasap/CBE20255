# Introduction to Chemical Engineering Analysis

_Introduction to Chemical Engineering Analysis_ demonstrates the use of mass and energy balances for the analysis of chemical processes and products. The notebooks in the repository show how to prepare and analyze conceptual flowsheets for chemical processes, perform generation-consumption analysis, and perform basic engineering calculations for stoichiometry, reactor performance, separations, and energy analysis.

The notebooks incorporate executable Python 3 code to demonstrate basic chemical engineering calculations. The notebooks can be opened directly in Google Colaboratory where they can be run, edited, shared, and saved to your Google Drive. No other software is needed when using Google Colaboratory. Alternatively, the render in nbviewer link allows notebooks to be downloaded and executed in a Python development distribution installed on your own computer. These notebooks were developed and tested using the distribution from [Anaconda.com](https://www.anaconda.com/download/).

Most notebooks are 3-5 pages in length covering a single topic. Notebooks marked as examples are short problem statements with solutions.

** Note on the use of Python.** The Python used in these notebooks is deliberately limited to a core set of language features.  These notebooks use scalar variables and lists of scalar variables to represent data. Also used are arithmetic, math, print, and plotting functions from the `matplotlib.pyplot` library. Functions created with `def` and `lambda` are used when root-finding calculations are required. List comprehesions are used on occasion when the result is more readable code. The `Sympy` library for symbolic math is used extensively for writing mass balances. Other libraries included `numpy`, `math`, and the root-finding functions from `scipy.optimize`. Notebooks with more advanced use of Python, such as dictionaries, are marked.

The materials in this repository are available at [http://github.com/jckantor/CBE20255](http://github.com/jckantor/CBE20255) for noncommercial use under terms of the [Creative Commons Attribution Noncommericial ShareAlike License](http://creativecommons.org/licenses/by-nc-sa/4.0/). You are invited to fork this repository, and to use, adapt, remix these material for non-commericial purposes. The license terms require you to give attribution and share your work under the same terms. Pull requests for corrections and additions to these materials are most welcome.


| 0. Getting Started | |
| :--- | ---: |
| Getting Started with Jupyter Notebooks and Python | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Getting_Started_with_Jupyter_Notebooks_and_Python.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Getting_Started_with_Jupyter_Notebooks_and_Python.ipynb) |
| Example: Solving Linear Equations with Sympy | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Solving_Linear_Equations_with_Sympy.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Solving_Linear_Equations_with_Sympy.ipynb)|
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| |

| 1. Units, Quantities, and Engineering Calculations | |
| :--- | ---: |
| Getting Started with Units and Engineering Calculations | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Units_and_Engineering_Calculations.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Units_and_Engineering_Calculations.ipynb) |
| *Example:* Units and Conversions for Home Heating | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Units_and_Conversions_for_Home_Heating.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Units_and_Conversions_for_Home_Heating.ipynb) |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| |

| 2. Stoichiometry | |
| :--- | ---: |
| Balancing Reactions | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Balancing%20Reactions.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Balancing%20Reactions.ipynb) |
| Generation-Consumption Analysis for Ammonia Production | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Generation_Consumption_Analysis_for_Ammonia_Production.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Generation_Consumption_Analysis_for_Ammonia_Production.ipynb) |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| |

| 3. Process Flows and Balances | |
| :--- | ---: |
| Example: Global CO<sub>2</sub> Budget | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Global%20CO2%20Budget.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Global%20CO2%20Budget.ipynb) |
| Example: CO2 Production by Automobiles | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/CO2%20Production%20by%20Automobiles.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/CO2%20Production%20by%20Automobiles.ipynb) |
| General Mass Balance on a Single Tank | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/General%20Mass%20Balance%20on%20a%20Single%20Tank.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/General%20Mass%20Balance%20on%20a%20Single%20Tank.ipynb) |
| Separating Milk | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Separating_Milk.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Separating_Milk.ipynb) |
| Adipic Acid Flowsheet | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Adipic%20Acid%20Flowsheet.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Adipic%20Acid%20Flowsheet.ipynb) |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| |

| 4. Material Balances | |
| :--- | ---: |
| Lean NOx Trap | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Lean%20NOx%20Trap.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Lean%20NOx%20Trap.ipynb) |
| Ethylene Oxide Flowsheet | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Ethylene%20Oxide%20Flowsheet.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Ethylene%20Oxide%20Flowsheet.ipynb) |
| General Mass Balance on a Single Tank | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/General%20Mass%20Balance%20on%20a%20Single%20Tank.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/General%20Mass%20Balance%20on%20a%20Single%20Tank.ipynb) |
| Unsteady-State Material Balances | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Unsteady-State%20Material%20Balances.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Unsteady-State%20Material%20Balances.ipynb)
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| |

| 5. Reactors | |
| :--- | ---: |
| Dehydrogentation of Propane | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Dehydrogenation_of_Propane.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Dehydrogenation_of_Propane.ipynb) |
| Steam Reforming of Methane | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Steam%20Reforming%20of%20Methane.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Steam%20Reforming%20of%20Methane.ipynb) |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| |

| 6. Vapors and Gases | |
| :--- | ---: |
| PVT Calculations for Non-Ideal Gases | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/PVT_Calculations_for_Non-Ideal_Gases.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/PVT_Calculations_for_Non-Ideal_Gases.ipynb) |
| Hydrogen Storage for a Fuel Cell Vehicle | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Hydrogen_Storage_for_a_Fuel_Cell_Vehicle.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Hydrogen_Storage_for_a_Fuel_Cell_Vehicle.ipynb) |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| |

| 7. Vapor/Liquid Equilibrium | |
| :--- | ---: |
| Gases with One Condensable Component | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Gases_with_One_Condensable_Component.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Gases_with_One_Condensable_Component.ipynb) |
| Vapor-Liquid Equilibrium for Pure Components | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Vapor-Liquid_Equilibrium_for_Pure_Components.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Vapor-Liquid_Equilibrium_for_Pure_Components.ipynb) |
| Operating Limits for a Methanol Lighter | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Operating_Limits_for_a_Methanol_Lighter.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Operating_Limits_for_a_Methanol_Lighter.ipynb) |
| Raoult's Law for Ideal Mixtures | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Raoult's_Law_for_Ideal_Mixtures.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Raoult's_Law_for_Ideal_Mixtures.ipynb) |
| Txy and xy Diagrams for Binary Mixtures | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Txy_and_xy_Diagrams_for_Binary_Mixtures.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Txy_and_xy_Diagrams_for_Binary_Mixtures.ipynb) |
| Bubble and Dew Point Calculations for Binary Mixtures | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Bubble%20and%20Dew%20Point%20Calculations%20for%20Binary%20Mixtures.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Bubble%20and%20Dew%20Point%20Calculations%20for%20Binary%20Mixtures.ipynb) |
| Bubble and Dew Point Calculations for Multicomponent Mixtures | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Bubble%20and%20Dew%20Point%20Calculations%20for%20Multicomponent%20Mixtures.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Bubble%20and%20Dew%20Point%20Calculations%20for%20Multicomponent%20Mixtures.ipynb) |
| Isothermal Flash and the Rachford-Rice Equation | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Isothermal_Flash_and_the_Rachford-Rice_Equation.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Isothermal_Flash_and_the_Rachford-Rice_Equation.ipynb) |
| Binary Distillation with McCabe-Thiele | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Binary%20Distillation%20with%20McCabe-Thiele.ipynb) [![nbviewer](images/badges//nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Binary%20Distillation%20with%20McCabe-Thiele.ipynb) |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| |

| 8. Energy Balances | |
| :--- | ---: |
| Humidity and Psychrometrics | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Humidity%20and%20Psychrometrics.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Humidity%20and%20Psychrometrics.ipynb) |
| Adiabatic Flame Temperature | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Adiabatic%20Flame%20Temperature.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Adiabatic%20Flame%20Temperature.ipynb) |
| Torpedo Propulsion | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Torpedo%20Propulsion.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Torpedo%20Propulsion.ipynb) |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| |

| Projects: Product Design and Analysis | |
| :--- | ---: |
| Diesel Engine Emissions Control | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Diesel%20Engine%20Emissions%20Control.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Diesel%20Engine%20Emissions%20Control.ipynb) |
| Pyrotechnic Design for Airbags | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Pyrotechnic%20Design%20for%20Airbags.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Pyrotechnic%20Design%20for%20Airbags.ipynb) |
| Flameless Cooking | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Flameless%20Cooking.ipynb)  [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Flameless%20Cooking.ipynb) |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| |

| Projects: Process Systems Analysis | |
| :--- | ---: |
| West Virginia Chemical Spill | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/West%20Virginia%20Chemical%20Spill.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/West%20Virginia%20Chemical%20Spill.ipynb) |
| Ajka Alumina Plant Spill | [![Open In Colab](images/badges/colab-badge.svg)](https://colab.research.google.com/github/jckantor/CBE20255/blob/master/notebooks/Ajka%20Alumina%20Plant%20Spill.ipynb) [![nbviewer](images/badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/jckantor/CBE20255/blob/master/notebooks/Ajka%20Alumina%20Plant%20Spill.ipynb) |
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| |

