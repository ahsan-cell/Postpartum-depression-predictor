# Postpartum Depression Predictor  

This project leverages machine learning to accurately predict postpartum depression (PPD) based on responses to a brief questionnaire. Early diagnosis of PPD is critical for providing timely intervention, improving outcomes for affected women, and supporting their families.  

## Dataset  
The dataset consists of 1503 records collected from a medical hospital through a questionnaire administered via a Google Form. The questionnaire includes ten questions that gather information about symptoms, demographics, and other relevant factors associated with postpartum depression.  

## Machine Learning Model  
A neural network was designed and trained to predict the likelihood of postpartum depression. The architecture of the model is as follows:  

- **Input Layer**: 9 neurons  
- **Hidden Layers**:  
  - Layer 1: 81 neurons, activation function = ReLU  
  - Layer 2: 64 neurons, activation function = ReLU  
  - Layer 3: 64 neurons, activation function = ReLU  
  - Layer 4: 16 neurons, activation function = ReLU  
- **Output Layer**: 1 neuron, activation function = Sigmoid  

### Training Details  
- **Batch Size**: 32  
- **Epochs**: 20  
- **Loss Function**: Binary Cross-Entropy  
- **Optimizer**: Adam  

## Features  
1. Predicts postpartum depression using a structured questionnaire with high accuracy.  
2. Aims to assist healthcare providers in identifying high-risk cases early.  
3. Employs a neural network model optimized for performance on a small, focused dataset.  

## Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/PostpartumDepressionPredictor.git
   cd PostpartumDepressionPredictor
