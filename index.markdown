---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

![overview](/assets/images/1.png)

# SOON: Scenario Oriented Object Navigation

The ability to navigate like a human towards a language-guided target from anywhere in a 3D embodied environment is one of the "holy grail" goals of intelligent robots. Most visual navigation benchmarks, however, focus on navigating toward a target from a fixed starting point, guided by an elaborate set of instructions that depicts step-by-step. This approach deviates from real-world problems in which human-only describes what the object and its surrounding look like and asks the robot to start navigation from anywhere. Accordingly, we introduce a Scenario Oriented Object Navigation (SOON) task. In this task, an agent is required to navigate from an arbitrary position in a 3D embodied environment to localize a target following a scene description. We also propose a new large-scale benchmark named From Anywhere to Object (FAO) dataset. To avoid target ambiguity, the descriptions in FAO provide rich semantic scene information includes: object attribute, object relationship, region description, and nearby region description. 

## Dataset Analysis

![framework_v2](/assets/images/2.png)


#### Download FAO dataset

<a id="anchor-name"></a>

The FAO dataset is provided: [train.json](https://drive.google.com/file/d/1tuS3PFHOECwA5U-ofFyv6WZnTXoZjaBr/view?usp=sharing), [val_unseen_instrs.json](https://drive.google.com/file/d/1r6-rkaj02fdVPmFdpTlVrUX9k6WECRNb/view?usp=sharing),[val_unseen_house.json](https://drive.google.com/file/d/1MtALkrfXoXug3hLNim2BUt8_CKcQbPzv/view?usp=sharing), [test_minival.json](https://drive.google.com/file/d/122EGTMa2UeGsmKXBWb7DMwOBeguhPj0d/view?usp=sharing)


### Important Dates

**July 28, 2021:** Challenge starts

**September 28, 2021:** Results submission deadline

**October 8, 2021:** Paper submission deadline


## Citation
```
@InProceedings{Zhu_2021_CVPR,
    author    = {Zhu, Fengda and Liang, Xiwen and Zhu, Yi and Yu, Qizhi and Chang, Xiaojun and Liang, Xiaodan},
    title     = {SOON: Scenario Oriented Object Navigation With Graph-Based Exploration},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2021},
    pages     = {12689-12699}
}
```

