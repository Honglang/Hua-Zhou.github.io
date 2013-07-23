---
layout: default
title: TensorReg
---

## TensorReg Toolbox for Matlab

TensorReg toolbox is a collection of Matlab functions for tensor regressions.

### Compatibility

The code is tested on Matlab 8.0.0 (R2012b), but should work on other versions of Matlab with no or little changes. Current version works on these platforms: Windows 64-bit, Linux 64-bit, and Mac (Intel 64-bit). Type `computer` in Matlab's command window to determine the platform.

### Dependency

TensorReg toolbox requires the [tensor toolbox](http://www.sandia.gov/~tgkolda/TensorToolbox/index-2.5.html) developed at the Sandia National Laboratories. Please follow the link to download and install the tensor toolbox (it's free) before using the TensorReg toolbox. 

If you want to run sparse tensor regression, you also need to download and install the [SparseReg toolbox](http://www4.stat.ncsu.edu/~hzhou3/softwares/sparsereg/).

### Download

[TensorReg_toolbox_0.0.1.zip](../TensorReg_toolbox_0.0.1.zip) (693KB)

### Installation

1. Download the zip package
2. Extract the zip file
3. Rename the folder from `TensorReg_toolbox_0.0.1` to `TensorReg`
4. Add the `TensorReg` folder to Matlab search path (File -> Set Path ... -> Add Folder...)
5. Go through the documentation or following tutorials for the usage

### Tutorials

* [Resize arrays](./html/demo_resize.html)
* [Kruskal regression and sparse Kruskal regression](./html/demo_kruskal.html)
* [Tucker regression and sparse Tucker regression](./html/demo_tucker.html)
* [Regularized matrix regression](./html/demo_matrixreg.html)


### Licensing

TensorReg Toolbox for Matlab is licensed under the [BSD](./html/COPYRIGHT.txt) license. Please use at your own risk. 

The toolbox is developed by [Hua Zhou](http://www.stat.ncsu.edu/people/zhou/).  Lexin Li, Bo Zhang, Xiaoshan Li, Eun Jeong Min and Changhan Wang provide testing and valuable feedback.

### Citation

If you use this software in your research, please cite the following papers.

* H Zhou, L Li, and H Zhu (2013) Tensor regression with applications in neuroimaging data analysis, JASA 108(502):540-552. [link](http://www.tandfonline.com/doi/abs/10.1080/01621459.2013.776499#.UeW24mTXjbw)
* H Zhou and L Li (2013) Regularized matrix regression, Journal of Royal Statistical Society Series B, in press. \[[arXiv](http://arxiv.org/abs/1204.3331)\]
* X Li, H Zhou, and L Li (2013) Tucker tensor regression and neuroimaging analysis, \[[arXiv](http://arxiv.org/abs/1304.5637)\]

### Contacts

Hua Zhou <hua_zhou@ncsu.edu>
