# **Convolution Operations with Different Parameters**  

## **Overview**  
This project demonstrates **2D convolution** using **NumPy** and **TensorFlow/Keras** on a **5×5 input matrix** with a **3×3 kernel**, testing different **stride and padding configurations**.  

## **Dataset**  
The input matrix and kernel are **manually defined** in the script. No external datasets are used.  

## **Code Flow**  
1. **Defining the Input Matrix and Kernel:**  
   - A **5×5 matrix** representing the input.  
   - A **3×3 kernel** for convolution operations.  
2. **Performing Convolution:**  
   - Using **NumPy** for manual convolution.  
   - Using **TensorFlow/Keras** for optimized convolution.  
3. **Applying Different Stride and Padding Values:**  
   - **Stride = 1, Padding = ‘VALID’**  
   - **Stride = 1, Padding = ‘SAME’**  
   - **Stride = 2, Padding = ‘VALID’**  
   - **Stride = 2, Padding = ‘SAME’**  
4. **Printing the Output Feature Maps** for each configuration.  

## **Installation & Requirements**  
### **Running on Google Colab (Pre-installed TensorFlow):**  
- No additional installation required.  

### **Running on a Local System:**  
```sh
pip install tensorflow numpy
```

## **Running the Script**  
To execute the script, run the following command in your terminal or Colab:  
```sh
python question_2.py
```

## **Output**  
- Displays the **feature maps** for each **stride and padding** configuration.  
- **NumPy and TensorFlow outputs** are compared for correctness.  

📌 **Note:** Open the **question_2.ipynb** notebook to view the **executed output**.  
📍 **Path:** `Question_2_Convolution_Operations/question_2.ipynb`  

## **Observations**  
1. **Stride & Padding Impact:**  
   - **Smaller stride = larger output**, **larger stride = reduced output size**.  
   - **Padding 'SAME' preserves size**, while **'VALID' reduces it**.  
2. **NumPy vs TensorFlow:**  
   - **NumPy manually extracts regions** and performs element-wise multiplication.  
   - **TensorFlow optimizes convolution** for deep learning applications.  

## **Remarks**  
- The code is **well-structured** and **properly commented**.  
- Use **`Question_2_Convolution_Operations/question_2.ipynb`** to view the **executed code in Google Colab**.  
- **Attaching `question_2.py` script for reference.**  

## **Contact**  
**Name:** Harshith Reddy Gundra  
**Email:** hxg07240@ucmo.edu
**Student-ID:** 700780724

📍 **Code Path:** `Question_2_Convolution_Operations/question_2.ipynb`  
