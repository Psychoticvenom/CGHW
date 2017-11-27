# Computer Graphics HomeWorks -- 計算機圖學作品集
學生：I4A49 黃暐程

### Homework 1 [URL](https://psychoticvenom.github.io/CGHW/HW1.html)
- : 利用[Time-based Animation](https://drive.google.com/file/d/0B1qUcd0UXJyZaDVaWGJBTWE4aE0/view)練習撰寫一個能夠在不同運算速率的電腦中呈現幾乎相同速度的碼表 [WHY?](http://blog.sklambert.com/using-time-based-animation-implement/)
- : 利用[Color Models](https://drive.google.com/file/d/0B1qUcd0UXJyZRGRxQ2hjdGU5bWc/view)為自己的碼表增添色彩
- : 使用不同的運動方式呈現 [Example](https://www.youtube.com/watch?v=zBflo3UG6Og)：Analog、Quartz

##### 作品介紹
- : Start、Pause Button
	- 控制碼表的開始及暫停
- : Restart Button
	- 使碼表重新開始計算
- : Analog、Quartz、Sector Button
	- 改變碼表的運動方式及圖形
- : 在Sector圖形中，我使用了[HSL](http://csscoke.com/2015/01/01/rgb-hsl-hex/)利用Angle調整Hue讓這個圖形隨著進行的角度改變而變色

### Homework 3 [URL](https://psychoticvenom.github.io/CGHW/HW3.html)
1. 建構坦克模型：
	- :正確的機構(kinematic)模型，以及合理的joint angle limits
	- :架設合適的燈光，設定合適的顏色
2. 砲彈發射：
	- :初始位置：砲口; 發射方向：砲管方向; 發射速率：固定
	- :砲彈打到地面(y=0)即停止。停止後，才可以發射下一發砲彈。
	- :[雜研與專題生] write "class" for cannonball, 使得可以發射多發砲彈, reference
3. 簡單遊戲：
	- :坦克在中線(x = 0)上前後運動
	- :地圖的兩端(x = 100, x = -100)隨機產生標靶
	- :操作坦克，將標靶擊落
	- :[bonus] 分隔畫面: god's eye view 以及 坦克操作員視角（以便瞄準）
	
##### 作品介紹
- : Q、E旋轉砲台；W、S旋轉砲管；A、D左右移動坦克
- : Space發射砲彈