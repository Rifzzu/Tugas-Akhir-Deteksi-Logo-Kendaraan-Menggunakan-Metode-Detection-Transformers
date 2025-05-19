# Tugas Akhir - "Deteksi Logo Kendaraan Menggunakan Metode Detection Transformers"
[![Huggingface](https://camo.githubusercontent.com/b0242aba08cbaf9670cb3f59bb946606c709c80409bf20141a01ded0f889d0b0/68747470733a2f2f68756767696e67666163652e636f2f64617461736574732f68756767696e67666163652f646f63756d656e746174696f6e2d696d616765732f7261772f6d61696e2f7472616e73666f726d6572732d6c6f676f2d6461726b2e737667)](https://huggingface.co/facebook/detr-resnet-50)

[![Python](https://badges.aleen42.com/src/python.svg)](https://www.python.org/)

Diajukan untuk memenuhi salah satu syarat memperoleh gelar sarjana 
dari Program Studi S1 Informatika
Fakultas Informatika
Universitas Telkom

Nama : Rifky Fahrizal Ubaidillah
NIM : 1301204054

## Konten
Notebook ini merupakan salah satu dari beberapa eksperimen pada training model DETR. Konfigurasi yang dilakukan berfokus pada perubahan nilai *Gradient CLip Validation* dan *Accumulate Gradient Batches*. Pengujian ini meliputi beberapa tahapan yaitu:
- Import library
- Training model
- Inferensi citra
- Evaluasi model

Referensi:
| Judul | Link |
| ------ | ------ |
| Meta Research - DE⫶TR: End-to-End Object Detection with Transformers | [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/facebookresearch/detr) |
| Roboflow - How to Train DETR with 🤗 Transformers on a Custom Dataset | [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/roboflow/notebooks/blob/main/notebooks/train-huggingface-detr-on-custom-dataset.ipynb) |
| NielsRogge - Fine-tuning DETR on a custom dataset for object detection | [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/NielsRogge/Transformers-Tutorials/blob/master/DETR/Fine_tuning_DetrForObjectDetection_on_custom_dataset_(balloon).ipynb) |
| Adham Mohamed - Object-Detection-Interpretation-for-Advanced-Models | [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/adhammohamed1/Object-Detection-Interpretation-for-Advanced-Models/blob/main/detr.ipynb) |

Sumber Tambahan :
| Judul | Link |
| ------ | ------ |
| Umar Farooq - Vehicle Logos (VL)-10  | https://www.kaggle.com/datasets/mufarooqq/vl-10/data |
| Alberto1404 - Prepare dataset from YOLO format to COCO for DETR | https://discuss.huggingface.co/t/prepare-dataset-from-yolo-format-to-coco-for-detr/34894/2 |
