# OCR_Handwritten
<b>OCR</b> is an optical character recognition (OCR) tool for python. That is, it will recognize and "read" the text embedded in images.</br>
</br>
<B>EasyOCR</B> is a Python package that allows computer vision developers to effortlessly perform Optical Character Recognition.</br>
</br>
In EasyOCR it didnt allow handwritten fonts it only allows compuratrized fonts. For detecting handwritten fonts I have created my own dataset using NIST dataset which contains 8,10,000 images after filtering it only contains 30,000 images and I have also added 6,000 different font images.</br> Model has been trained on tanserflow which gives accuracy of   40-50 percent. It only detects characters. The process of detecting characters from words is still on going. If we use heavy dataset OCR becames custom model which will detect handwritten fonts as well as computerized fonts. This will also improve accuracy of model.</br>
</br>
<b>To run the given model follow these steps :- </b></br>
-> Download the given dataset. </br>
-> Download the given notebooks. </br>
-> Use train model notebook to train the model. </br>
-> Run character detection notebook (to detect the characters). </br>
</br>
<b>Approch</b> :- </br>
-> Firstly I used EasyOCR liberary but it didnt detect handwritten fonts it only detect compuratrized fonts.  </br>
-> After that I have used NIST dataset to train my model because OCR_handwritten model were not available on any site. As i was try to train my model it consumes alot of time and    I was train my model on paperspace which only allows 6 hours on free GPU.  </br>
-> After this I work on NIST dataset as it contains 8,10,000 images after filtering and reducing the size of data it only contains 30,000 images. </br>
-> For training the dataset Firstly I 
