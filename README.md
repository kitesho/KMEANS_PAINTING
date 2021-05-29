# KMEANS_PAINTING

 1. K-means for reducing the number of colors in the image
 2. filters to detect the edges
 3. pyautogui for drawing using cursor
 4. coloring with k-means

1
  number of colors in the input image may be large and it may forever to complete the painting. so, kmeans is used to reduce the number of colors in the input image.
 
2 
  using gaussian blur and canny edge detection the outline of the image is detected.
  
3
  using pyauto gui the movement of the cursor is controlled and the commands are created using the points we extracted by appyling the filters

4
  Each color is applied the same way the outline is drawn. Instead of using filters, centroid of each clusters are taken and the commands for puautogui is created using all the points which have selected centroid as their centers. 
