### sympy
---
https://github.com/sympy/sympy

```py
from sympy import Symbol, cos
x = Symbol('x')
e = 1/cos(x)
print e.series(x, 0, 10)

@artcle{10.7717/peerj-cs.103,
  title = {SymPy: symbolic computing in Python},
  author = {Meurer, Aaron and Smith, Christopher P. and Paprocki, Mateusz and \v{C}ert\'{i}k, Ond\v{r}ej and ...},
  year = 2017,
  month = jan,
  keywords = {Python, Computer algebra system, Symbolics},
  abstract = {
    SymPy is an open source computer algebra system written in pure Python. It is built with...
  },
  volume = 3,
  pages = {e103},
  journal = {PeerJ Computer Science},
  issn = {2376-5992},
  url = {https://doi.org/10.7717/peerj-cs.103},
  doi = {10.7717/peerj-cs.103}}
```

```sh
cd doc
make html

bin/isympy
isympy
python setup.py install
sudo python setup.py install
./setup.py test
conda install -c conda-forge antlr=4.7
./setup.py antlr
./setup.py clean
git clean -Xdf
git clean -df
git reset --hard
git shortlog -ns
git shortlog -ns --since="1 year"
```

```
```


