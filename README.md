# Pytroch_Violence_Detection

This project, CCTV Violence Classification, aims to classify surveillance CCTV
footages into three classes: Non-Violence, Violence, and Weapon Violence.

## AI models

We developed 3 AI models for the same task, but each one of them has a different architecture. 
*Note: you can see the details of the models' architecture in the corresponding ipynb file for each model.* 

In the [first model](3DCNN_Model_pretrained.ipynb), we used a pre trained 3D CNN model (Efficient_x3d_xs) and we fine-tuned the classification layer.

The [second model](3DCNN.ipynb) was a custom 3D CNN from scratch.

In The [Third model](lstm_model.ipynb), we extracted features from the frames using resnet50 then we passed the features to a custom lstm model.


We might try majority voting in the future, but for now we wanted to see how well each model does.

