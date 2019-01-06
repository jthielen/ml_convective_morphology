# Classification of Convective Morphology Using Machine Learning

*Jonathan E. Thielen, W. A. Gallus, and A. M. Haberlie*

## Project Abstract

Mesoscale convective systems (MCSs) play a critical role in the hydroclimate and occurrence of severe weather in the central United States. In the analysis and forecasting of these convective systems, the morphology—the shape, structure, and organization—is an important system characteristic. Numerous past studies have used radar mosaic imagery to evaluate both observed and modeled systems according to categories or modes of convective morphology. However, their methods have relied on manual classification, which limits potential sample sizes and risks inconsistency of results. Recent advancements in the use of image analysis software to automatically extract convective systems from radar mosaics and of machine learning algorithms to classify said systems have shown promise in the automation of convective morphology analysis. However, no framework yet exists for automated classification according to detailed convective modes with subtypes of cellular and linear systems, and so, this study seeks to evaluate and compare machine learning techniques in addressing this problem of detailed convective classification. Results from this study show that an ensemble of decision tree ensemble classifiers which utilize a large set of input parameters designed to differentiate between the convective modes performs best at this detailed classification task. This classifier performs better than any of the decision tree ensemble classifiers relying on only the basic areal and intensity parameters used in past studies or convolutional neural networks (CNNs), even though prior studies have suggested that CNNs tend to outperform other image classification techniques. However, with an overall accuracy score of 59.37%, this best-performing decision tree ensemble technique remains insufficient for future use as an automated tool in research or operations. Therefore, additional steps are considered for how to improve the classification accuracy and obtain a more reliable method for future use.

## Papers/Presentations

- [Poster (presented at AMS Student Conference 2019)](presentation/thielen_ml_morphology_ams_2019.pdf)
- [Presentation (ISU Senior Thesis)](presentation/thielen_senior_thesis_presentation.pdf)
- [Paper (ISU Senior Thesis)](paper/thielen_senior_thesis.pdf)

## Preliminary Analysis Notebooks/Data/Figures

See [notebooks/](notebooks/).

## Areas of Ongoing Work

- Enhancement of past results through
  - Exapanded training sample
  - Re-formulation of added morphology parameters
  - More robust CNNs
- Including temporal continuity criteria of past studies
- Connections with severe weather reports
