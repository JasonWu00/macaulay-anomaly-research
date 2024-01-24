## Replicating Our Work

Our work is based on the authors' source code [in this GitHub repo](https://github.com/saikat15010/Brain-Tumor-Detection). We recommend running the Python Notebooks on Google Colab if you do not have sufficiently powerful hardware, as training the models on your device may consume large amounts of resources and take a long time.

Prior to running the notebooks, remember to download the Harvard and Figshare datasets (that the authors used in their paper) into your Google Drive. Alternatively, if the datasets are too large and taxing on your wireless connection, you can make a shortcut to the datasets in a Google Drive folder of your choice. Remember to adjust the file directory address in the notebooks to point to wherever you stored the data set / shortcut.

Remember to connect your notebook to a GPU. Look in the upper right of the Google Colab window and look for a button labeled "Connect". Click on it and select a T4 GPU to connect to. Neural networks are usually best trained using a GPU, as they are much faster and more efficient than the CPUs that Colab connects to by default.