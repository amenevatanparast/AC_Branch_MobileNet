# AC_Branch_MobileNet  

AC_Branch_MobileNet is a novel convolutional neural network designed for classifying fetal brain planes in ultrasound images. This lightweight and efficient hybrid branch network incorporates an attention module, significantly enhancing the accuracy of identifying trans-ventricular, trans-thalamic, and trans-cerebellar brain planes. The model balances computational efficiency with high accuracy, making it ideal for both clinical and research applications in prenatal diagnostics.  

## Features  
- **High Accuracy**: Achieves 95.11% accuracy on a public fetal ultrasound dataset.  
- **Lightweight Design**: Combines MobileNetV2 architecture with a hybrid branch structure, reducing the parameter count while maintaining robust performance.  
- **Preprocessing Enhancement**: Uses Maximum Local Variation-Based Unsharp Masking (MLVUM) to improve ultrasound image quality by reducing speckle noise and enhancing contrast.  
- **Attention Module**: Focuses on critical features, improving interpretability and classification performance.  
- **Portable and Efficient**: Suitable for integration into various healthcare devices, enabling broader access to advanced diagnostic tools.  

## About  

Prenatal screening is crucial for identifying abnormalities in fetal brain development. Traditional methods heavily rely on expert sonographers to identify standard brain planes in ultrasound images, a process prone to variability and subjectivity. AC_Branch_MobileNet addresses these challenges by providing a robust automated solution for fetal brain plane classification.  

The network leverages MobileNetV2 as its backbone and enhances feature extraction with an attention module and a branch structure. This innovative design allows the model to effectively capture multi-level features without significantly increasing its depth, offering a balanced approach to efficiency and accuracy. The system's performance has been validated on a public dataset, showing superior results compared to existing methods while maintaining a lower computational overhead.  

## Results  
- **Accuracy**: 95.11%  
- **Precision**: 94.62%  
- **Recall**: 94.39%  
- **F1-Score**: 94.50%  

## Getting Started  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/amenevatanparast/AC_Branch_MobileNet.git  
   cd AC_Branch_MobileNet  
   ```  

2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  


## Dataset  
The dataset used for this project is publicly available [here](https://zenodo.org/records/3904280). Ensure to preprocess the data and apply augmentation techniques as outlined in the research article.  

## Citation  
If you use this work in your research, please cite the following:  
```
@article{Vatanparast2025AC_Branch_MobileNet,
  title={AC_Branch_MobileNet: An effective hybrid branch network for plane classification in fetal brain ultrasound image},
  author={Amene Vatanparast, Mansoor Fateh, Hoda Mashayekhi},
  journal={Your Journal Name},
  year={2025},
  volume={XX},
  pages={YY-ZZ}
}
```  

## License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

## Contact  
For questions or collaborations, feel free to reach out to:  
- Mansoor Fateh: [mansoor_fateh@shahroodut.ac.ir](mailto:mansoor_fateh@shahroodut.ac.ir)  
- Amene Vatanparast: [amene.vatanparast@gmail.com](mailto:amene.vatanparast@gmail.com)  
