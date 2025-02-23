# **AlexNet and ResNet Implementation**  

## **Overview**  
This project demonstrates the implementation of **AlexNet** and **ResNet** using **TensorFlow/Keras** for deep learning applications. Each model is built separately following the correct architectures.  

## **Task 1: AlexNet Implementation**  
### **Description**  
- Implements the **AlexNet architecture** for image classification.  
- Uses **five convolutional layers**, followed by **fully connected layers**.  
- Includes **ReLU activations, max-pooling layers, and dropout layers** to enhance performance.  

### **Code Flow**  
1. **Define the AlexNet Model:**  
   - Five **Conv2D layers** for feature extraction.  
   - Three **MaxPooling layers** to reduce spatial dimensions.  
   - Two **Fully Connected layers** with **Dropout** to prevent overfitting.  
   - A **Softmax output layer** for classification.  
2. **Print the Model Summary:**  
   - Displays **layer-wise structure and parameter count**.  

## **Task 2: ResNet Implementation**  
### **Description**  
- Implements a **simple ResNet-like model** with residual blocks.  
- Uses **skip connections** to enhance gradient flow and prevent vanishing gradients.  

### **Code Flow**  
1. **Define the Residual Block:**  
   - Two **Conv2D layers** with **ReLU activation**.  
   - A **skip connection** that adds the input tensor to the output.  
2. **Create the ResNet Model:**  
   - Initial **Conv2D layer (7×7 kernel, stride 2)** for feature extraction.  
   - Two **residual blocks** applying skip connections.  
   - **Flatten and Dense layers** for classification with a **Softmax output layer**.  
3. **Print the Model Summary:**  
   - Displays **layer-wise structure and parameter count**.  

## **Installation & Requirements**  
### **Running on Google Colab (Pre-installed TensorFlow):**  
- No additional installation required.  

### **Running on a Local System:**  
```sh  
pip install tensorflow numpy  
```

## **Running the Scripts**  
To execute the scripts, run the following commands in your terminal or Colab:  
```sh  
python question_4_AlexNet.py   # Runs AlexNet model  
python question_4_ResNet.py    # Runs ResNet model  
```

## **Output**  
- **Task 1 (AlexNet):** Prints **AlexNet model architecture and parameter count**.  
- **Task 2 (ResNet):** Prints **ResNet model architecture and parameter count**.  

📌 **Note:** Open the **question_4_AlexNet.ipynb** and **question_4_ResNet.ipynb** notebooks to view the **executed outputs**.  
📍 **Paths:**  
- `question_4_AlexNet_ResNet/question_4_AlexNet.ipynb`  
- `question_4_AlexNet_ResNet/question_4_ResNet.ipynb`  

## **Observations**  
1. **AlexNet Implementation:**  
   - **Uses deep convolutional layers** to extract detailed features.  
   - Includes **dropout layers** for better generalization.  
2. **ResNet Implementation:**  
   - Uses **residual blocks** to retain feature integrity.  
   - Skip connections **improve gradient flow** in deep networks.  

## **Remarks**  
- The code is **well-structured** and **properly commented**.  
- Use **`question_4_AlexNet_ResNet/question_4_AlexNet.ipynb`** and **`question_4_AlexNet_ResNet/question_4_ResNet.ipynb`** to view the executed code in Google Colab.  
- **Attaching `question_4_AlexNet.py` and `question_4_ResNet.py` scripts for reference.**  

## **Contact**  
**Name:** Harshith Reddy Gundra  
**Email:** hxg07240@ucmo.edu  
**Student-ID:** 700780724  

📍 **Code Paths:**  
- `question_4_AlexNet_ResNet/question_4_AlexNet.ipynb`  
- `question_4_AlexNet_ResNet/question_4_ResNet.ipynb`

