# Effects of MRI scanner manufacturers in classification tasks with deep learning models
The paper has been accepted for publication in Nature Scientific Reports (https://www.nature.com/articles/s41598-023-43715-5).  

```
@article{kushol2023effects,
  title={Effects of MRI scanner manufacturers in classification tasks with deep learning models},
  author={Kushol, Rafsanjany and Parnianpour, Pedram and Wilman, Alan H and Kalra, Sanjay and Yang, Yee-Hong},
  journal={Scientific Reports},
  volume={13},
  number={1},
  pages={16791},
  year={2023},
  publisher={Nature Publishing Group UK London}
}
```

## Abstract
Deep learning has become a leading subset of machine learning and has been successfully employed in diverse areas, ranging from natural language processing to medical image analysis. In medical imaging, researchers have progressively turned towards multi-center neuroimaging studies to address complex questions in neuroscience, leveraging larger sample sizes and aiming to enhance the accuracy of deep learning models. However, variations in image pixel/voxel characteristics can arise between centers due to factors including differences in magnetic resonance imaging scanners. Such variations create challenges, particularly inconsistent performance in machine learning-based approaches, often referred to as domain shift, where the trained models fail to achieve satisfactory or improved results when confronted with dissimilar test data. This study analyzes the performance of multiple disease classification tasks using multi-center MRI data obtained from three widely used scanner manufacturers (GE, Philips, and Siemens) across several deep learning-based networks. Furthermore, we investigate the efficacy of mitigating scanner vendor effects using ComBat-based harmonization techniques when applied to multi-center datasets of 3D structural MR images. Our experimental results reveal a substantial decline in classification performance when models trained on one type of scanner manufacturer are tested with data from different manufacturers. Moreover, despite applying ComBat-based harmonization, the harmonized images do not demonstrate any noticeable performance enhancement for disease classification tasks.

#### CALSNIC2 MRI Scanner Manufacturer Effects in 3D tSNE plot



https://user-images.githubusercontent.com/76894940/200472206-f14c7b39-bdb8-451a-9571-6e6c61f4f5fe.mp4



#### CALSNIC2 MRI Scanner Manufacturer Effects in 3D UMAP plot


https://user-images.githubusercontent.com/76894940/200472299-0f43b3d2-801c-4f3a-9d46-d1583043a3d9.mp4





#### ADNI2 MRI Scanner Manufacturer Effects in 3D tSNE plot



https://user-images.githubusercontent.com/76894940/200472425-ef41b1c1-1216-4423-927f-02dfeecf7278.mp4



#### ADNI2 MRI Scanner Manufacturer Effects in 3D UMAP plot



https://user-images.githubusercontent.com/76894940/200472523-c3c3f16b-dbe7-4d87-885a-2f680748a650.mp4





#### ADNI1 MRI Scanner Manufacturer Effects in 3D tSNE plot



https://user-images.githubusercontent.com/76894940/200472618-24ed18a4-1cf1-4b0b-be58-09c3ff495148.mp4



#### ADNI1 MRI Scanner Manufacturer Effects in 3D UMAP plot


https://user-images.githubusercontent.com/76894940/200472734-1397513b-e8f6-4fe2-bd52-f516cfb77e83.mp4


