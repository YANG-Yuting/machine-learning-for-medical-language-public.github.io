---
title: "Improving Model Transferability for Clinical Note Section Classification Models Using Continued Pretraining"
collection: publications
permalink: /publications/2023-09-19-section-continued-pretraining
date: 2023-09-19
venue: 'Journal of the American Medical Informatics Association (JAMIA)'
paperurl: 'https://academic.oup.com/jamia/advance-article/doi/10.1093/jamia/ocad190/7277369?login=true'
citation: '<b>Weipeng Zhou</b>, Meliha Yetisgen, Yanjun Gao, Guergana Savova, and <b>Timothy Miller</b>. 2023. Improving Model Transferability for Clinical Note Section Classification Models Using Continued Pretraining. JAMIA, September 2023, ocad190'
---
Objective: The classification of clinical note sections is a critical step before doing more fine-grained natural language processing tasks such as social determinants of health extraction and temporal information extraction. Often, clinical note section classification models that achieve high accuracy for 1 institution experience a large drop of accuracy when transferred to another institution. The objective of this study is to develop methods that classify clinical note sections under the SOAP ("Subjective," "Object," "Assessment," and "Plan") framework with improved transferability.

Materials and methods: We trained the baseline models by fine-tuning BERT-based models, and enhanced their transferability with continued pretraining, including domain-adaptive pretraining and task-adaptive pretraining. We added in-domain annotated samples during fine-tuning and observed model performance over a varying number of annotated sample size. Finally, we quantified the impact of continued pretraining in equivalence of the number of in-domain annotated samples added.

Results: We found continued pretraining improved models only when combined with in-domain annotated samples, improving the F1 score from 0.756 to 0.808, averaged across 3 datasets. This improvement was equivalent to adding 35 in-domain annotated samples.

Discussion: Although considered a straightforward task when performing in-domain, section classification is still a considerably difficult task when performing cross-domain, even using highly sophisticated neural network-based methods.

Conclusion: Continued pretraining improved model transferability for cross-domain clinical note section classification in the presence of a small amount of in-domain labeled samples.

