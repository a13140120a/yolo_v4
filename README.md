# yolo_v4

1. [下載這個](https://github.com/a13140120a/yolo_v4/blob/main/train.rar)

2. 下載labelImg  
  * cmd輸入:
      ```js
      pip install pyqt5
      pip install lxml     #已經裝過就不用
      pip install labelImg
      labelImg
      ```
  * 或是直接下載[exe檔](https://github.com/a13140120a/yolo_v4/blob/main/windows_v1.8.1.rar)
    
3. 把要訓練的圖片放進[剛剛下載的這包解壓縮之後](https://github.com/a13140120a/yolo_v4/blob/main/train.rar)底下的\VOCdevkit\VOC2021\JPEGImages
4. 開啟labelImg 之後把Change Save Dir 改成[剛剛下載的這包解壓縮之後](https://github.com/a13140120a/yolo_v4/blob/main/train.rar)底下的VOCdevkit\VOC2021\Annotations
5. 並且點擊Open dir 開啟 \JPEGImages
6. 勾選左上選單的View底下的 Auto Save mode
7. 可以開始拉框框標記了 (快捷鍵 W:拉框框， D:下一張， A:上一張)
    ![image](https://github.com/a13140120a/yolo_v4/blob/main/teach.PNG)
9. 每標記完一張圖Annotations 底下都會出現一個xml檔案  #檔名不要有中文
