# Qt-CodeOptimization-Task-1

Today a client contacted our company Umpun-Numpum and asked to improve his code, because his code is too slow. The client says that this code is processing a very large number of photos, but recently, the audience of his service has grown by 1 person, after which the server can no longer cope with processing 2 people at the same time.

**Also, the client asked to transfer the code to a special class.**

The tasks of the code include:
1. Get all images from **image cache folder**.
2. Sort in QList by last modified time.
3. Perform image operations.

Required when completing the assignment:
1. Compliance with [Qt Coding Style](https://wiki.qt.io/Qt_Coding_Style).
2. Download [image data](https://drive.google.com/file/d/1odsM9ab8Sg27K3qDkhXX1YnJLucN9y4P/view?usp=sharing) and unzip all images inside **image folder** of your debug folder. 

___

To complete this task, You have to use threads, very usefull will be to use [QtConcurrent](https://doc.qt.io/qt-5/qtconcurrent-index.html) lambda.
You have to complete test for max **150ms**.
