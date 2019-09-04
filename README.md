[![Build Status](https://travis-ci.org/vvv214/LDP_Protocols.png?branch=master)](https://travis-ci.org/vvv214/LDP_Protocols)

## Environment
Python 2.7.10 (can also work for Python 3 by chaning the print statements)

xxhash 1.0.1

numpy 1.11.3

pytest 3.4.0

Or, run
```
pip install -r requirements.txt
pytest
```


## Protocols


### OLH
Frequency Oracle

Related Paper: Locally Differentially Private Protocols for Frequency Estimation 
([link](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-wang-tianhao.pdf))


### I am slowly cleaning and publishing code for the protocols below:


### PEM
Heavy Hitter Identification

Related Paper: Locally Differentially Private Heavy Hitter Identification
([link](https://arxiv.org/pdf/1708.06674.pdf))


### SVIM/SVSM
Frequent Itemset Mining

Related Paper: Locally Differentially Private Frequent Itemset Mining
([link](https://ieeexplore.ieee.org/document/8418600))

Errata: In Equation (10) of Section V, there are three terms, two of them misses the coefficient $\ell$.

Clarification: To find top-k itemsets, we also consider singleton estimates from SVIM.


<!--- ### CALM (under construction) Marginal Estimation Related Paper: CALM: Consistent Adaptive Local Marginal for Marginal Release under Local Differential Privacy ([link](https://dl.acm.org/citation.cfm?id=3243742)) --->
<!--- ###HIO (under construction) Multi-Dimensional Analytics Related Paper: Answering Multi-Dimensional Analytical Queries under Local Differential Privacy ([link](https://dl.acm.org/citation.cfm?id=3319891)) --->
<!--- ### Norm-Hyb Post-Porcessing Related Paper: Consistent and Accurate Frequency Oracles under Local Differential Privacy ([link](https://arxiv.org/pdf/1905.08320.pdf)) --->


### CALM
Marginal Estimation 

The source code is not opened yet, but the similar code (plus a data synthesizing component) for the central DP setting is opened at [DPSyn](https://github.com/usnistgov/PrivacyEngCollabSpace/tree/master/tools/de-identification/Differential-Privacy-Synthetic-Data-Challenge-Algorithms/DPSyn) (related info at [nist challenge 1](
https://www.nist.gov/communications-technology-laboratory/pscr/funding-opportunities/open-innovation-prize-challenges-2) and [nist challenge 2](https://www.nist.gov/communications-technology-laboratory/pscr/funding-opportunities/open-innovation-prize-challenges-1).

Related Paper: CALM: Consistent Adaptive Local Marginal for Marginal Release under Local Differential Privacy ([link](https://dl.acm.org/citation.cfm?id=3243742))


### MURS
Shuffler Model

Related Paper: Practical and Robust Privacy Amplification with Multi-Party Differential Privacy
([link](https://arxiv.org/pdf/1908.11515.pdf))


