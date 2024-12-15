# Brown-Exponential-Smoothing
Brown Exponential Smoothing implementation in PowerBI by using DAX

The Brownian model, also known as the random walk or Wiener process, is a statistical model used to represent random, unpredictable changes over time. When combined with exponential smoothing, it provides a robust method for forecasting time series data by applying diminishing weights to past observations. This approach allows for more recent data points to have a greater influence on the prediction, making it suitable for dynamic systems where trends and patterns evolve rapidly. Exponential smoothing helps to reduce noise and highlight underlying trends, offering a more accurate and responsive forecasting model.

![image](https://github.com/user-attachments/assets/b8ba2895-6054-4762-b65f-d963754eb805)

Alpha (α) is a parameter that controls the weighting of recent observations in the smoothing process:

A higher value of 𝛼 (close to 1) places more weight on recent data, making the model highly responsive to changes but also more sensitive to noise.
A lower value of 𝛼 (closer to 0) places more weight on past data, creating a smoother trend that reacts more slowly to changes.
By selecting an appropriate 𝛼, the model can be fine-tuned to balance responsiveness and stability, making it effective for various forecasting scenarios.

![image](https://github.com/user-attachments/assets/d832f777-12b3-4e35-adc4-a2da2c16f2f9)

![image](https://github.com/user-attachments/assets/0e8bcc81-fa5a-423a-87ee-e5aa13c272e0)

![image](https://github.com/user-attachments/assets/e7bb1bfe-d0e5-4812-869b-acaec350e71b)
