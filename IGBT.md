---
created: 2024-05-13T13:32:00
Topics:
  - 電子元件
  - MOS
  - BJT
Source URL: https://www.youtube.com/watch?v=wqvEvHmNNZ8
---
![[Pasted image 20240513133328.png|300]]
當要驅動大電流時MOS無法做到，以一般BJT來說若要驅動100A，則BE間要有10A流過，但單晶片無法輸出10A給BE，結合MOS及BJT如上圖，當給MOS高電壓時，MOS導通BJT關閉；給MOS低電壓時，MOS開路，則可以給BJT足夠的電流了
而這裡有兩個小問題：需額外的5V及電阻、MOS導通關閉與輸出相反，因此稍微改一下
![[Pasted image 20240513134443.png|300]] ![[Pasted image 20240513134609.png]]
如上圖就是IGBT的架構