# Deep Learning System for Image Retrieval

Can refer to this medium article to find out more about the technical details and thought process behind this project ->  https://medium.com/@sraosumanth/attention-in-multi-modal-machine-learning-problems-67cd0aeb3964


## How to run the project

To start with,
download the weights of the pretrained models from [here](https://mega.nz/#F!zow0XCRT!xlSu9UGgAKO56gszuTQkdQ),  and save the folder in the same directory as the other files of this repo.

Now the base directory will have 3 subdirs which are namely:
  1.	DLSIR_demo: contains the code for the final GUI demo
  2.	DLSIR_model_training_experiments: contains several colab notebooks where different experiments where trained and the model weights were saved.
  3.	DLSIR_model_weights: contains several model weights for the various models which were trained.
  4.  DLSIR_report: this is the project report which entails all the architectural details and training details in detail.

In order to run the DLSIR_demo the steps to follow are:
  1.	Run download_data.py
  2.	Run inception_features_saving_to_disk.py
  3.	Run cache_image_embeddings.py
  4.	Run predictions.py and server.py as two separate simultaneous processes
  5.	Go to 0.0.0.0:5000 to see the application running
  
### Developers:
  - [`Parashara Ramesh`](https://github.com/ParasharaRamesh)
  - [`Shahid Ikram`](https://github.com/shahidikram0701)
  - [`Sumanth Rao`](https://github.com/sumanthrao)
