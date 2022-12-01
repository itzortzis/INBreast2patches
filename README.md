# INBreast2patches

This tool can be used for extracting image patches from the original INBreast dataset, according to user configuration parameters.

Required libraries:

    os, cv2, numpy, pydicom, matplotlib, torch, random, tqdm, skimage

Required external tools:

    INBreast_XML_parser: (https://github.com/itzortzis/INBreast_XML_parser)


Files and description:
----------------------
```
INBreast2patches
│    README.md
│    LICENCE
│    INBreast2patches.ipynb # Test bed - notebook approach
│    INBreast2patches.py # Test bed - python approach
│
└─── utils
│    │   dataset_utils.py  # Utilities referring to the output dataset (patches)
│    │   inbreast_utils.py # Utilities referring to the input dataset (INBreast)
```

INBreast dataset:
-----------------
Inês C. Moreira, Igor Amaral, Inês Domingues, António Cardoso, Maria João Cardoso, Jaime S. Cardoso,
INbreast: Toward a Full-field Digital Mammographic Database,
Academic Radiology,
Volume 19, Issue 2,
2012,
Pages 236-248,
ISSN 1076-6332,
https://doi.org/10.1016/j.acra.2011.09.014.
(https://www.sciencedirect.com/science/article/pii/S107663321100451X)
