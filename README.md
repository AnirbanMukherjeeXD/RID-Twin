# RID-Twin: An end-to-end pipeline for automatic face de-identification in videos

**Authors:**  
Anirban Mukherjee, Monjoy Narayan Choudhury, Dinesh Babu Jayagopi

📄 **Paper:** [arXiv:2403.10058](https://arxiv.org/abs/2403.10058)

---

This repository accompanies our research work titled "RID-Twin: Decoupling Identity from Motion for Face De-identification in Videos". It is a novel pipeline for automatic face de-identification in videos. It leverages state-of-the-art generative models and explicitly decouples identity from motion to preserve realism, temporal coherence, and non-identifiable features — key aspects often overlooked in prior approaches.

We evaluate RID-Twin on the VoxCeleb2 dataset and a custom behavioral dataset, addressing important gaps in current benchmarks.

---

## Code Release

The code for this project is **not yet publicly released**. 
Since our approach is based on existing open-source tools (which was an important criterion for our work), the pipeline can be replicated using the following dependencies:

- [StableDiffusion](https://huggingface.co/stabilityai/stable-diffusion-2-inpainting)
- [SAFA](https://github.com/Qiulin-W/SAFA)
- [Mediapipe](https://github.com/google/mediapipe)
- [BLIP2](https://github.com/salesforce/blip2)

---

## 📚 Citation

If you find this work helpful, please cite our paper:

```
@article{mukherjee2024rid,
  title={RID-TWIN: An end-to-end pipeline for automatic face de-identification in videos},
  author={Mukherjee, Anirban and Choudhury, Monjoy Narayan and Jayagopi, Dinesh Babu},
  journal={arXiv preprint arXiv:2403.10058},
  year={2024}
}

```

---

## 📬 Contact

For questions or collaborations, please reach out to [your.email@example.com].

