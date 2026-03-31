# russian-texts-vlm
Russian handwritten text recognition using picture preprocessing and а quantized Qwen 3 8B VLM model.

This repository contains a dataset of five picures of handwritten texts in Russian. All of the texts were written and photographed by me. Un purpose, I tried to make the texts less readable by adding various artefacts to them.

The attached notebook offers picture preprocessing functions and texts scanning using a quantized Qwen/Qwen3-VL-8B-Instruct model. In the end of the notebook, the model is evaluated using the Character Error Rate (CER) metric.
