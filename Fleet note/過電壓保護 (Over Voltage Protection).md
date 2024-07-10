# 用途：保護電子設備免受高壓損害，提高可靠性

## 1. [[SCR]]保護：使用矽控整流器(Silicone Controlled Rectifier,SCR)作為過電壓保護電路的方法
![[Pasted image 20240710092525.png]]
- 晶閘管有時單指SCR，有時只具有四層以上PN交錯的半導體(單向稱SCR，雙向稱TRIAC)
-  單向晶閘管：陽極A（Anode），陰極C（Cathode）和控制極G（Gate），AC端加正電壓不導通，在G及再加上正電壓(相較C極而言)才導通，且導通後去掉G極電壓依然保持導通
- 雙向晶閘管：可等校為兩個單項晶閘管反向並聯，正負雙向都可以控制，所以除G極外其餘兩個電極改稱MT1、MT2或T1、T2，當G與MT1間訊號時，MT2與MT1間就可導通![[Pasted image 20240710101321.png|100]]![[Pasted image 20240710102805.png|200]]

