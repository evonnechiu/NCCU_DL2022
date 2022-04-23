# HW3: EMNIST Classification Using CNN

For details: https://docs.google.com/presentation/d/1GDp-3_kb5bE82fLf6OqAqC04fh1Oefe1/edit#slide=id.p1

題目為建立一個分類器來分 Emnist 62類
但這次模型採用的 CNN 

這次要繳交的內容為：
請建立一個 CNN 模型他的測試準確率在 87% 以上 (Model baseline)，並畫出訓練回合數跟loss之間的關係圖

再不更改你原先建立的 CNN 模型 \ 回合數 \ 優化器(包含優化器內的超參數)等參數。而是使用 Data augmentation 的方法來將資料做擴增並進行訓練，並回報測試準確率是多少 (Model Improvement) ，並畫出訓練回合數跟loss之間的關係圖

Data augmentation:  https://pytorch.org/vision/stable/transforms.html
