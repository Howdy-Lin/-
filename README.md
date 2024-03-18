# 航港局大數據競賽--塞港分析
## 1. 如何具體定義塞港?
利用船舶的誤點時間差當作研究船舶塞港的一個依據\
誤點時長定義:誤點時長 = (進港靠泊時間-預定進港時間)\
## 2.資料分析
### (1) 誤點時長逐年分析
![image](https://github.com/Howdy-Lin/-/assets/74965449/c550cda3-325f-418f-862a-068a90acde30) 
![image](https://github.com/Howdy-Lin/-/assets/74965449/252e5dcd-4fe9-4952-bb54-f325a7e4bf91)\
### (2) 船種分析
![image](https://github.com/Howdy-Lin/-/assets/74965449/4dc919f8-0245-448c-a496-d60aac8076a2)
![image](https://github.com/Howdy-Lin/-/assets/74965449/45d237b6-900d-4586-aa6d-589f0a1a7263)
![image](https://github.com/Howdy-Lin/-/assets/74965449/c6b58240-0403-4c74-933a-574601494953)
![image](https://github.com/Howdy-Lin/-/assets/74965449/ae661349-903b-4aca-89cc-f0af6009dab7)\
### (3) 結論
1.塞港狀況一直都有，並非引發於疫情\
*Ans. 塞港是一直都有的問題，但近年更嚴重*\
2.航班到港時間掌握不足\
*Ans. 找出誤點情況嚴重的碼頭，觀察其誤點狀況*
## 3. LSTM預測
透過LSTM去對未來船班可能的誤點時間做預測，倘若真的能有準確的誤點預測系統\
便能大幅度縮短港口宮坐人員的作業時間，進而減少塞港的時間成本\
![image](https://github.com/Howdy-Lin/-/assets/74965449/cebb0f69-65b2-4c61-bdd9-7750a52c0300)


