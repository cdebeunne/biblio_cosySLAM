# Cosy Pose

- Deep Im project Link : https://rse-lab.cs.washington.edu/projects/deepim/

<details> <summary> More details here </summary> 

- Estimates recursively the pose with a CNN that returns the transformation between a rendered image and the real input
- Uses a flowNet backbone and 2 dense layer of 256 neuronnes that returns a translation vector and a quaternion

</details>

- Cosy-pose project link : https://www.di.ens.fr/willow/research/cosypose/

<details> <summary> More details here </summary> 

- 3 step algorithm: first transformation estimate with an improved DeepIm-like CNN, an outlier rejection with RANSAC and a global scenen refinement with bundle adjustment
- improved deep Im with: a new transformation parametrization / a different backbone : EfficientNet / a new loss function / no optical flow reconstruction while training / data augmentation

</details>


- page of the BOP challenge : https://bop.felk.cvut.cz/challenges/bop-challenge-2020/#identifyingsymmetries
- For robotic application MaskRCNN is used for object detection (HE 2018) https://arxiv.org/pdf/1703.06870.pdf