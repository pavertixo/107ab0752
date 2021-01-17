# 資財三乙 107ab0752 蔡康杰

## <H1>ch8<H1>
在CH8中我們學習如何利用SKlearn中RandomForestClassifier以及FeatureHasher分析惡意程式， \
![image](https://github.com/pavertixo/image/blob/main/1.jpg?raw=true)\
一路點進資料夾後能看到這幾個檔案，執行程式的就是run_complete_dector.sh \
而如果點進complete_detector.py觀察程式碼能發現\
![image](https://github.com/pavertixo/image/blob/main/3.jpg?raw=true)\
必須利用SKlearn的RandomForestClassifier以及FeatureHasher對資料進行分析
### <H1>而執行結果為<H1>
![image](https://github.com/pavertixo/image/blob/main/2.jpg?raw=true)\
Statistics: \
Benign-Files: 991 \
Malware-Files: 428 \
從randomforest分類器開始，使用class_weight balance處理傾斜的數據。 \
在繪製時是可以調整靈敏度的，靈敏度越高，檢測寬鬆所以錯誤會高；\
靈敏度低檢測率提高則錯誤率會降低。\
預設的檢測結果是假陽性1%，可檢測到約94%的惡意軟體。

#### <H1> 心得 <H1>
雖然這學期實際上是毛老師上課的次數不多，但兩位老師想傳達給我們實務上 \
是如何解決資安問題的方法有深刻體會，多少能感覺如果接續上學期的suricata檢測被攻擊， \
而如果儲存下樣本，配合這學期的分析方法就能夠將惡意程式進行分類，並尋找解決方式； \
這學期雖然沒點名，功課也只有兩次，但希望老師行行好，能否給高分一點，上學期超級認真， \
結果也才拿到88覺得很灰心喪志。