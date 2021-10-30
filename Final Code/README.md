# Industry Porject
## Files Description


[region_128.ipynb](./region_128.ipynb): Jupyter notebook to train autoencoder with input size 128*128

[region_256.ipynb](./region_256.ipynb): Jupyter notebook to train autoencoder with input size 256*256


[autoencoder_region_size_128](./autoencoder_region_size_128): Saved model with input 128

[autoencoder_region_size_256](./autoencoder_region_size_256): Saved model input 256

[data](./data): training data & test instance

[autoencoder_region_size_128.json](./autoencoder_region_size_128.json) : training & validation loss for autoencoder input size 128

[autoencoder_region_size_256.json](./autoencoder_region_size_256.json) : training & validation loss for autoencoder input size 256

[create_test_data_set.ipynb](./create_test_data_set.ipynb): Jupyter notebook to create test data. Input is a single eta_t (1500 x 3600). The notebook will split the original eta_t into smaller chuncks (ie. 128x128 or 256x256)