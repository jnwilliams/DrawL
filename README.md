Welcome to the official GitHub repository for **DrawL: Understanding the Effects of Non-Mainstream Dialects in Prompted
Image Generation** (arXiv: https://arxiv.org/abs/2405.05382). This repository hosts the dataset used in the research in order to provide easy access for replication, analysis, and further exploration.

About the Dataset

The DrawL dataset comprises a collection of contrastive prompts for image generation models in Mainstream American English (MAE) and African American English (AAE), e.g.,

| Mainstream American English                             | African American English                                     |
| ------------------------------------------------------- | ------------------------------------------------------------ |
| A closeup of a person. They put sunglasses on their cat | A closeup of a person. They done put sunglasses on their cat |

The dataset is divided into a set of  minimal, syntax-only changes to the MAE prompts that express grammatical constructions found AAE. Each prompt is labeled with the grammar rule used to construct the contrastive AAE prompt.

 This data may facilitate experiments in which one would like to investigate behavior changes of language models with respect to the dialect of the user. 

Repository Contents

    [prompts_by_gendered_subject]: This directory includes the full set of data, separated by the gender of the generated subject for the purposes of investigating intersectional effects of dialect and gender.

    [prompts_by_syntactic_construction]: This directory includes the multiple csv files for each grammar rule with the unedited, raw prompt, the baseline MAE prompt, and AAE counterfactual prompt.

    [datasheet]: The datasheet directory provides a README with detailed information about the dataset, including its composition, source, preprocessing steps, and potential applications. Refer to this file for a deeper understanding of the dataset's characteristics and guidelines for its usage.

Usage Guidelines

To utilize this dataset effectively, follow these guidelines:

    Download: Clone or download the repository to access the dataset files and related materials.

    Explore: Review the datasheet to understand the dataset's structure, attributes, and any preprocessing steps applied.

    Citation: If you use this dataset in your work, please cite it using the provided BibTeX citation below.

Citation

If you find this dataset useful and incorporate it into your research, please cite it as:

```
@misc{williams2024drawl,
      title={DrawL: Understanding the Effects of Non-Mainstream Dialects in Prompted Image Generation}, 
      author={Joshua N. Williams and Molly FitzMorris and Osman Aka and Sarah Laszlo},
      year={2024},
      eprint={2405.05382},
      archivePrefix={arXiv},
      primaryClass={cs.CY}
}
```

Contact

For any inquiries or feedback regarding the dataset or this repository, please contact jnwillia [at] cs [ dot] cmu [dot] edu.
