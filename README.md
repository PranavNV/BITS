# BITS (Bias Identification Test in Sentiments)

BITS is a sentence repository test that consists of **2,896 sentences** curated to probe sentiment and toxicity analysis models for biases in sociodemographic factors like disability, race and gender.

The dataset is currently divided into **three** primary facets. They are:
1. Disability Facet
2. Race Facet
3. Gender Facet

As the name explains, each facet contains sentences that are created to check if language models differentiate words based on that particular sociodemographic group it represents. This means that the Disability Facet can be used to check if language models are biased towards people with disability and the Race facet can be used to check if language models are biased towards certain races. 

The motivation behind the creation of BITS is to intitiate the first step to eliminate un-intended bias in sentiment analysis, i.e. **identification**. A model, if used in a social environment, must be aware of the possible biases it might have. The BITS template is created in a way that it can be easily modified or updated to include groups of concern for the usecase it is used in. More details about the creation process can be found in <Paper Under Rreview>. Do cite the work in case you use this dataset to check for bias in sentiment or toxicity analysis models. 

 Research Paper:
 @article{venkit2021identification,
  title={Identification of bias against people with disabilities in sentiment analysis and toxicity detection models},
  author={Venkit, Pranav Narayanan and Wilson, Shomir},
  journal={arXiv preprint arXiv:2111.13259},
  year={2021}
}
  

Please feel free to email us at pranav.venkit@psu.edu or shomir@psu.edu for additional information regarding this work. 
