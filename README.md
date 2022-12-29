## Idea
It's my idea for a diploma thesis in Machine Learning project. The project is based on comparsion of 2 methods to initial transofrmation of CAPTCHA for its recognition. The first method involves using the autoencoder (AEFPNC) to transofrmation the data. For initial training of AEFPNC I used default fonts of Windows 7 environment. In the second method I used the mathematical morphology operators. Results predicted by a simple CNN model and visualised by a few graphiс techniques (default loss & accuracy, balanced accuracy and confusion matrix). Prediction occurs for each character separately:

![image](https://user-images.githubusercontent.com/89090809/209942540-79c49c3f-d58d-4fb2-86e8-d3c35f252371.png)

## Structure
* AEFPNC
The network takes a single-scale image as input with size M x N and passes it through four components: Early encoder, Feature Pyramid Network Component (FPNC), Smoothing layers and Decoder. [More info about AEFPNC:](https://github.com/ekremcet/AEFPNC)
![image](https://user-images.githubusercontent.com/89090809/209940687-8a5abddf-66b0-4a42-a37d-98b93052f10e.png)

* Example of the result after transofrmation by mathematical morphology operators:

![image](https://user-images.githubusercontent.com/89090809/209940444-cb2eea72-201e-476f-b3a2-120589e63be9.png)

a – original 24-bit picture, below – binary; b – adaptive thresholding;
c – morfological close; d – morfological dilation; e – Gauss smoothing

* Structure of CNN:

![image](https://user-images.githubusercontent.com/89090809/209940624-8b1b7b10-4286-4da5-9d13-9f29b1afa795.png)

## To sum up
Thanks to the project I have a some better ideas for recognition CAPTCHA, I acquired a pretty good experience and profound knowledge.
