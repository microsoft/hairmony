# Hairmony

This repo accompanies the paper [Hairmony: Fairness-aware hairstyle classification](https://aka.ms/hairmony) which appeared at SIGGRAPH Asia 2024.
The repo includes details of the synthetic training dataset, real evaluation dataset and taxonomy definition.

## Taxonomy Definition

In the paper we introduce a taxonomy for hairstyle characterization aiming to satisfy the following:

- *Completeness*. All human hairstyles are captured to some degree of accuracy.
- *Fairness*. Differences (inaccuracy) between an actual hairstyle and the taxonomic description are similar across all demographics.
- *Granularity*. The categories are granular enough to distinguish between the majority of hairstyles.
- *Simplicity of use*. Diverse users (researchers, groom artists, users of avatars  etc.) can all understand the taxonomy.
- *Consistency*. A single hairstyle is described by a unique combination of attributes.
- *Objectivity*. The language refers to physical attributes rather than cultural references and is unambiguous.
- *Extensibility*. Allowing diverse communities to contribute to continuous taxonomy improvements.

A complete definition of the taxonomy can be found in the [taxonomy](/taxonomy/) folder.

## Synthetic Training Dataset

We share the synthetic training images in a multi-part ZIP and taxonomy attribute and hairstyle labels as CSV files, with the `image_name` column corresponding to each image file name.

- Images
  - [Part 1](https://facesyntheticspubwedata.z6.web.core.windows.net/sga-2024-hairmony/dataset/images.z01)
  - [Part 2](https://facesyntheticspubwedata.z6.web.core.windows.net/sga-2024-hairmony/dataset/images.z02)
  - [Part 3](https://facesyntheticspubwedata.z6.web.core.windows.net/sga-2024-hairmony/dataset/images.z03)
  - [Part 4](https://facesyntheticspubwedata.z6.web.core.windows.net/sga-2024-hairmony/dataset/images.z04)
  - [Part 5](https://facesyntheticspubwedata.z6.web.core.windows.net/sga-2024-hairmony/dataset/images.zip)
- [Taxonomy Attribute Labels](https://facesyntheticspubwedata.z6.web.core.windows.net/sga-2024-hairmony/sx_taxonomy.csv)
- [Hairstyle Labels](https://facesyntheticspubwedata.z6.web.core.windows.net/sga-2024-hairmony/image_hairstyle_labels.csv)

## Real Evaluation Dataset

We share labels for a subset of [FairFace](https://github.com/joojs/fairface).

- You will need to obtain a copy of the [FairFace](https://github.com/joojs/fairface) dataset.
- [Hair Taxonomy Labels](https://facesyntheticspubwedata.z6.web.core.windows.net/sga-2024-hairmony/fairface_taxonomy.csv)

## Disclaimer

We would like to acknowledge our dataset will not be perfect, both in terms of label accuracy and definitions of labels. We have outlined our method in the paper which is our best effort to achieve the aims set out in "Taxonomy definition". We fully expect the hair taxonomy and labels provided to be a useful starting point for future work and to evolve.

## Citation

If you use the taxonomy or datasets in your research, please cite the following [paper](https://aka.ms/hairmony):

```bibtex
@inproceedings{meishvili2024hairmony,
  title={Hairmony: Fairness-aware hairstyle classification},
  author={Meishvili, Givi and Clemoes, James and Hewitt, Charlie and Hosenie, Zafiirah and Xian, Xiao and de La Gorce, Martin and Takacs, Tibor and Baltru\v{s}aitis, Tadas and Criminisi, Antonio and McRae, Chyna and Jablonski, Nina and Wilczkowiak, Marta},
  booktitle={SIGGRAPH Asia 2024 Conference Papers (SA Conference Papers '24), December 3-6, Tokyo, Japan},
  year={2024},
}
```
