# charuco-pose-estimation
ChArUco pose estimation using OpenCV

1. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tony2guo/charuco-pose-estimation/blob/master/charuco-pose-estimation.ipynb)
1. Print out [charuco_board.png](charuco_board.png) and take a picture of it, name the picture [image.png](image.png). Make sure not to accidentally stretch the image during print.
1. Measure the actual square length and marker length of the printout, and change it in the code respectively
1. Create [intrinsic.txt](intrinsic.txt) with camera intrinsic matrix
1. Upload [image.png](image.png) and [intrinsic.txt](intrinsic.txt) to the current directory at the "Files" bar on the left
1. Click "Runtime" and "Run all" and see the output file [charuco_tf.txt](charuco_tf.txt) and [camera_tf.txt](camera_tf.txt) in the current directory


Create ChArUco
![charuco_board](charuco_board.png)

Detect markers
![markers](markers.png)

Detect ChArUco
![charuco](charuco.png)

Projection
![projection](projection.png)

## Printer settings for Windows

- Uncheck `Fit picture to frame`:

  ![printer-uncheck-fit-picture-to-frame](images/printer-uncheck-fit-picture-to-frame.png)

- Select `Shrink to Fit`:

  ![printer-select-shrink-to-fit](images/printer-select-shrink-to-fit.png)
