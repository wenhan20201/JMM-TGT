# JMM-TGT: Self-supervised 3D action recognition through joint motion masking and topology-guided transformer
Han Wen, Guangping Zeng, Qingchuan Zhang, Zihan Li, Mengyang Zhu

Wen H, Zeng G, Zhang Q, Li Z,
Zhu M (2025) [JMM-TGT: Self-supervised 3D action recognition through joint motion masking and topology-guided transformer.](https://doi.org/10.1371/journal.pone.0338008) PLoS One 20(12): e0338008.

![](images/Fig1.tif)
![](images/Fig2.tif)

## Abstract
In the field of 3D skeleton action recognition, research on self-supervised learning methods has primarily focused on spatio-temporal feature modeling. However, these methods rely heavily on modeling single motion features, which limits their ability to capture subtle motion variations and complex spatio-temporal relationships. This is a direct result of the fact that understanding the model of the action remains incomplete. To address the above-mentioned issue, this paper proposes the Joint Motion Masking with Topology-Guided Transformer model (JMM-TGT) for action recognition. First, the Joint Motion Masking strategy is applied to enhance the ability of the model to perceive subtle joint movements. This method can generate masking probabilities by combining the differences and similarities in joint motion, thereby guiding the selection of joints to be masked at each time step. Meanwhile, in the transformer-based encoder module, the topological relationship between joints is introduced to adjust the attention mechanism, allowing the model to capture spatio-temporal dependencies and better understand the complex dynamic patterns of joint motion. To verify the performance of the JMM-TGT model, we conducted comparison experiments between it and mainstream action recognition models. Experiments demonstrate that the proposed JMM-TGT achieves performance improvements ranging from 1.5\% to 7.9\% under different evaluation settings on the NTU RGB+D 60, NTU RGB+D 120, and PUK-MMD datasets.

# Requirements
```bash
python==3.8.13
torch==1.8.1+cu111
torchvision==0.9.1+cu111
tensorboard==2.9.0
timm==0.3.2
scikit-learn==1.1.1
tqdm==4.64.0
numpy==1.22.4
```
# Raw Datasets
PUK-MMD: http://39.96.165.147/Projects/PKUMMD/PKU-MMD.html

NTU RGB+D 60\120: https://rose1.ntu.edu.sg/dataset/actionRecognition

# Preprocessed data and The minimal dataset for reproducing the results of this study：

https://pan.baidu.com/s/1hCc5iu24rSeW038UXsdqGA?pwd=ipv3 提取码: ipv3 
