# **Convolution Operations and Pooling Demonstration**  

## **Overview**  
This project demonstrates **edge detection using the Sobel filter** and **2D Max & Average Pooling** using **NumPy** and **TensorFlow/Keras**.  

## **Task 1: Sobel Filter for Edge Detection**  
### **Description**  
- Applies **Sobel X and Sobel Y filters** to detect **horizontal and vertical edges**.  
- Computes the **gradient magnitude** for complete edge representation.  
- Uses **convolution operation in TensorFlow/Keras** to perform filtering.  

### **Code Flow**  
1. **Load and preprocess the image** (convert to grayscale and normalize).  
2. **Define Sobel X and Sobel Y filters** for edge detection.  
3. **Apply convolution using TensorFlow/Keras** to extract edge features.  
4. **Compute gradient magnitude** to combine horizontal & vertical edges.  
5. **Display the original image and processed edge-detected images**.  

## **Task 2: Max Pooling and Average Pooling Demonstration**  
### **Description**  
- Generates a **random 4×4 matrix** as input.  
- Applies **2×2 Max Pooling** and **2×2 Average Pooling**.  
- Prints the **original, max-pooled, and average-pooled matrices**.  

### **Code Flow**  
1. **Generating a Random 4×4 Matrix:**  
   - A **4×4 matrix** with random values is created using NumPy.  
2. **Applying Pooling Operations:**  
   - **2×2 Max Pooling** to retain maximum values.  
   - **2×2 Average Pooling** to compute the average values.  
3. **Printing Results:**  
   - The **original matrix**, **max-pooled matrix**, and **average-pooled matrix** are displayed.  

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
python question_3.py      
```

## **Output**  
- **Task 1 (Sobel Filter):** Displays **original image, Sobel X, Sobel Y, and gradient magnitude**.  
- **Task 2 (Pooling):** Displays the **original 4×4 matrix, max-pooled 2×2 matrix, and average-pooled 2×2 matrix**.  

📌 **Note:** Open the **question_3.ipynb**  notebooks to view the **executed output**.  
📍 **Path:**  
- `MaxAvgPooling/question_3.ipynb`  

## **Observations**  
1. **Sobel Filter Effect:**  
   - Highlights **edges** in an image using convolution filters.  
   - The **gradient magnitude** combines horizontal & vertical edges.  
2. **Max Pooling Effect:**  
   - Selects the **largest value** from each 2×2 region, preserving key features.  
3. **Average Pooling Effect:**  
   - Computes the **average of each 2×2 region**, leading to a smoother output.  

## **Remarks**  
- The code is **well-structured** and **properly commented**.  
- Use **`MaxAvgPooling/question_3.ipynb`** to view the executed code in Google Colab.  
- **Attaching `question_3.py` scripts for reference.**  

## **Contact**  
**Name:** Harshith Reddy Gundra  
**Email:** hxg07240@ucmo.edu  
**Student-ID:** 700780724  

📍 **Code Paths:**  
- `MaxAvgPooling/question_3.ipynb`
