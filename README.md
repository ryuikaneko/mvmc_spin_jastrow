# mVMC (unofficial spin Jastrow implementation)

* Current [mVMC](https://github.com/issp-center-dev/mVMC) code (at least ver.1.1.1) cannot treat the spin Jastrow factor.
* This is an unofficial patch for the spin Jastrow implementation (when Sz is not fixed).
* The simplest modification is to replace the charge Jastrow part in [mVMC/src/mVMC/projection.c](https://github.com/issp-center-dev/mVMC/blob/master/src/mVMC/projection.c) with the spin Jastrow one.
* At the moment, the charge Jastrow factor will be overwritten by the spin Jastrow one.
* Install in the google colaboratory environment [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryuikaneko/mvmc_spin_jastrow/blob/master/mVMC-1.1.1__spin_jastrow_only__sz_nonfixed_only/mvmc_spin_jastrow.ipynb)
