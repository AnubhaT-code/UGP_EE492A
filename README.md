# UGP_EE492A
In this repository, I have included my research work for biomedical image enhancement using image processing techniques.

To run each file,  follow these steps:
1. Create a folder for input images and save input images in that folder.
2. Create a folder to store output images.
3. Each file has a cell as <br>
```
     dir_path = '/content/drive/MyDrive/UGP_EE492A/PSO_results/roi_images/' 
     output_path =  '/content/drive/MyDrive/UGP_EE492A/PSO_results/roi_results/' 
```

  Update dir_path variable with pathname to input image folder. <br>
  Similarly, update output_path variable with pathname to output image folder.
     
4. Run the script to get the results.<br>
5. Remove this if not using google colab and make relevant changes accordingly. <br>

```
     from google.colab import drive <br>
     drive.mount('/content/drive',force_remount=True)
```
