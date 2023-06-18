# mnist-classifier-web-app

***This is one of my early projects, finished by the end of dec 2022***

This is a web app that can classify handwritten digits from 0 to 9. The model is trained using the MNIST dataset. The model is a feed forward neural network with 2 hidden layers. The model is trained using PyTorch. The web app is built using Flask.


## Dependencies

- flask
- torch
- torchvision
- matplotlib

## How To Use

1. In order to get the .pth file, run `python app/mnist_ffn.py` to train the model
2. Run `python app/app.py` to start the web app
3. Run `python app/test_six.py` to test the web app

## References

- [Flask](https://flask.palletsprojects.com/en/1.1.x/)
- [PyTorch](https://pytorch.org/)
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
