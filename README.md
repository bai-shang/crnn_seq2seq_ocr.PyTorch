# crnn_seq2seq_ocr.Pytorch

This software implements the Convolutional Recurrent Neural Network (CRNN), a combination of CNN, Sequence to sequence and Attention for image-based sequence recognition tasks, such as scene text recognition and OCR.

# Dependencies
All dependencies should be installed are as follow: 
* Python3.5
* Pytorch
* opencv-python
* numpy
* Pillow

Required packages can be installed with
```bash
pip3 install -r requirements.txt
```    

# Run demo

Asume your current work directory is "crnn_seq2seq_ocr.Pytorch"：  

```bash
python3 inference.py --img_path ./data/test_img/20439171_260546633.jpg \
    --encoder model/pretrained/encoder.pth --decoder model/pretrained/decoder.pth
```

Result is:
![20439171_260546633.jpg](https://github.com/bai-shang/crnn_seq2seq_ocr.Pytorch/blob/master/data/test_img/20439171_260546633.jpg?raw=true)

# Train a new model
