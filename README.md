# Dominant-Color-Extraction-UnsupervisedML
In this project an automated dominant color extraction method using clustering models (K-means, K-medoids clustering) is proposed and implemented. The functions in the jupyter file can be used as a mini toolbox to help anyone who might be interested in color extraction and/or quantification of colors in an image. Possible uses of the functions in the notebook include assistance in: marketing analysis, semiotics, sociology of colors, automatic creation of movie scene timestamps and artistic projects.

# Some general examples:
## Input Image:
![](Sample%20Images/Sample1.png)
## Function Call:
`get_dominant_colors(image, 
                     k=k, 
                     model='kmedoids', 
                     plot_elbow=True, 
                     max_clusters=20, 
                     plot_dominant_colors=True, 
                     metric='distance', 
                     color_ratios=True,
                     pearson_sensitivity=pearson_sensitivity)`
## Dominant Colors:
![](Sample%20Images/Sample1_Dominant.png)

## Input Image:
![](Sample%20Images/Sample2.webp)
## Function Call:
`get_dominant_colors(image, 
                     k=k, 
                     model='kmedoids', 
                     plot_elbow=True, 
                     max_clusters=20, 
                     plot_dominant_colors=True, 
                     metric='distance', 
                     color_ratios=True,
                     pearson_sensitivity=pearson_sensitivity)`

## Dominant Colors:
![](Sample%20Images/Sample2_Dominant.png)

## Input Image:
![](Sample%20Images/Sample3.jpg)
## Function Call:
`get_dominant_colors(image, 
                     k=k, 
                     model='kmeans', 
                     plot_elbow=True, 
                     max_clusters=20, 
                     plot_dominant_colors=True, 
                     metric='distance', 
                     color_ratios=True,
                     pearson_sensitivity=pearson_sensitivity)`
## Dominant Colors:
![](Sample%20Images/Sample3_Dominant.png)

## Input Image:
![](Sample%20Images/Sample4.webp)
## Function Call:
`get_dominant_colors(image, 
                     k=k, 
                     model='kmeans', 
                     plot_elbow=True, 
                     max_clusters=20, 
                     plot_dominant_colors=True, 
                     metric='pearson', 
                     color_ratios=True,
                     pearson_sensitivity=pearson_sensitivity)`
## Dominant Colors:
![](Sample%20Images/Sample4_Dominant.png)

## Input Image:
![](Sample%20Images/Sample5.jpg)
## Function Call:
`get_dominant_colors(image, 
                     k=k, 
                     model='kmedoids', 
                     plot_elbow=True, 
                     max_clusters=20, 
                     plot_dominant_colors=True, 
                     metric='distance', 
                     color_ratios=True,
                     pearson_sensitivity=pearson_sensitivity)`
## Dominant Colors:
![](Sample%20Images/Sample5_Dominant.png)

# Movie Scene Detection
## Input Images:
1/100 of the frames from Stanley kubrick's movie "The Shining"
## 2 Dominant Colors per frame:
![](Sample%20Images/The%20Shining%20-%20Miniature4.png)

For example the red part of the photo above is the bathroom scene:
![](Sample%20Images/bathroom.jpg)

# Time Magazine Covers 1923-2022: 2 Dominant Colors 
![](Sample%20Images/Time_Magazine_Covers.png)
