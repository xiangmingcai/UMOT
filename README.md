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

**The UMO is the core module of the UMOT toolkit.** In fact, both UMG and UIB are designed to support the use of UMO. The UMG is super-powerful💪 and user-friendly🥰 in addressing most unmixinng issues😵. 

In short, the UMOT assumes the selected "positive populaiton" and "negative population" are homogenious, and the only real difference between these two populations are the intensity of "positive fluor". The UMO will then use the unmixed incorrect difference at all other fluors to correct the signature of "positive fluor". The detail of the algorithm will be shown in our paper, which in ongoing...🥱

For the whole UMOT project, fcs files from Aurora and Xenith were already tested and supported.🔓 The fcs files from other spectral instruments should also work, as long as thr file follows a FCS 3.0/3.1 standard, which is probably the case.

If you find any bug💔, you may post in the [Issues](https://github.com/xiangmingcai/UMOT/issues). Also, feel free to reach out to us with an e-mail if you need specific assistance or if you got any suggestions.

Note: UMOT is complete static, meaning everything you do with UMOT is 100% local. No data will be sent out, and we do not store any user information.


📝If you find it helpful, please remember to give us a star⭐ and cite us in your work. 

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
  
/
