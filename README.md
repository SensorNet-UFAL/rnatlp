# Natural Language Processing for Systematic Reviews

This is a [Jupyter](https://jupyter.readthedocs.io/en/latest/running.html#running) R notebook set of scripts to extract meaningful information when performing a Systematic Literature Review.

Pull requests are welcome!

## To run in your computer
```
jupyter notebook
```

## To install jupyter in ubuntu, follow these steps in this specific order:
* Configure a virtualenv (preferred version is pip3)
	```
	virtualenv --python=/usr/bin/python3 rkernels
	source rkernels/bin/activate
	```
* Install jupyter using pip 
	```
	pip install --upgrade pip
	pip install jupyter
	```
* Initialize R in terminal
	```
	install.packages("devtools") 
	install.packages("pbdZMQ")
	install.packages("epr")
	devtools::install_github('IRkernel/IRkernel')
	IRkernel::installspec()
	```
### Additional Packages
 - R (Some packages requires )
   -  install.packages(c("readxl","rvest", "reticulate", "tidyverse", "ggplot2", "officer"))
 - Python
   - pip install spacy

# References
* [Officer](https://davidgohel.github.io/officer/articles/offcran/word.html)
* [Spacy](http://spacy.io/)
* [https://marcocarnini.github.io/software/2016/08/01/installing-r-kernel-for-jupyter.html](https://marcocarnini.github.io/software/2016/08/01/installing-r-kernel-for-jupyter.html)
* [https://jupyter.readthedocs.io/en/latest/install.html](https://jupyter.readthedocs.io/en/latest/install.html)
* [https://medium.com/@kyleake/how-to-install-r-in-jupyter-with-irkernel-in-3-steps-917519326e41](https://medium.com/@kyleake/how-to-install-r-in-jupyter-with-irkernel-in-3-steps-917519326e41)

# Credits
* [SensorNet-UFAL](https://sites.google.com/site/sensornetufal/home)