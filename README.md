# Kaggle Notebooks
- Kaggle 컴피티션/데이터에 대한 문제해결 아카이브 입니다. 
- 모든 코드는 [Colab](https://colab.research.google.com/) 에서 작성되었습니다.

## Tabular Data
| Competition / Data                                                                      | Problem Type               | Notebook (colab)                                                                                            |
|-------------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------------------------------------------------------|
| [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)                                         | Binary Classification      | [Notebook](https://colab.research.google.com/drive/1okqZ7yFba9xVnke9Px3AapLunupCeMog?usp=sharing)      |
| [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) | Regression                 | [Notebook](https://colab.research.google.com/drive/1n9XYmcvefp6rSD-rH7uZqfw3eVQ_cnxh?usp=sharing)  |
| [Forest Cover Type Prediction](https://www.kaggle.com/c/forest-cover-type-prediction)          | Multi-class Classification | [Notebook](https://colab.research.google.com/drive/1Kgd6OOrRE7rXrl62HTu4PHtAED2d2zWJ?usp=sharing)  |
| [Bike Sharing Demand](https://www.kaggle.com/c/bike-sharing-demand)                 | Multi-output Regression    | [Notebook](https://colab.research.google.com/drive/1FihAHMXlpPxLwlpa-B261IcY1zisMrEL?usp=sharing) |
| [Prudential Life Insurance Assessment](https://www.kaggle.com/c/prudential-life-insurance-assessment)                 | Ordinal Classification    | [Notebook](https://colab.research.google.com/drive/1WPxPqsUsWxgZcmeHRsXn-jYR6aJLdegO?usp=sharing) |

## Recommendation

| Competition / Data                                                                                       | Problem Type          | Notebook (colab) |
|----------------------------------------------------------------------------------------------------------|-----------------------|------------------|
| [MovieLens 100K](https://www.kaggle.com/prajitdatta/movielens-100k-dataset)                            | Matrix Completion <br> (on explicit feedback)  | Matrix Factoriazation ([Paper](https://ieeexplore.ieee.org/abstract/document/5197422?casa_token=yU_a_jQk3FoAAAAA:1c80Grtze6IyXKSz81M4-znwmGs13dojvr6OhAqIcvkiWIYch2wD3Wu4wcJaE65agQgd9oe-) / [Notebook](https://colab.research.google.com/drive/1bFejhfvL_hAvyvJSAo2GuOwTYIdGO6pR?usp=sharing)) <br> SVD++ ([Paper](https://dl.acm.org/doi/abs/10.1145/1401890.1401944?casa_token=tZHDSBhztHEAAAAA:lkb_CQw_VKPJ8TIFmPc8Y7YDACAqltEn6guZzcpblnISX0vEiYIgBj3ynrTTgo_nJ0wl2XG8nHpk) / [Notebook](https://colab.research.google.com/drive/1bPy85bDJKUt_BdbK5N3TwOYvYiyZvE3w?usp=sharing)) <br> SVD++ Temporal Dynamics ([Paper](https://dl.acm.org/doi/abs/10.1145/1557019.1557072?casa_token=IEQ4ql25LJkAAAAA:YZdpt465lHuQoDn0aPUY6r6mb66oerR5WpyLxxl8b7_56FLZz1NZZGJTHYsiF0x-LC_i2Lpz2570) / [Notebook](https://colab.research.google.com/drive/1O0IqiSfG_KBWt3eQ_09_YcL-8kKCXnTN?usp=sharing)) <br> AutoRec ([Paper](https://dl.acm.org/doi/abs/10.1145/2740908.2742726?casa_token=-rsq4DNjwtMAAAAA:zAlU4S0GAAgtJedHACqn2_C5o5iMa4dpJ7d1EHaQF-fOoUhdSBgoycFw3p6YsiofMNJQ6H0mH_qE) / [Notebook](https://colab.research.google.com/drive/1r_50WEsS2s3DGbPW-4HQoUnXZd4KMyHB?usp=sharing)) <br> NeuralCF ([Paper](https://dl.acm.org/doi/abs/10.1145/3038912.3052569?casa_token=3GcImCEhOs4AAAAA:j_iBG70sZt9BcZnUkzhUBeA2whcjXSDQ7I2IY0K0ITtcnsfMBnxBTW0f210OotYghSDsYWKPUgAD) / [Notebook](https://colab.research.google.com/drive/1OFQ_yWmjNZScot-qxvkP-cYGI9sHHFtt?usp=sharing)) |
| [MovieLens 100K](https://www.kaggle.com/prajitdatta/movielens-100k-dataset)                            | Personalized Ranking prediction <br> (on implicit feedback)  | NeuralCF ([Paper](https://dl.acm.org/doi/abs/10.1145/3038912.3052569?casa_token=3GcImCEhOs4AAAAA:j_iBG70sZt9BcZnUkzhUBeA2whcjXSDQ7I2IY0K0ITtcnsfMBnxBTW0f210OotYghSDsYWKPUgAD) / [Notebook](https://colab.research.google.com/drive/1cYMOXcBmzL5wamnJfE6-3H-XoI-1NcQk?usp=sharing)) <br> Caser ([Paper](https://dl.acm.org/doi/abs/10.1145/3159652.3159656?casa_token=_hkVJ2pf35QAAAAA:UAI6ecH9FzUj6Z-HL4orIZyYMUF1zFN7UxDI5edgCog2eb7OxzEF5NEeJ8BFS6H1RAO9eBX7LqaE2V0) / [Notebook](https://colab.research.google.com/drive/12A645NnzWCwLYaYJlFQL6pAwUa7pWj22?usp=sharing)) |
| [Online Advertising](https://d2l.ai/chapter_recommender-systems/ctr.html)                            | Click Through Rate (CTR) Prediction <br> (on feature-rich interaction data)  | Factorization Machines ([Paper](https://ieeexplore.ieee.org/abstract/document/5694074/?casa_token=XfxWteIAUtYAAAAA:UlFIuG28xBkJG3TkZblX3rvcYfolq4wgkReklygGyhEq4fFD_ov8dyRLydDyvnWRdpkeLZYE) / [Notebook](https://colab.research.google.com/drive/1ld-5bX_8UZOj6l_LpXlZMan_G8NQx_5e?usp=sharing)) <br> DeepFM ([Paper](https://arxiv.org/abs/1703.04247) / [Notebook](https://colab.research.google.com/drive/1ctt8Vak0Uw_Nz7Ksj9RUcNvKts2qPaN3?usp=sharing)) |

## Image Data
| Competition / Data                                                                                          | Problem Type          | Notebook (colab) |
|----------------------------------------------------------------------------------------------------------|-----------------------|------------------|
| [Dog Breed Identification](https://www.kaggle.com/c/dog-breed-identification)                            | Classification        | [ResNet34_Pretrained.ipynb](https://colab.research.google.com/drive/1iNMV8kik9ue6sy8DPgG73zT7wO_pQKtB?usp=sharing) <br> [ResNet18_Scratch.ipynb](https://colab.research.google.com/drive/1d1jMyWEWMVLBvOOvU5AAhD69V9_uSZDF?usp=sharing) <br> [NiN_Scratch.ipynb](https://colab.research.google.com/drive/1X_MktEUblvBMyfZebMm88sEj0oQL3HEE?usp=sharing)|
| [Generative Dog Images](https://www.kaggle.com/competitions/generative-dog-images)                            | Generation        | [DCGAN.ipynb](https://colab.research.google.com/drive/1wnSNIV6uiL7r4prkPxs-yDMyDzaG3R7J?usp=sharing) <br> [DCGAN_Tune.ipynb](https://colab.research.google.com/drive/1RI04dr6EztTvhaGkgv4NNClfxRynN6dC?usp=sharing) | 
| [I’m Something of a Painter Myself](https://www.kaggle.com/c/gan-getting-started)                        | Style Transfer        | [Neural_Style_Transfer.ipynb](https://colab.research.google.com/drive/1FduBuKqs3ToSrnRekxcxUQfzkaHbJcBr?usp=sharing)                 |
| [PASCAL VOC 2012](https://www.kaggle.com/datasets/huanghanchina/pascal-voc-2012) | Semantic Segmentation | [FCN_ResNet18.ipynb](https://colab.research.google.com/drive/1C-o68TRZc8YThVyEWbLnEKn-G0_JgwK0?usp=sharing)                 |
| [Sartorius - Cell Instance Segmentation](https://www.kaggle.com/c/sartorius-cell-instance-segmentation)  | Instance Segmentation | [MaskRCNN.ipynb](https://colab.research.google.com/drive/1tTYRj-9Z-IXlXlLYe0EVPGEERtwYU29j?usp=sharing)                  |

## Sequential Data
| Competition / Data                                                                                          | Problem Type          | Notebook (colab) |
|----------------------------------------------------------------------------------------------------------|-----------------------|------------------|
| [Pump Sensor Data](https://www.kaggle.com/datasets/nphantawee/pump-sensor-data)                            | Multivariate Time-Series Anomaly Detection       | [LSTM_AutoEncoder.ipynb](https://colab.research.google.com/drive/1iOdhjbuNhE1nesQiY5ST6RCWlWao9MCz?usp=sharing)|
| [NASA Turbofan Jet Engine Data Set](https://www.kaggle.com/datasets/behrad3d/nasa-cmaps) | Multivariate Time-Series Scalar(Remaining Useful Life) Forecasting | [LSTM.ipynb](https://colab.research.google.com/drive/1BfLSPNT2reXh1M1KztdFwOa-JYURpDDl?usp=sharing) |
