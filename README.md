# Code samples for "Neural Networks and Deep Learning"

This repository contains code samples for Michael Nielsen's book on
["Neural Networks and Deep Learning"](http://neuralnetworksanddeeplearning.com).

Updates have been made for more recent versions of python and its packages.

To setup environment:

```sh
conda env create -f environment.yml
conda activate nndl
```

Consult the book for individual experiments and their purposes.

To run all experiments:

```sh
cd src
python
```

```python
import conv
conv.run_experiments()
```
