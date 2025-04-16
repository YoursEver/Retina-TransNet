# Retina-TransNet: A Gradient-Guided Few-Shot Retinal Vessel Segmentation Network

The source code for **Retina-TransNet (v1)**, published in the *IEEE Journal of Biomedical and Health Informatics (JBHI), 2023*, will be released soon.

---

## 🧠 Abstract

Due to the high labor cost of physicians, it is difficult to collect a rich amount of manually-labeled medical images for developing learning-based computer-aided diagnosis (CADx) systems or segmentation algorithms. To tackle this issue, we reshape the image segmentation task as an image-to-image (I2I) translation problem and propose a retinal vascular segmentation network, which can achieve good cross-domain generalizability even with a small amount of training data. We devise primarily two components to facilitate this I2I-based segmentation method. The first is the constraints provided by the proposed gradient-vector-flow (GVF) loss, and, the second is a two-stage Unet (2Unet) generator with a skip connection. This configuration makes 2Unet's first-stage play a role similar to conventional Unet, but forces 2Unet's second stage to learn to be a refinement module. Extensive experiments show that by re-casting retinal vessel segmentation as an image-to-image translation problem, our I2I translator-based segmentation subnetwork achieves better cross-domain generalizability than existing segmentation methods. Our model, trained on one dataset, e.g., DRIVE, can produce segmentation results stably on datasets of other domains, e.g., CHASE-DB1, STARE, HRF, and DIARETDB1, even in low-shot circumstances.

---

## 📄 Citation

If you find our work useful, please cite:

```bibtex
@article{shao2023retina,
  title={Retina-TransNet: A Gradient-Guided Few-Shot Retinal Vessel Segmentation Net},
  author={Shao, Hao-Chiang and Chen, Chih-Ying and Chang, Meng-Hsuan and Yu, Chih-Han and Lin, Chia-Wen and Yang, Ju-Wen},
  journal={IEEE Journal of Biomedical and Health Informatics},
  volume={27},
  number={10},
  pages={4902--4913},
  year={2023},
  publisher={IEEE}
}
