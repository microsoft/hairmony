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

TODO summary and download instructions for synthetic dataset

## Real Evaluation Dataset

TODO summary and download instructions for real dataset

## Citation

If you use the taxonomy or datasets in your research, please cite the following [paper](TODO):

```bibtex
@inproceedings{meishvili2024hairmony,
  title={Hairmony: Fairness-aware hairstyle classification},
  author={Meishvili, Givi and Clemoes, James and Hewitt, Charlie and Hosenie, Zafiirah and Xian, Xiao and de La Gorce, Martin and Takacs, Tibor and Baltru\v{s}aitis, Tadas and Criminisi, Antonio and McRae, Chyna and Jablonski, Nina and Wilczkowiak, Marta},
  booktitle={Proceedings of SIGGRAPH Asia},
  year={2024}
}
```
