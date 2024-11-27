#Masterthesis-Analysis-of-the-contribution-of-clinical-texts-to-early-prediction-of-sepsis
Abstract:
Sepsis is a life-threatening condition characterized by the body’s immune response
to infection, leading to organ failure and mortality. Early detection and prediction
of sepsis are important for effective treatment and improved patient outcomes. This
study focuses on early sepsis prediction using a combination of physiological values
and clinical text data. The aim is to evaluate the performance of a Transformer-
based model proposed by Wang et al. [1] applied to the MIMIC-III dataset.
In our work, we conducted several ablation studies to investigate how removing
specific words affects the predictions of the model. We also focused on the effects
of removing words with high average attention weights. These words were found
to have a significant impact on model performance compared to other medical
terms associated with sepsis diagnosis, such as "sepsis" and "infection". However,
it should be noted that the model may encounter difficulties in distinguishing
between medical terms that are not exclusively specific to sepsis diagnosis but also
associated with other diseases. This work emphasizes the need to consider specific
criteria and further investigate the effect of different terms on sepsis prediction.

[1] Yuqing Wang et al. “Integrating Physiological Time Series and Clinical
Notes with Transformer for Early Prediction of Sepsis”. In: arXiv preprint
arXiv:2203.14469 (2022).
