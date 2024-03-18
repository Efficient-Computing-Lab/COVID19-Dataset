# COVID19-XRay-Dataset
Chest X-Ray Images of COVID-19, Pneumonia (Bacterial) and Normal incidents


## Dataset

The dataset contains chest X-Ray images from patients with:
-  confirmed COVID-19 disease
-  common bacterial pneumonia 
-  normal incidents (no infections) 

```
chest_xray_dataset/
├── test
│   ├── covid [30 samples]
│   ├── normal [30 samples]
│   └── pneumonia [30 samples]
└── train
    ├── covid [112 samples]
    ├── normal [112 samples]
    └── pneumonia [112 samples]

8 directories, 426 files
```

## Dataset Source

The dataset combines two different publicly available datasets:

- [COVID-19 image data collection](https://github.com/ieee8023/covid-chestxray-dataset)
- [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)


## Cite Us 

[COVID-19 detection from chest X-Ray images using Deep Learning and Convolutional Neural Networks](https://dl.acm.org/doi/10.1145/3411408.3411416)
     

    @inproceedings{makris2020covid,
    title={COVID-19 detection from chest X-Ray images using Deep Learning and Convolutional Neural Networks},
    author={Makris, Antonios and Kontopoulos, Ioannis and Tserpes, Konstantinos},
    booktitle={11th Hellenic Conference on Artificial Intelligence},
    pages={60--66},
    year={2020}
    }


