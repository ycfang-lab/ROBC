ROBC
====
This is a radical-level annotation oracle bone character dataset.

## Dataset
The image data of oracle bone character can be obtained by visiting www.baidu.com.

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

### OBC IDS
The Ideographic Description Sequence for Oracle bone characters is shown in [OBC_IDS]([http://github.com/kawabata/ids](https://github.com/ycfang-lab/ROBC/blob/main/OBC_IDS.json))
