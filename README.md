# Multimodal Image inspired Hashtag Generator

The goal of this project is to generate hashtags given a multi-modal post on OSM like Instagram that may contain both images and text content. The user might also provide a set of few seed hashtags as input and the generated hashtags should be relevant to these hashtags as well.
The project thus requires to leverage the latest methods in computer vision such as Convolutional Neural Networks (Resnet50, Transfer
learning) and in NLP such as glove embeddings, and word2vec to get a high precision/recall on the given task. A two level hierarchical system is proposed where the predictions made by an image classifier are subsequently used by the corresponding text based approach.
