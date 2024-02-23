---
category: reference
citekey: @Selvaraju2020a
stage: working
year: 2020
---


# Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization

%% begin tags %%
#machine_learning 
%% end tags %%

> [!tip]  
> **Zotero** = [Selvaraju et al_2020_Grad-CAM.pdf](zotero://select/library/items/DNNBJJ5F)
> **Citation Key** = @Selvaraju2020a

> [!cite]
> Selvaraju, R. R., Cogswell, M., Das, A., Vedantam, R., Parikh, D., & Batra, D. (2020). Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization. _International Journal of Computer Vision_, _128_(2), 336–359. [https://doi.org/10.1007/s11263-019-01228-7](https://doi.org/10.1007/s11263-019-01228-7)


## Abstract
We propose a technique for producing ‘visual explanations’ for decisions from a large class of Convolutional Neural Network (CNN)-based models, making them more transparent and explainable. Our approach—Gradient-weighted Class Activation Mapping (Grad-CAM), uses the gradients of any target concept (say ‘dog’ in a classification network or a sequence of words in captioning network) flowing into the final convolutional layer to produce a coarse localization map highlighting the important regions in the image for predicting the concept. Unlike previous approaches, Grad-CAM is applicable to a wide variety of CNN model-families: (1) CNNs with fully-connected layers (e.g.VGG), (2) CNNs used for structured outputs (e.g.captioning), (3) CNNs used in tasks with multi-modal inputs (e.g.visual question answering) or reinforcement learning, all without architectural changes or re-training. We combine Grad-CAM with existing fine-grained visualizations to create a high-resolution class-discriminative visualization, Guided Grad-CAM, and apply it to image classification, image captioning, and visual question answering (VQA) models, including ResNet-based architectures. In the context of image classification models, our visualizations (a) lend insights into failure modes of these models (showing that seemingly unreasonable predictions have reasonable explanations), (b) outperform previous methods on the ILSVRC-15 weakly-supervised localization task, (c) are robust to adversarial perturbations, (d) are more faithful to the underlying model, and (e) help achieve model generalization by identifying dataset bias. For image captioning and VQA, our visualizations show that even non-attention based models learn to localize discriminative regions of input image. We devise a way to identify important neurons through Grad-CAM and combine it with neuron names (Bau et al. in Computer vision and pattern recognition, 2017) to provide textual explanations for model decisions. Finally, we design and conduct human studies to measure if Grad-CAM explanations help users establish appropriate trust in predictions from deep networks and show that Grad-CAM helps untrained users successfully discern a ‘stronger’ deep network from a ‘weaker’ one even when both make identical predictions. Our code is available at https://github.com/ramprs/grad-cam/, along with a demo on CloudCV (Agrawal et al., in: Mobile cloud visual media computing, pp 265–290. Springer, 2015) (http://gradcam.cloudcv.org) and a video at http://youtu.be/COjUB9Izk6E.


# Annotations
%% begin annotations %%  
  

  
###### Imported: 2024-02-08 8:44 am  
  
> Consequently, when today’s intelligent systems fail, they often fail spectacularly disgracefully without warning or explanation, leaving a user staring at an incoherent output, wondering why the system did what it did.  


*Unguided or unsupervised systems seem to produce outputs that can be flawed, particularly when thinking about causal problems.*

  
> First, when AI is significantly weaker than humans and not yet reliably deployable (e.g. visual question answering [3]), the goal of transparency and explanations is to identify the failure modes [1,25], thereby helping researchers focus their efforts on the most fruitful research directions. Second, when AI is on par with humans and reliably deployable (e.g., image classification [30] trained on sufficient data), the goal is to establish appropriate trust and confidence in users. Third, when AI is significantly stronger than humans (e.g. chess or Go [50]), the goal of explanations is in machine teaching [28] – i.e., a machine teaching a human about how to make better decisions.  


*This concept is interesting. There may be levels of where AI and ML can interact with humans in different capacities.*

  
> In order to combine the best of both worlds, we show that it is possible to fuse existing pixel-space gradient visualizations with Grad-CAM to create Guided Grad-CAM visualizations that are both high-resolution and class-discriminative.  


*Essentially, can increase interpretability without sacrificing model accuracy or structure.*

  
>   
 
![fig-3-x43-y569](figures/Selvaraju2020a/fig-3-x43-y569.png)


*Fig. 1: (a) Original image with a cat and a dog. (b-f) Support for the cat category according to various visualizations for VGG-16 and ResNet. (b) Guided Backpropagation [53]: highlights all contributing features. (c, f) Grad-CAM (Ours): localizes class-discriminative regions, (d) Combining (b) and (c) gives Guided Grad-CAM, which gives high-resolution class-discriminative visualizations. Interestingly, the localizations achieved by our Grad-CAM technique, (c) are very similar to results from occlusion sensitivity (e), while being orders of magnitude cheaper to compute. (f, l) are Grad-CAM visualizations for ResNet-18 layer. Note that in (c, f, i, l), red regions corresponds to high score for class, while in (e, k), blue corresponds to evidence for the class. Figure best viewed in color.*

  
>   
 
![fig-4-x39-y569](figures/Selvaraju2020a/fig-4-x39-y569.png)


*Fig. 2: Grad-CAM overview: Given an image and a class of interest (e.g., ‘tiger cat’ or any other type of differentiable output) as input, we forward propagate the image through the CNN part of the model and then through task-specific computations to obtain a raw score for the category. The gradients are set to zero for all classes except the desired class (tiger cat), which is set to 1. This signal is then backpropagated to the rectified convolutional feature maps of interest, which we combine to compute the coarse Grad-CAM localization (blue heatmap) which represents where the model has to look to make the particular decision. Finally, we pointwise multiply the heatmap with guided backpropagation to get Guided Grad-CAM visualizations which are both high-resolution and concept-specific.*

  

  
%% end annotations %%

# Notes
%% begin notes %%
- [ ] Finish reading article
- [ ] Look at equations and try to understand them

I've started taking notes on using this software in [Gradient-Weighted Class Activation Mapping (Grad-CAM)](../permanent/Gradient-Weighted%20Class%20Activation%20Mapping%20(Grad-CAM).md). 

%% end notes %%

%% Import Date: 2024-02-08T08:45:02.625-06:00 %%
