# Unifying-Vision-and-Language-Tasks-via-Text-Generation

In this study, we reproduce the works created in the paper named Unifying Vision-and-Language Tasks via Text Generation. Normally, there are task-specific models for each of these tasks in the literature.  But creating a separate model for each task requires extra effort and time. Moreover, the approach presented in this paper achieves success close to task specific models in the literature.

In this paper, 2 different models are presented that can perform different tasks on a single model. These are named VL-T5 and VL-BART. There are very minor architectural differences between the two. We performed our experiments on the VL-T5. Our aim in this study is to set up experiments to prove that the model presented by the authors can deliver what they promise.
For this purpose, we create 5 different experiments.
<br>
- VQAValid.ipynb: Experiment for custom data to test that the existing model can perform the VQA task.
- VQAValidError.ipynb: Experiment for showing the model not valid vqa task if image contains both woman and mans
- VQABiasDetection.ipynb: Experiment for racial bias detection
- Reproducible_VQA.ipynb:Experiment for reproducing VQA task result
- Reproducible_NLVR.ipynb: Experiment for reproducing NLVR task result

