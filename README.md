<h1 id="mobilenet-google">MobileNet (Google)</h1>
<h2 id="overview">Overview</h2>
<p>The MobileNet is a neural network architecture. It’s suitable for mobile devices.<br>
It can be used as the following:</p>
<ul>
<li>Feature extractor</li>
<li>Basic image classifier</li>
</ul>
<p>It’s one of the Google products. According to [1] The first version was efficient for general purpopse computer vision neural networks designed for mobile devices.<br>
The second version is more powerful for</p>
<ul>
<li>Classification</li>
<li>Object detection</li>
<li>Semantic Segmentation</li>
</ul>
<h2 id="convolutional-layer-in-the-mobilenet">Convolutional layer in the MobileNet</h2>
<p>The convolutional layers are for feature detecting, therefore they are important for computer vision. If we consider a convolutional layer in a model, it has quite expensive computation.<br>
In MobileNet the convolutional layer has been replaced with <strong>depthwise separable</strong> convolutions.</p>

## MobileNetV2 usage
The mobile visual recognition is done more efficiently with classification. The MobileNetV2 is part of [TensorFlow-Slim Image Classification Library](https://github.com/tensorflow/models/blob/master/research/slim/README.md), it will be explained later. 

## MobileNetV2

<h2 id="references">References</h2>
<p><a href="http://ai.googleblog.com/2018/04/mobilenetv2-next-generation-of-on.html">1- MobileNetV2: The Next Generation of On-Device Computer Vision Networks</a></p>

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTUyMjA3Mzk0NSw3MjY4NTY5OTAsNTY5NT
Y5NDc0XX0=
-->