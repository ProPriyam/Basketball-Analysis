### Analyze basketball shots and shooting pose using deep learning

All the data for the shooting pose analysis is calculated by implementing [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose). Please note that this is an implementation only for noncommercial research use only. Please read the [LICENSE](https://github.com/chonyy/AI-basketball-analysis/blob/master/LICENSE), which is exaclty same as the [CMU's OpenPose License](https://github.com/CMU-Perceptual-Computing-Lab/openpose/blob/master/LICENSE).

### Prerequisites

Before running the project, we have to install all the dependencies from requirements.txt

``` pip
pip install -r requirements.txt
```

GPU with proper CUDA setup is needed to run the video analysis

### Running

``` python
python app.py
```
