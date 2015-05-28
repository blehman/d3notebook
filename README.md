# d3notebook
IPython continues to be my favorite environment to massage data, explore ideas, and visualize stories. The R library known as ggplot is my standard tool for exploratory visualizations, but I do use (D3)[http://d3js.org/] for web based visualizations and more advanced presentations. 

# How to set up d3 in iPython
$ touch d3_example/__init__.py  
Download [d3.min.js](http://d3js.org/)  
Place it in the folder d3_example dir  
ipynb.py into the d3_example/d3 path
- ipynb.py = make sure the d3 javascript library is available inside the
  iptyhon notebook  

- visualize.py = python code that inserts the javascript d3 code into the
  notebook.

- circle.tpl = tmplated version of the javascript that uses jinja to
  replace the values.

- place `import ipynb` inside the __init__.py folder so we automatically
  get access to the d3 library when we import d3_example.

- cd d3_notebook_example

- make sure to `source env.sh` from the directory where IPython is
  running.

