# ML_Class1
Note for ML
機器學習 ＝ 讓機器具備找函式的能力

## Different types of functions 機器學習的兩大類任務
 1. Regression -> 函式的輸出是一個數值
 2. Classification -> 機器要從眾多類別中選出正確的答案
    如：G-mail去偵測信件是否為垃圾郵件
 3. Structured Learning -> 要機器學會創造（畫一張圖、寫一篇文章等）

## How to find a function?
 機器學習找函式的過程有三步驟：
  1. 寫出一個帶有未知參數的函式: 未知參數是based on domain knowledge，可以從data去得出
     Function with unknown parameters = model
  2. Define loss from training data: Loss值可以去判斷所挑選的weight跟bias挑的好不好
     L有MAE(mean absolute error)、MSE(mean square error)等
     計算Loss所畫出來的等高線圖 -> error surface
  3. Optimization: 找出使loss最小的weight跟bias，使用gradient descent的方法
     Learning rate的大小由自己來決定，若Learning rate大一點的話，參數變化的量就會很大，學習的速度可能較快
     gradient descent會有無法找到global minima的問題！
  ＊ 在機器學習中，需要自己設定的參數稱為hyperparameters
  ＊ 基於對問題的理解，來做模型的修改
 
## 如何減少Model Bias -> 使用Flexible Model
  different w,b,c -> different sigmoid function -> different piecewise function -> different continuous function
  要用多少個sigmoid function是由自己決定
  
  
