# Image-Captioning
We use flickr8K dataset that has 5 captions for each traing image:<br />
https://www.kaggle.com/adityajn105/flickr8k <br />
After adding strat and end tokens to the caption and assigning an index to words, we emmbed the captions. The following two architecture are relatively used in training and testing the model. We compare results woth and withput freezing the reznet part of the architecture.<br />
![training the model](https://github.com/BanafshehKarimian/Image-Captioning/blob/main/1.PNG)<br />
![testing the model](https://github.com/BanafshehKarimian/Image-Captioning/blob/main/2.PNG)<br />
A sample of the result:<br />
![A sample of the result](https://github.com/BanafshehKarimian/Image-Captioning/blob/main/resultsample.PNG)
