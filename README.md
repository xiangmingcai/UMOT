# UMOT
Unmixing Matrix Online web Toolkit for spectral flow cytometry

<p align="center">
  <img src="./images/overview.jpg" />
</p>


Unmixing is a key step of spectral flow cytometry, and the unmixing matrix is a matrix containing signatures of fluors and autofluorescences. **The UMOT is developed to address the unmixing issues**, which is caused by the mismatch between extracted signatures and "real" signatures in multi-color samples.

The UMOT includes 3 out-of-the-box webtools:
  1. [Unmixing Matrix Generator (UMG)](https://github.com/xiangmingcai/UnmixingMtxGenerator.github.io/tree/main): generate unmixing matrix from raw fcs files.

2. **[Unmixing Matrix Optimizer (UMO)](https://github.com/xiangmingcai/UnmixingMtxOptimizer.github.io): correct unmixing matrix to address unmixing issues.** 🚀🚀🚀

  3. [Unmixing In Batch (UIB)](https://github.com/xiangmingcai/UnmixingInBatch.github.io): do unmixing on raw fcs files to obtain unmixed fcs files in batch.

The UMG could be very helpful for users to generate an unmixing matrix in ~ 30 mins to 1 hour, since most flow cytometers do not allow exporting unmixing matrix. 

**The UMO is the core module of the UMOT toolkit.** In fact, both UMG and UIB are designed to support the use of UMO. The UMG is super-powerful and user-friendly in addressing most unmixinng issues. The algorithm of UMO will be released in our paper, which in ongoing...

For the whole UMOT project, fcs files from Aurora and Xenith were tested and supported.💪💪💪

If you find any bug, fell free to post in the [Issues](https://github.com/xiangmingcai/UMOT/issues)
Note: UMOT is complete static, meaning everything you do with UMOT is 100% local. No data will be sent out, and we do not store any user information.


📝If you find it helpful, please remember to cite us in your work. 

<br>

- Author : Xiangming Cai; Sara Garcia Garcia; Juan J. Garcia Vallejo

- Email : x.cai@amsterdamumc.nl

- Update time : 2025/4/6

- Version: v1.0

Links to: 

🐱[Xiangming Cai](https://www.linkedin.com/in/xiangming-cai-7a95a1258/)

🎣[Group Juan](https://immunologyamsterdam.org/2020/08/10/juan-j-garcia-vallejo/)

🎮[Core facility](https://vumc.nl/research/overzicht/molecular-cell-biology-immunology-research/mcbi-technology-center/o2flow-facility-mcbi.htm)

<p align="center">
  <img src="./images/logo-amsterdamumc.svg" width = 200  class="left-align" />
</p>
  
