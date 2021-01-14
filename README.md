# 107ab0752

ch8

在CH8中我們學習如何利用SKlearn中RandomForestClassifier以及FeatureHasher分析惡意程式，
其中
X = benign_features + malware_features
Y = [1 for _ in range(len(benignware))] + [0 for _ in range(len(malware))]

X_train, X_test, Y_train, Y_test = train_test_split(X, Y, test_size=0.3, random_state=42)
陽性及陰性程度是可以自己去調整的，如前一次功課所提及，關聯度調的越鬆那就越容易連在一起。

而最終搜尋結果為
Statistics:
Benign-Files: 991
Malware-Files: 428

這是我另外找到有同樣是做malware各個章節地的大神github，學習了不少。
https://github.com/hija/MalwareDataScience/blob/master/chapter08/MalwareClassifier.ipynb
