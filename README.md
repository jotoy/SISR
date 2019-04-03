# Unsupervised learning for blind single image super-resolution
## Some experiment results on real-world LR image SR:

As shown in Figure 1, our model can generate high-resolution image with less artifacts and more details.
![Cover](result/cover.png)
<p align="center">Figure 1</p>

We have evaluated our approach on 400 real-world LR images. 
Figure 2 shows the comparison results for six (more detailed comparison can be found in the supplementary material): chip (244 × 200), cat (429 × 380), comic (358 × 578), flower (334 × 490), store (440 × 430) and building (440 × 430). Image cat, comic, flower, store and building are stored in JPEG format, unknown quantization-related distortions (e.g., block artifacts) are inevitable. 
![Cover](result/eval_on_real_LR_1.png)
<p align="center">Figure 2</p>

## Citation
Please refer to the following if this repository is useful for your research.

## Bibtex:
```
@misc{zhao2018unsupervised,
    title={Unsupervised Degradation Learning for Single Image Super-Resolution},
    author={Tianyu Zhao and Wenqi Ren and Changqing Zhang and Dongwei Ren and Qinghua Hu},
    year={2018},
    eprint={1812.04240},
    archivePrefix={arXiv},
    primaryClass={cs.CV}
}
```
