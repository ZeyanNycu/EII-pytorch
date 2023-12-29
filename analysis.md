# Experimental Result
In this notes, we show the result of experiment. We separately presented the results of qualitization and quantization.
## Images from different domains
### Qualitization
* City  
![Alt text](analysis_img/city.png)
* Nature  
![Alt text](analysis_img/nature.png)
* Painting  
![Alt text](analysis_img/painting.png)
* Satellite  
![Alt text](analysis_img/satellite.png)
* X_ray  
![Alt text](analysis_img/x_ray.png)

### Quantization
| Metric | City | Nature | Painting | Satellite | X_ray |
|:------:|:--------------:|:-------------:|:----------------:|:---------------:|:---------------:|
|  PSNR  |      24.77      |     22.78      |      18.5       |      25.93       |      25.93       |
| LPIPS  |      0.12      |     0.32      |       0.15       |      0.11       |      0.11       |


## learning rate of each layers
### Qualitization
* Linear descent  
![Alt text](analysis_img/linear_descent.png)
* Linear ascent  
![Alt text](analysis_img/linear_ascent.png)
* concave function  
![Alt text](analysis_img/concave_function.png)
* convex function  
![Alt text](analysis_img/convex_function.png)
* GT  
![Alt text](analysis_img/GT.png)
### Quantization
| Metric | Linear descent | Linear ascent | concave function | convex function |
|:------:|:--------------:|:-------------:|:----------------:|:---------------:|
|  PSNR  |      22.24      |     20.26      |      21.53       |      24.11       |
| LPIPS  |      0.23      |     0.32      |       0.17       |      0.07       |
## Number of layers
### Qualitization
* 1  
![Alt text](analysis_img/1.png)
* 2  
![Alt text](analysis_img/2.png)
* 3  
![Alt text](analysis_img/3.png)
* 4  
![Alt text](analysis_img/4.png)
* 5  
![Alt text](analysis_img/5.png)
* GT  
![Alt text](analysis_img/GT.png)
### Quantization
| Metric |   1   |   2   |   3   |   4   |   5   |
|:------:|:-----:|:-----:|:-----:|:-----:|:-----:|
|  PSNR  | 19.06 | 21.25 | 22.24 | 17.37 | 15.99 |
| LPIPS  | 0.34  | 0.25  | 0.23  | 0.19  |  0.2  |
