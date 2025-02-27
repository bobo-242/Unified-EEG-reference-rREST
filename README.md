# A repository of Unified-EEG-reference-rREST

<img src="https://github.com/ShiangHu/Unified-EEG-reference-rREST/blob/master/rREST%202017/head.jpg" width="150" align='right'>

## How to apply rREST

### Step1 Download

   Download matlab and [eeglab](https://sccn.ucsd.edu/eeglab/download.php) Toolbox
   
   Download and unzip to your work directory
   
### Step2 Use [rREST_core](https://github.com/ShiangHu/Unified-EEG-reference-rREST/tree/master/rREST_core) and [sample data](https://github.com/ShiangHu/Unified-EEG-reference-rREST/tree/master/sample%20data)
   
   Open [Main_REST4Giorgio.m](https://github.com/ShiangHu/Unified-EEG-reference-rREST/blob/master/sample%20data/Main_REST4Giorgio.m) and modify at least three paths in the code, as follows
   
   rRESTpath: to the folder [rREST_core](https://github.com/ShiangHu/Unified-EEG-reference-rREST/tree/master/rREST_core)
   
   eeglabpath: to the eeglab toolkit you downloaded
   
   eegpath: to the folder [sample data](https://github.com/ShiangHu/Unified-EEG-reference-rREST/tree/master/sample%20data)
   
   Optional
   
   eegname and lfname: file name of your personal data
   
### Step3 Applying

   Run [Main_REST4Giorgio.m](https://github.com/ShiangHu/Unified-EEG-reference-rREST/blob/master/sample%20data/Main_REST4Giorgio.m), then You will get the converted data file under the current folder
   
### about
   
   For the theory of rREST, see the paper: [Unified Bayesian estimator of EEG reference at infinity: rREST](https://doi.org/10.3389/fnins.2018.00297)

## How to apply unipolar reference
   Use [unipolar_ref](https://github.com/ShiangHu/Unified-EEG-reference-rREST/tree/master/unipolar_ref) and see the paper: [The statistics of EEG unipolar references](https://link.springer.com/article/10.1007/s10548-019-00706-y)

## Publications
*1) Hu, S., Lai, Y., Valdes-Sosa, P. A., Bringas-Vega, M. L., & Yao, D. (2018). [How do reference montage and electrodes setup affect the measured scalp EEG potentials?](https://iopscience.iop.org/article/10.1088/1741-2552/aaa13f)*

*2) Yao, D., Qin, Y., Hu, S., Dong, L., Vega, M. L. B., & Sosa, P. A. V. (2019). [Which Reference Should We Use for EEG and ERP practice?](https://link.springer.com/article/10.1007/s10548-019-00707-x)*

*3) Yao, D. (2001). [A method to standardize a reference of scalp EEG recordings to a point at infinity](https://iopscience.iop.org/article/10.1088/0967-3334/22/4/305/meta)*
