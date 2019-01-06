# deep-learning-with-keras-notebooks

這個github的repository主要是個人在學習Keras的一些記錄及練習。希望在學習過程中發現到一些好的資訊與範例也可以對想要學習使用
Keras來解決問題的同好，或是對深度學習有興趣的在學學生可以有一些方便理解與上手範例來練練手。如果你/妳也有相關的範例想要一同分享給更多的人, 也歡迎issue PR來給我。

這些notebooks是使用Python 3.6與Keras 2.1.1版本跑在一台配置Nivida 1080Ti的Windows 10的機台所產生的結果。對於想要進行Deeplearning的朋友們, 真心建議要有GPU啊~!

## 內容

### 0.圖像資料集
* [0.0: COCO API解說與簡單範例](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/0.0-coco-dataset-api.ipynb)
* [0.1: 土炮自製撲克牌圖像資料集](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/0.1-poker-cards-dataset.ipynb)

### 1.Keras API範例
* [1.0: 使用圖像增強來進行深度學習](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/1.0-image-augmentation.ipynb)

* [1.1: 如何使用Keras函數式API進行深度學習](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/1.1-keras-functional-api.ipynb)

* [1.2: 從零開始構建VGG網絡來學習Keras](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/1.2-vgg16-from-scratch.ipynb)

* [1.3: 使用預訓練的模型來分類照片中的物體](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/1.3-use-pretrained-model.ipynb)
	
* [1.4: 使用圖像增強來訓練小數據集](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/1.4-small-datasets-image-augmentation.ipynb)

* [1.5: 使用預先訓練的卷積網絡模型](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/1.5-use-pretrained-model-2.ipynb)

* [1.6: 卷積網絡模型學習到什麼的可視化](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/1.6-visualizing-what-convnets-learn.ipynb)

* [1.7: 構建自動編碼器(Autoencoder)](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/1.7-autoencoder.ipynb)

* [1.8: 序列到序列(Seq-to-Seq)學習介詔](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/1.8-seq2seq-introduction.ipynb)


### 2.圖像辨識 (Image Classification) 
* [2.0: Julia(Chars74K) 字母圖像辨識](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/2.0-first-steps-with-julia.ipynb)

* [2.1: 交通標誌圖像辨識](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/2.1-traffic-signs-recognition.ipynb)

* [2.2: 辛普森卡通圖像角色辨識](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/2.2-simpson-characters-recognition.ipynb)

* [2.3: 時尚服飾圖像辨識](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/2.3-fashion-mnist-recognition.ipynb)

* [2.4: 人臉關鍵點辨識](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/2.4-facial-keypoints-recognition.ipynb)

* [2.5: Captcha驗證碼辨識](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/2.5-use-keras-break-captcha.ipynb)

* [2.6: Mnist手寫圖像辨識(MLP)](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/2.6-mnist-recognition-mlp.ipynb)

* [2.7: Mnist手寫圖像辨識(CNN)](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/2.7-mnist-recognition-cnn.ipynb)

### 3.物體偵測 (Object Recognition)
* [3.0: YOLO物體偵測演算法概念與介紹](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/3.0-yolo-algorithm-introduction.ipynb)

* [3.1: YOLOv2物體偵測範例](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/3.1-yolov2-object-detection.ipynb)

* [3.2: 浣熊 (Racoon)偵測-YOLOv2模型訓練與調整](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/3.2-yolov2-train_racoon_dataset.ipynb)

* [3.3: 浣熊 (Racoon)偵測-YOLOv2模型的使用](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/3.3-yolov2-racoon_detection_inaction.ipynb)

* [3.4: 袋鼠 (Kangaroo)偵測-YOLOv2模型訓練與調整](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/3.4-yolov2-train-kangaroo-dataset.ipynb)

* [3.5: 雙手 (Hands)偵測-YOLOv2模型訓練與調整](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/3.5-yolov2-train-hands-dataset.ipynb)

* [3.6: 辛普森卡通圖像角色 (Simpson)偵測-YOLOv2模型訓練與調整](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/3.6-yolov2-train-simpson-dataset.ipynb)

* [3.7: MS COCO圖像偵測-YOLOv2模型訓練與調整](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/3.7-yolov2-train-coco-dataset.ipynb)

### 4.物體分割 (Object Segmentation)

### 5.關鍵點偵測 (Keypoint Detection)

### 6.圖像標題 (Image Caption)

### 7.人臉偵測辨識 (Face Detection/Recognition)
* [7.0: 人臉偵測 - OpenCV (Haar特徵分類器)](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/7.0-opencv-face-detection.ipynb)

* [7.1: 人臉偵測 - MTCNN (Multi-task Cascaded Convolutional Networks)](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/7.1-mtcnn-face-detection.ipynb)

* [7.2: 人臉辨識 - 臉部偵測、對齊 & 裁剪](http://nbviewer.jupyter.org/github/erhwenkuo/deep-learning-with-keras-notebooks/blob/master/7.2-face-detect-align-and-crop.ipynb)

### 8.自然語言處理 (Natural Language Processing)