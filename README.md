# OCR_Handwritten
OCR is an optical character recognition (OCR) tool for python. That is, it will recognize and "read" the text embedded in images.</br>
</br>
<B>EasyOCR</B> is a Python package that allows computer vision developers to effortlessly perform Optical Character Recognition.</br>
</br>
In EasyOCR it didnt allow handwritten fonts it only allows compuratrized fonts. For detecting handwritten fonts I have created my own dataset using NIST dataset which contains 8,10,000 images after filtering it only contains 30,000 images and I have also added 6,000 different font images.</br> Model has been trained on tanserflow which gives accuracy of   40-50 percent. It only detects characters. The process of detecting characters from words is still on going. If we use heavy dataset OCR becames custom model which will detect handwritten fonts as well as computerized fonts. This will also improve accuracy of model.</br>
</br>
To run the given model follow these steps :-
-> Download the given dataset.
-> Download the given notebooks.
-> Use train model notebook to train the model.
-> Run character detection notebook (to detect the characters).
