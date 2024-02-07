---
category: reference
citekey: @vandeLeur2021
stage: working
year: 2021
---


# Discovering and Visualizing Disease-Specific Electrocardiogram Features Using Deep Learning

%% begin tags %%
#machine_learning 
#electrocardiogram 
#genetics 
%% end tags %%

> [!tip]  
> **Zotero** = [van de Leur et al_2021_Discovering and Visualizing Disease-Specific Electrocardiogram Features SUPPLEMENT.pdf](zotero://select/library/items/FQKHYKBM)
> **Citation Key** = @vandeLeur2021

> [!cite]
> van de Leur, R. R., Taha, K., Bos, M. N., van der Heijden, J. F., Gupta, D., Cramer, M. J., Hassink, R. J., van der Harst, P., Doevendans, P. A., Asselbergs, F. W., & van Es, R. (2021). Discovering and Visualizing Disease-Specific Electrocardiogram Features Using Deep Learning. _Circulation: Arrhythmia and Electrophysiology_, _14_(2), e009056. [https://doi.org/10.1161/CIRCEP.120.009056](https://doi.org/10.1161/CIRCEP.120.009056)


## Abstract
BACKGROUND: ECG interpretation requires expertise and is mostly based on physician recognition of specific patterns, which may be challenging in rare cardiac diseases. Deep neural networks (DNNs) can discover complex features in ECGs and may facilitate the detection of novel features which possibly play a pathophysiological role in relatively unknown diseases. Using a cohort of PLN (phospholamban) p.Arg14del mutation carriers, we aimed to investigate whether a novel DNN-based approach can identify established ECG features, but moreover, we aimed to expand our knowledge on novel ECG features in these patients. METHODS: A DNN was developed on 12-lead median beat ECGs of 69 patients and 1380 matched controls and independently evaluated on 17 patients and 340 controls. Differentiating features were visualized using Guided Gradient Class Activation Mapping++. Novel ECG features were tested for their diagnostic value by adding them to a logistic regression model including established ECG features. RESULTS: The DNN showed excellent discriminatory performance with a c-statistic of 0.95 (95% CI, 0.91–0.99) and sensitivity and specificity of 0.82 and 0.93, respectively. Visualizations revealed established ECG features (low QRS voltages and T-wave inversions), specified these features (eg, R- and T-wave attenuation in V2/V3) and identified novel PLN-specific ECG features (eg, increased PR-duration). The logistic regression baseline model improved significantly when augmented with the identified features (P<0.001). CONCLUSIONS: A DNN-based feature detection approach was able to discover and visualize disease-specific ECG features in PLN mutation carriers and revealed yet unidentified features. This novel approach may help advance diagnostic capabilities in daily practice. GRAPHIC ABSTRACT: A graphic abstract is available for this article.


# Annotations
%% begin annotations %%  
  

  
###### Imported: 2024-01-17 8:55 pm  
  
>   
 
![[figures/vandeLeur2021/fig-5-x83-y115.png]]


*They used median beats on 12-lead ECG for phospholamban mutant carriers and compared them with controls (on the left side). On the right, they used a deep neural network approach to help highlight regions of importance.*

  

  
%% end annotations %%

# Notes
%% begin notes %%
This approach using  neural networks seems to be readily applicable across multiple diseases. The limitation I think is in getting the case-control ratio correct.
%% end notes %%

%% Import Date: 2024-01-17T20:55:36.846-06:00 %%
