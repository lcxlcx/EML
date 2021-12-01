# We will open source our code soon.


# EML Online Distillation Framework
**The EML schematic**

![EML.png](https://i.loli.net/2021/12/01/3RlIK8pCvQiOY4a.png)



# EML
Knowledge distillation (KD) is an effective method for acquiring smaller networks exhibiting excellent performance for deploying on most common devices. Previous KD methods mostly use simple information contained in logits or features as the source of KD, resulting in limited performance improvement. And the online distillation structure also lacks flexibility. To address those problems, we propose a novel online KD method called embedded mutual learning (EML). By embedding an adaptive fusion branch and an ensemble branch between two parallel peer networks, EML can use the ensemble information and overall feature map distribution of the co-trained peer networks as well as the logits to complete online KD. Diverse knowledge helps fully mine the potential of the model during the distillation process.  We conduct experiments on three public datasets: CIFAR-10, CIFAR-100, and ImageNet, which prove that our method outperforms state-of-the-art KD methods. Meanwhile, we provide insights on why our EML method is effective from different perspectives. In particular, the embedded implementation makes EML highly flexible. EML is widely applicable to various network combinations, comprising heterogeneous or homogeneous networks.
