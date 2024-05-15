# MSD_task
Resources for the paper "Morpheme Sense Disambiguation: A New Task Aiming for Understanding the Language at Character Level" (LREC-COLING 2024)

# general description

Our MorDis resource for Chinese MSD includes one morpheme inventory (**MorInv**) and two morpheme annotated datasets (**MorTxt** and **MorWrd**) for in-text and in-word MSD.

Due to the restriction of intellectual property of the Chinese Contemporary Dictionary, we paraphrase the senses using ChatGPT and release a subset of MorDis covering 7930 frequently used morphemes of the 3000 most frequently used characters.
These sampled resources are uploaded to `data/`. The file structure is as follows:

- `data/`: data files
  - `MorInv.txt`
  - `MorTxt/`: dataset for in-text MSD
    - `train.csv`
    - `valid.csv`
    - `test.csv`
  - `MorWrd/`: dataset for in-word MSD
    - `train.csv`
    - `valid.csv`
    - `test.csv`




