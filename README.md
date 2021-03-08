# MiniTorch Module 4

<img src="https://minitorch.github.io/_images/match.png" width="100px">

MiniTorch is a teaching library for machine learning engineers who wish to learn about the internal concepts underlying deep learning systems. Specifically, it is a pure Python re-implementation of the Torch API designed to be simple, easy-to-read, tested, and incremental. The final library can run Torch code with minimal changes (at some efficiency cost). The project was developed for the course Machine Learning Engineering at Cornell Tech.

The project is organized into 5 modules. Each module is build upon the precedents.
* [Module-0](https://github.com/Mountagha/Module-0)
* [Module-1](https://github.com/Mountagha/Module-1)
* [Module-2](https://github.com/Mountagha/Module-2)
* [Module-3](https://github.com/Mountagha/Module-3)
* [Module-4](https://github.com/Mountagha/Module-4)

This is [Module-4](https://github.com/Mountagha/Module-3) this module takes advantage of the fully working deep learning build through [Module-0](https://github.com/Mountagha/Module-0) to [Module-3](https://github.com/Mountagha/Module-3) and build an image recognition system.

### Notes

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module4.html

This module requires `fast_ops.py`, `cuda_ops.py`, `scalar.py`, `tensor_functions.py`, `tensor_data.py`, `tensor_ops.py`, `operators.py`, `module.py`, and `autodiff.py` from Module 3.


Additionally you will need to install and download the MNist library.

(On Mac, this may require installing the `wget` command)

```
pip install python-mnist
mnist_get_data.sh
```


* Tests:

```
python run_tests.py
```
