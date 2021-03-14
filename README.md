# pyprobml

<img src="https://img.shields.io/github/stars/probml/pyprobml?style=social">

Python 3 code for my new book series [Probabilistic Machine Learning](https://probml.github.io/pml-book/).
This is work in progress, so expect rough edges.

## Jupyter notebooks

For each chapter there are one or more accompanying Jupyter notebooks that cover some of the material in more detail.
When you open a notebook, there will be a button at the top that says 'Open in colab'. If you click on this, it will start a virtual machine (VM) instance on Google Cloud Platform (GCP), running [Colab](https://colab.research.google.com/notebooks/intro.ipynb). This has most of the libraries you will need (e.g., scikit-learn,  JAX) pre-installed, and gives you access to a free GPU. See [this tutorial](https://colab.research.google.com/github/probml/pyprobml/blob/master/book1/intro/colab_intro.ipynb) for details on how to use Colab.

###  Book 1 (PML: An Introduction)

See [this link](https://github.com/probml/pyprobml/blob/master/book1) for a list of notebooks.

### Book 2 (PML: Advanced topics)

See [this link](https://github.com/probml/pyprobml/blob/master/book2) for a list of notebooks.


## Running scripts to make individual figures

Many of the figures in the book are generated by various  [scripts](scripts). 
To run these, first clone this gihub repo. (For some tutorials on how to use github, see [github guides](https://guides.github.com/).)
Then, to manually execute an individual script from the command line,
follow this example:
```
export PYPROBML=/Users/kpmurphy/github/pyprobml // set this to the directory where you downloaded this repo
cd $PYPROBML
python3 scripts/softmax_plot.py // writes to /Users/kpmurphy/github/pyprobml/figures/softmax_temp.pdf
```
The notebook for each chapter uses these scripts to recreate all the figures for that chapter.

## Viewing the scripts 

To browse the code using VScode instead of the gihub file viewer, you can just replace 
https://github.com/probml/pyprobml/tree/master/scripts
with 
https://github1s.com/probml/pyprobml/tree/master/scripts (see [this tweet](https://twitter.com/hediet_dev/status/1359093978570907648?s=21)).
The output should look like this:

![](https://github.com/probml/pyprobml/blob/master/images/github-vscode-browser.png)


<h2><a id="endorsements"></a>Acknowledgements</h2>

I would like to thank the following people for contributing to the code (alphabetical order):
 Andrew Carr, Aurelien Geron, Gerardo Durán Martín, Osvaldo Martin, Ashish Papanai, Duane Rich, Mahmoud Soliman, Theodore Vasiloudis, Oscar Wahltinez.




 





