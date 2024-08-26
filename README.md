## Unsupervised Curriculum Learning (UCL) for SeaGrass Detection
### Overview
This repository contains the implementation of the Unsupervised Curriculum Learning (UCL) framework for detecting sea grass from underwater images. UCL is an unsupervised learning approach designed to improve the detection performance by gradually increasing the complexity of the learning tasks.

This project utilizes the publicly available DeepSeaGrass dataset to train and evaluate the model.

### Features
* Unsupervised Learning: Leverages UCL to structure the learning process without needing labeled data.
* Curriculum Learning: Gradually increases the difficulty of the learning tasks to improve model robustness.
* DeepSeaGrass Dataset: Uses a real-world dataset containing underwater images for seagrass detection.

### Dataset
CSIRO provides the [DeepSeaGrass dataset](https://data.csiro.au/collection/csiro:47653v1?redirected=true) and contains a comprehensive set of underwater images specifically designed for sea grass detection. The dataset can be accessed and downloaded from [this link](https://data.csiro.au/collection/csiro:47653v1?redirected=true) .

### Installation
To get started with this project, clone the repository and install the required dependencies:
```
git clone https://github.com/nabid69/Unsupervised-Curriculum-Learning---UCL.git
cd Unsupervised-Curriculum-Learning---UCL
pip install -r requirements.txt
```

### Contributing
Contributions are welcome! Please open an issue or submit a pull request with your improvements or bug fixes.

### Acknowledgments
This project utilizes the DeepSeaGrass dataset, which is provided by CSIRO. We are grateful for their contribution to the research community.
