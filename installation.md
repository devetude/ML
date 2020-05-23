---
description: How to install ML environment?
---

# Installation

### 1. Install Anaconda3

{% hint style="info" %}
Anaconda

The open-source Individual Edition \(Distribution\) is the easiest way to perform Python/R data science and machine learning on a single machine.

[Read more...](https://www.anaconda.com/)
{% endhint %}

**We'd better install Anaconda3 `5.2.x` version.** Because embed Python version is `3.7.x` from Anaconda3 `5.3.x` version. But **Tensorflow doesn't support libraries of Python `3.7.x` version.** So, when you already installed Anaconda3 `5.3.x` version then you have to downgrade your Python version to `3.6.x`.

You can download Anaconda3 `5.2.x` version for Windows x64 to click [here](https://repo.anaconda.com/archive/Anaconda3-5.2.0-Windows-x86_64.exe).

### 2. Update Anaconda3

When you finished Anaconda3 installation, **open Anaconda prompt and insert some commands for updating to the latest version.** This work is required quite times and during updates, we have to insert `y` several times to agree.

```python
conda update -n base conda
conda update --all
```

### 3. Install Tensorflow

{% hint style="info" %}
Tensorflow

TensorFlow is an end-to-end open source platform for machine learning. The core open source library to help you develop and train ML models.

[Read more...](https://www.tensorflow.org/)
{% endhint %}

Now, **we will create Tensorflow CPU virtual environment and its name is `tensorflow_cpu`.** Also, **we have to activate created virtual environment.**

```python
conda create -n tensorflow_cpu python=3.6
activate tensorflow_cpu
```

### 4. Update PIP

{% hint style="info" %}
PIP\(=Package Installer for Python\)

PIP is the package installer for Python. You can use PIP to install packages from the Python Package Index and other indexes.

[Read more...](https://github.com/pypa/pip)
{% endhint %}

After activating your own virtual environment, **let's update PIP and install Tensorflow CPU version.** This work is also required quite times and during updates, we have to insert `y` several times to agree.

```python
pyhton -m pip install --upgrade pip
pip install tensor flow
```

### 5. Install extra libraries

Finally, we will install extra libraries which are used frequently to develop machine learning projects. Via PIP, we can install easily these libraries.

{% hint style="info" %}
[NumPy](https://numpy.org/): The package for scientific computing.  
[Matplotlib](https://matplotlib.org/): A library for creating static, animated, and interactive visualizations.  
[Pandas](https://pandas.pydata.org/): A open source data analysis and manipulation tool.  
[Pillow](https://pillow.readthedocs.io/en/stable/): Python Imaging Library  
[Graphviz](https://www.graphviz.org/): A open source graph visualization software.
{% endhint %}

```python
pip install numpy matplotlib pandas pillow graphviz
```

