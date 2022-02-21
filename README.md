# Probability model misspecification and parameter estimation uncertainty
## Abstract

One of the main steps in probabilistic seismic collapse risk assessment is estimating the fragility function parameters. The maximum likelihood estimation (MLE) approach, which is widely used for this purpose, contains the underlying assumption that the likelihood function is known to follow a specified parametric probability distribution. However, this assumed distribution may not always be consistent with the “true” probability distribution of the collapse data. This paper implements the Information matrix equivalence theorem to identify the presence of model misspecification i.e., if the assumed collapse probability distribution is, in fact, the “true” one. In the presence of model misspecification, the fragility parameter estimates continue to be asymptotically normally distributed but the variance-covariance matrix is no longer equal to the inverse of the Fisher’s Information matrix. To increase the robustness of the variance-covariance matrix, the Huber-White sandwich estimator is implemented. Using collapse data from eight woodframe buildings, the effect of model misspecification on fragility parameter estimates and collapse rate is quantified. For the considered building cases, the parameter estimation uncertainty in the collapse risk did not increase when the “sandwich” estimator was used compared to when probability model misspecification was not considered (i.e., using MLE). The proposed framework should be used to further investigate the issue of probability model misspecification as it relates to fragility parameter estimation since only a single construction type (woodframe buildings) and limit state (collapse) was considered in the current study.


### For more information, please refer to the following:
* Dahal, L., Burton, H., & Onyambu, S. (2022). Quantifying the effect of probability model misspecification in seismic collapse risk assessment. Structural Safety, 96, 102185.

## Citation
<pre>
@article{dahal2022quantifying,
  title={Quantifying the effect of probability model misspecification in seismic collapse risk assessment},
  author={Dahal, Laxman and Burton, Henry and Onyambu, Samuel},
  journal={Structural Safety},
  volume={96},
  pages={102185},
  year={2022},
  publisher={Elsevier}
}
</pre>
