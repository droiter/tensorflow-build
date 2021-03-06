This repository contains custom builds of tensorflow. To install
one of these on your system, download the correct file according
to your version of python and gcc and run the following command.
```
pip install --ignore-installed --upgrade /path/to/binary.whl
```
| TF       | HW  | OS           | GCC            | Python      | Supports                                  |                                                                                                                         |
|----------|-----|--------------|----------------|-------------|-------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| 1.1.0    | CPU | Arch Linux   | 6.3            | 3.6.1       | FMA, AVX, AVX2, SSE4.1, SSE4.2, XLA       | [Download](https://github.com/lakshayg/tensorflow-build/raw/master/tensorflow-1.1.0-cp36-cp36m-linux_x86_64.whl)        |
| 1.2.0rc1 | CPU | Arch Linux   | 6.3            | 3.6.1       | Optimized for Intel Core i7-4500U         | [Download](https://github.com/lakshayg/tensorflow-build/raw/master/tensorflow-1.2.0rc1-cp36-cp36m-linux_x86_64.whl)     |
| 1.2.0rc2 | CPU | Arch Linux   | 7.1            | 3.6.1       | Optimized for Intel Core i7-4500U + MKL   | [Download](https://github.com/lakshayg/tensorflow-build/raw/master/tensorflow-1.2.0rc2-cp36-cp36m-linux_x86_64.whl)     |
| 1.3.0rc2 | CPU | Ubuntu 16.04 | 5.4            | 3.5.2       | FMA, AVX, AVX2, SSE4.1, SSE4.2            | [Download](https://github.com/lakshayg/tensorflow-build/raw/master/tensorflow-1.3.0rc2-cp35-cp35m-linux_x86_64.whl)     |
| 1.3.0rc2 | CPU | Ubuntu 16.04 | 5.4            | 2.7.12      | FMA, AVX, AVX2, SSE4.1, SSE4.2            | [Download](https://github.com/lakshayg/tensorflow-build/raw/master/tensorflow-1.3.0rc2-cp27-cp27mu-linux_x86_64.whl)    |
| 1.2.1    | CPU | macOS Sierra | clang-802.0.42 | 2.7.13      | AVX, SSE4.1, SSE4.2                       | [Download](https://github.com/lakshayg/tensorflow-build/raw/master/tensorflow-1.2.1-cp27-cp27m-macosx_10_12_x86_64.whl) |
| 1.3.0rc2 | CPU | macOS Sierra | clang-802.0.42 | 2.7.13      | FMA, AVX, AVX2, SSE4.1, SSE4.2            | [Download](https://github.com/lakshayg/tensorflow-build/raw/master/tensorflow-1.3.0rc2-cp27-cp27m-macosx_10_12_intel.whl) |
| 1.2.1    | CPU | macOS Sierra | clang-802.0.42 | 3.6.1       | AVX, SSE4.1, SSE4.2                       | [Download](https://github.com/lakshayg/tensorflow-build/raw/master/tensorflow-1.2.1-cp36-cp36m-macosx_10_12_x86_64.whl) |
| 1.2.1    | CPU | macOS Sierra | clang-802.0.42 | 3.6.1       | FMA, AVX, AVX2, SSE4.1, SSE4.2            | [Download](https://github.com/lakshayg/tensorflow-build/raw/72454268db8ce69e0fe3c7b23c17aad6ea69b257/tensorflow-1.2.1-cp36-cp36m-macosx_10_12_x86_64.whl) |

**External Links** (Please consider giving a :star: or :+1: to the original sources in case you use external links)

| TF       | HW       | OS           | Python        | Supports                            |                                         |
|----------|----------|--------------|---------------|-------------------------------------|-----------------------------------------|
| 1.1-1.3  | CPU, GPU | Ubuntu 16.04 | 2.7, 3.5, 3.6 | FMA, AVX, AVX2, SSE4.1, SSE4.2, MPI | [Link](https://github.com/mind/wheels)  |
| 1.2.1    | CPU      | Ubuntu 17.01 | 3.5.3         | XLA, AVX, AVX2, FMA, SSE4.1, SSE4.2 | [Link](https://github.com/yaroslavvb/tensorflow-community-wheels/issues/26) |

**Note**

* Consider filling this form https://goo.gl/forms/ELoTSOcHE99nhVXc2 if you have downloaded or would like to request a binary
* Feel free to open a pull request/issue if you would like to share your binary on this page
