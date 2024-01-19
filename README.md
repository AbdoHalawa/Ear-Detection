<h1>Ear Recognition Using Image Processing And Machine Learning Project</h1>

<h3>Abstract</h3>
<p>This project aims to develop a robust ear recognition system utilizing advanced image processing techniques and machine learning algorithms. The human ear's intricate shape, earlobe structure, and the complex pattern of ridges and furrows on its surface provide a rich source of biometric data. The methodology involves preprocessing steps like resizing, normalizing, applying Gaussian blur, and using the Sobel operator for edge detection. The core of the machine learning component employs a Support Vector Machine (SVM) trained on the number of white pixels in the Sobel's output image.</p>

<h3>Methodolgy</h3>
<p>1- Loading the Image: Read and load the image data.

   
   2- Converting to Grayscale: Convert the loaded image to grayscale for simplified processing. 

   
   3- Resizing: Standardize the image size to 200 pixels in both height and width. 

   
   4- Normalizing: Standardize pixel values to a common range (0 to 1) for consistent machine learning performance. 

   
   5- Smoothing with Gaussian Blur: Apply Gaussian blur to reduce noise and enhance features.

   
   6- Edge Detection with Sobel Operator: Use the Sobel operator to emphasize rapid changes in intensity, highlighting edges and contours.

   
   7- Calculate Magnitude of Gradients: Compute the magnitude of gradients based on Sobel results, representing the strength of edges in the image.

   
   8- Support Vector Machine (SVM): Implement SVM for classification, trained using the number of white pixels in the Sobel's output image.

   
   9- Model Evaluation: Evaluate the trained SVM model using a separate set of images, measuring accuracy, precision, recall, and F1 score.</p>

<h3>Results</h3>
<p>
The project achieves promising results, with an accuracy of 85% for ear recognition involving two people, 75% for four people, and 60% for five people, showcasing the effectiveness of the proposed methodology.

Feel free to explore the project, contribute, and enhance the field of ear recognition in the ever-evolving landscape of biometrics and image processing.</p>
