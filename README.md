Keras Unet

Steps

1. Create a new environment with python>=3.8
   ```commandline
   conda create -n KerasUnet python==3.9.15
   ```

2. Install the package in your environment
   ```commandline
   python image-segmentation-keras/setup.py install
   ```
3. Install the requirements
   ```commandline
   pip install -r requirements.txt
   ```

4. Download dataset
   ```commandline
   python image-segmentation-keras/get_data.py
   ```

5. Train the model on the dataset
   ```commandline
   python python image-segmentation-keras/model_train.py \
   -dd "G:\My Drive\Upwork\Porfolio Projects\Image Segmentation with Keras Unet\data\dataset1" \
   -chxp "G:\My Drive\Upwork\Porfolio Projects\Image Segmentation with Keras Unet\Models" \
   -e 1 -ih 320 -iw 640
   ```