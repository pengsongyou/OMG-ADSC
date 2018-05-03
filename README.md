# A Deep Network for Arousal-Valence Emotion Prediction with Acoustic-Visual Cues

This repository contains the source codes for our submissions to [OMG Emotion Challenge 2018].
Method descriptions can be found [here].

Team Member: [Songyou Peng], [Le Zhang], [Yutong Ban], [Meng Fang], [Stefan Winkler]

## Requirements
* [PyTorch]
* [torchvision]
* [NumPy]
* [scikit-image]
* [SphereFace (PyTorch)]

## Preprocessing
Every video should be pre-processed as follows:
* Extract frames and apply [MTCNN] to align faces
* Extract WAV files and calculate STFT


## Citation
If you use the code (only for research), please consider citing our paper:
```sh
@inproceedings{peng2018omg,
 author =  {Peng, Songyou and Zhang, Le and Ban, Yutong and Fang, Meng and Winkler, Stefan},
 title = {{A Deep Network for Arousal-Valence Emotion Prediction with Acoustic-Visual Cues}},
 year = {2018},
 booktitle = {arxiv},
}
```
Contact **Songyou Peng** [:envelope:](mailto:songyou.peng@adsc-create.edu.sg) for questions, comments and reporting bugs.


[here]: <https://arxiv.org/abs/1805.00638>
[MTCNN]: <https://arxiv.org/abs/1604.02878>
[PyTorch]: <http://pytorch.org/>
[torchvision]: <http://pytorch.org/docs/master/torchvision/#module-torchvision>
[NumPy]: <http://www.numpy.org/>
[scikit-image]: <http://scikit-image.org/>
[SphereFace (PyTorch)]: <https://github.com/clcarwin/sphereface_pytorch>
[OMG Emotion Challenge 2018]: <https://www2.informatik.uni-hamburg.de/wtm/OMG-EmotionChallenge>
[Songyou Peng]: <https://pengsongyou.github.io>
[Le Zhang]: <https://sites.google.com/site/zhangleuestc/home>
[Yutong Ban]: <https://team.inria.fr/perception/team-members/yutong-ban/>
[Meng Fang]: <https://people.eng.unimelb.edu.au/mengf1/>
[Stefan Winkler]: <https://stefan.winkler.site/>
