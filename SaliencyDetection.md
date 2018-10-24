# OpenCV Saliency Detection with Python


OpenCV has three different saliency detection algorithms

- **Static saliency**

Static saliency -> this class of saliency detection algorithms relies on image features and statistics to localize the most interesting region of an image.

- **Motion saliency**

Algorithms in this class typically rely on video or frame-by-frame inputs. The motion saliency algorithms process the frames, keeping track of objects that move. Objects that move are considered salient.

- **Objectness**

Saliency detection algorithm that compute objectness generate a set of proposals, or more simply bounding boxes of where it thinks an object may lie in an image.


**Keep in mind that computing saliency is not object detection.** The underlying saliency detection algorithm has no idea if there is a particular object in an image or not.





<!--stackedit_data:
eyJoaXN0b3J5IjpbNTYxNDM2ODEsOTA5MTcwMDgxLC0xNzY3OD
UxMjIyLC0xNTU1NzE0MjA3LC0zNDYyNDcyNzIsLTEwMjk0Nzc4
NjhdfQ==
-->