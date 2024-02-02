# Yolov5_with_EigenCam
Train and do transfer learning with various yolov5 models and find out what parts of an image made the most contribution to decision making of the model, using explainable AI called EigenCam.

Follow the Colab Notebook code to train the models while also using ClearML for logging and comparing how models performed with different parameters.
When importing EigenCam, first unzip the folder pytorch_grad_cam and upload it to same location where your notebook is, so that it can be imported and used.
Also you can specify to freeze the layers in case you have pretrained model and you want to do transfer learning. And using clearML you can do hyperparameter optimization and upload your dataset to ClearML
