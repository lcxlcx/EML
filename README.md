# EML
Knowledge distillation (KD) is an effective method for acquiring smaller networks exhibiting excellent performance in running on most common devices. Previous methods mainly use logits to realize KD; however, the rich knowledge contained in feature maps has not yet been fully utilized. To address this problem, we propose a novel online KD method—embedded mutual learning (EML). By embedding an adaptive fusion branch and ensemble classifier between two parallel sub-networks, EML uses logits as well as overall feature map distribution of the co-trained sub-networks to fully mine and utilize the implicit knowledge between networks. Specifically, EML is widely applicable to various sub-network combinations, comprising heterogeneous or homogeneous networks. We conduct experiments on three public datasets: CIFAR-10, CIFAR-100, and ImageNet, which prove that our method outperforms state-of-the-art KD methods.
