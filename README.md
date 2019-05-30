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

# References
* [https://marcocarnini.github.io/software/2016/08/01/installing-r-kernel-for-jupyter.html](https://marcocarnini.github.io/software/2016/08/01/installing-r-kernel-for-jupyter.html)
* [https://jupyter.readthedocs.io/en/latest/install.html](https://jupyter.readthedocs.io/en/latest/install.html)
* [https://medium.com/@kyleake/how-to-install-r-in-jupyter-with-irkernel-in-3-steps-917519326e41](https://medium.com/@kyleake/how-to-install-r-in-jupyter-with-irkernel-in-3-steps-917519326e41)