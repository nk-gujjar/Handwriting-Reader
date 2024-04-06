# Handwriting Recognition System


## Configuration
General configuration can be found in config.py

CNN-specific architecture configuration can be found in cnn.py

## Training
```
python train.py
```
This will generate a text log file and a Tensorflow summary.

<img src="https://github.com/0x454447415244/HandwritingRecognitionSystem/blob/master/TensorBoard.png" width="100%">

## Decoding
```
python test.py
```
This will generate, for each image, the line transcription. The output will be written to decoded.txt by default.

```
python compute_probs.py
```
This will generate, for each image, the posterior probabilities at each timestep. Files will be stored in Probs by default.

## Dependencies
- Tensorflow
- OpenCV-Python

## Contributions
Feel free to send your pull request or open issues.

