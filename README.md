# Batik Classification (Deep Learning CNN)
> A deep learning project for classifying batik according to its pattern (<i>motif</i>) using CNN VGG-16. Built for IF4073 Digital Image Processing course project.

## About Batik
Batik, Indonesia's traditional textile arts that has been recognized as a Masterpiece of Intangible Heritage of Humanity by UNESCO 2009. As a cultural icon, batik reflects the diversity of Indonesian culture through its patterns (<i>motif</i>) and colors that are unique to each region of its origin. Each colors and patterns have a deep philosophical meaning, depicting life values, beliefs, and local traditions. Batik motifs are diverse, some of which are Batik Parang, Batik Kawung, Batik Mega Mendung, Batik Ceplok, Batik Kraton, etc. ([Steelyana, 2012](https://doi.org/10.21512/bbr.v3i1.1288))

## Dataset
[Dataset](https://drive.google.com/file/d/1ldQpQgTFg41SNPgp2KnvpbHgQvk6KH4n/view?usp=sharing) used in this project is compiled from online public dataset:
1. [Batik Ceplok, Lereng, and Nitik Dataset](https://github.com/yohanesgultom/deep-learning-batik-classification) from Y. Gultom, A. M. Arymurthy, and R. J. Masikome (2018) 
2. [Batik Ceplok Dataset](https://www.kaggle.com/datasets/dionisiusdh/indonesian-batik-motifs?select=batik-ceplok) from D. D. Hermansyah (2021)
3. [Batik Kawung, Mega Mendung, Parang, and Truntum Dataset](https://github.com/arifnurrhmnn/Dataset-Motif-Batik) from arifnurrhmnn (2021)

This project's dataset detail:
| Class        	| Train size 	| Test size 	| Total 	 |
|--------------	|------------	|-----------	|-------	 |
| Ceplok       	| 157        	| 15        	| 172   	 |
| Kawung       	| 560        	| 140       	| 700   	 |
| Lereng       	| 51         	| 10        	| 61    	 |
| Mega mendung 	| 560        	| 150       	| 710   	 |
| Nitik        	| 107        	| 10        	| 117   	 |
| Parang       	| 560        	| 140       	| 700   	 |
| Truntum      	| 560        	| 150       	| 710   	 |
| <b>Total</b> 	| <b>2555</b>  	| <b>615</b>   	| <b>3170</b>|

## Requirements
1. Python 3.7 and above
2. See [requirements](https://github.com/arleenchr/batik-classification/blob/main/requirements.txt)

## Repository Structure
```
batik-classification
├── data
│   ├── test
│   |   ├── Ceplok
│   |   |   └── ...
│   |   ├── Kawung
│   |   |   └── ...
│   |   ├── Lereng
│   |   |   └── ...
│   |   ├── Megamendung
│   |   |   └── ...
│   |   ├── Nitik
│   |   |   └── ...
│   |   ├── Parang
│   |   |   └── ...
│   |   └── Truntum
│   |       └── ...
│   └── train
│       ├── Ceplok
│       |   └── ...
│       ├── Kawung
│       |   └── ...
│       ├── Lereng
│       |   └── ...
│       ├── Megamendung
│       |   └── ...
│       ├── Nitik
│       |   └── ...
│       ├── Parang
│       |   └── ...
│       └── Truntum
│           └── ...
├── docs
│   └── batik_classification_paper.pdf
├── models
│   ├── model.h5
│   └── model.weights.h5
├── .gitignore
├── batik_classification.ipynb
├── README.md
└── requirements.txt
```
