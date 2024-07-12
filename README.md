ROBC
====
This is a radical-level annotation oracle bone character dataset.

## Dataset
The image data of oracle bone character can be obtained by aceessing the [kaggle](https://www.kaggle.com/datasets/ycfanglab/radical-level-oracle-bone-character-dataset).

### The dataset directory is as follows：
```plaintext
imgs/
├── OBCID_num_character/ (fine-grained)
│   ├── train_1.png (OBC image)
│   └── train_2.png
└── OBCID_character/ (coarse-grained)
    ├── train_1.png (OBC image)
    └── train_2.png 
```
- OBCID: the ID of Oracle Bone Character
- num: the corresponding IDS among various glyphs of the OBCID 
- character: the corresponding modern Chinese character

## OBC IDS
The Ideographic Description Sequence for Oracle bone character is shown in [OBC_IDS](./OBC_IDS.json).
- 02FF0~02FFF: IDCs (Ideographic Description Characters) representing spatial structure and radical posture, the meaning of each one refers to the [Unicode character code charts](https://www.unicode.org/charts/PDF/U2FF0.pdf)
- 6****: the encoding of oracle bone character/radical is annotated based on the [oracle bone font library of Yinqi Wenyuan](https://jgw.aynu.edu.cn/home/down/index.html)
- others: characters and radicals that have not yet been included in the oracle bone font library are replaced with corresponding modern Chinese character unicode

## References and Acknowledgements
```
Awaiting
```
