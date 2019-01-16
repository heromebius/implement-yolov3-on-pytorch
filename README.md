# implement-yolov3-on-pytorch
##  基本需求


		若要執行此程式,請先擁有：
		1.Python 3.5以上
		2.OpenCV
		3.PyTorch 0.4以上


##  開始偵測
		在執行之前,請先去下載[yolov3.weights]（https://pjreddie.com/media/files/yolov3.weights）


###  圖片偵測

		若要做圖片偵測,請輸入
		`python detect.py --images 你的圖片 --det 你要存放的位置`
###  影片偵測

		若要做影片偵測,請輸入
		`python video.py --video 你的影片`
		**請注意**,因為opencv的只能讀取avi檔的影片,因此在偵測前請先把影片格式改成.avi檔
