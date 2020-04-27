# FMNIST Classification using CNN and RNN
## Fendy Hendriyanto and Team

* <b>Introduction</b>

  Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples.
  Each example is a 28x28 grayscale image, associated with a label from 10 classes. Zalando intends Fashion-MNIST to serve as a direct drop-in 
  replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure 
  of training and testing splits. The MNIST dataset (arguably) is the dataset most often used as a starting point for image classification learning. 
  The scientific data community likes this dataset and uses it as a benchmark to validate their algorithms. MNIST is often the first dataset that researchers try.
  
  <i>"If the algorithm cannot work with MNIST, the algorithm will not work for other data sets. If the algorithm works with MNIST, a good start, but that does not mean it can work for other data sets."</i>
  
  | Label 	| Description 	|
  |:-----:	|-------------	|
  | 0 	| T-shirt/top 	|
  | 1 	| Trouser 	|
  | 2 	| Pullover 	|
  | 3 	| Dress 	|
  | 4 	| Coat 	|
  | 5 	| Sandal 	|
  | 6 	| Shirt 	|
  | 7 	| Sneaker 	|
  | 8 	| Bag 	|
  | 9 	| Ankle Boot 	|
  
  <img src="https://github.com/zalandoresearch/fashion-mnist/blob/master/doc/img/fashion-mnist-sprite.png" alt="" style="max-width:100%;">
  
  You can download the dataset in Kaggle or the link below :
  
  <table>
<thead>
<tr>
<th>Name</th>
<th>Content</th>
<th>Examples</th>
<th>Size</th>
<th>Link</th>
<th>MD5 Checksum</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>train-images-idx3-ubyte.gz</code></td>
<td>training set images</td>
<td>60,000</td>
<td>26 MBytes</td>
<td><a href="http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/train-images-idx3-ubyte.gz" rel="nofollow">Download</a></td>
<td><code>8d4fb7e6c68d591d4c3dfef9ec88bf0d</code></td>
</tr>
<tr>
<td><code>train-labels-idx1-ubyte.gz</code></td>
<td>training set labels</td>
<td>60,000</td>
<td>29 KBytes</td>
<td><a href="http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/train-labels-idx1-ubyte.gz" rel="nofollow">Download</a></td>
<td><code>25c81989df183df01b3e8a0aad5dffbe</code></td>
</tr>
<tr>
<td><code>t10k-images-idx3-ubyte.gz</code></td>
<td>test set images</td>
<td>10,000</td>
<td>4.3 MBytes</td>
<td><a href="http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/t10k-images-idx3-ubyte.gz" rel="nofollow">Download</a></td>
<td><code>bef4ecab320f06d8554ea6380940ec79</code></td>
</tr>
<tr>
<td><code>t10k-labels-idx1-ubyte.gz</code></td>
<td>test set labels</td>
<td>10,000</td>
<td>5.1 KBytes</td>
<td><a href="http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/t10k-labels-idx1-ubyte.gz" rel="nofollow">Download</a></td>
<td><code>bb300cfdad3c16e7a12a480ee83cd310</code></td>
</tr>
</tbody>
</table>

* <b>Content</b>

  Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total.
  Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. 
  This pixel-value is an integer between 0 and 255.The training and test data sets have 785 columns. 
  The first column consists of the class labels (see above), and represents the article of clothing.
  The rest of 784 columns (1-785) contain the pixel-values of the associated image.
  
* <b>Usage</b>
  
  <b>Use Google Colab if you have problem with your library Tensorflow or Keras.</b> 
  For complete installation details and load dataset, you can check <a href="https://github.com/zalandoresearch/fashion-mnist" rel="nofollow">Github Zalando</a>.
  
* <b>Method</b>
  
  In this Method, for classification using Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN). 
  For this theory you can see in <a href="https://towardsdatascience.com/the-4-convolutional-neural-network-models-that-can-classify-your-fashion-images-9fe7f3e5399d" rel="nofollow">Medium</a>.
  
  
  
  
  


