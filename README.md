# MSD_task
Resources for the paper "Morpheme Sense Disambiguation: A New Task Aiming for Understanding the Language at Character Level" (LREC-COLING 2024)

# general description

Our MorDis resource for Chinese MSD includes one morpheme inventory (**MorInv**) and two morpheme annotated datasets (**MorTxt** and **MorWrd**) for in-text and in-word MSD.

Considering the demands of research, the data for MorDis originates from the authoritative Chinese Contemporary Dictionary (CCD). To respect intellectual property rights and to better cater to computational applications, we have condensed the relevant semantic space to some extent, as well as largely revised and optimized the morpheme definitions.

Here we have open-sourced a subset of this resource, encompassing 7,930 commonly used morphemes from the most frequently used 3,000 characters in Chinese. This includes 7,930 entries from MorInv, 22,800 entries from MorTxt, and 85,095 entries from MorWrd. As a result, the experimental results in the paper may be slightly affected during replication.

These sampled resources are uploaded to `data/`. The file structure is as follows:

- `data/`: data files
  - `MorInv.txt`: Data for the morpheme inventory
  - `MorTxt/`: dataset for in-text MSD
    - `train.csv`
    - `valid.csv`
    - `test.csv`
  - `MorWrd/`: dataset for in-word MSD
    - `train.csv`
    - `valid.csv`
    - `test.csv`

# Data analysis
The coverage of the released subset is as follows:
|Dataset|#Entry|#Character|#Morpheme|
|:----|:----|:----|:----|
|**MorInv**|7930|3000|7930|
|**MorTxt**|22800|2463|6767|
|**MorWrd**|85095|2848|7384|

# Data format


## More Resources

For more work and resources related to the Chinese Object-Oriented Lexicon (COOL), Peking University, please refer to [this repository](https://github.com/COOLPKU) (to be released in the near future).


