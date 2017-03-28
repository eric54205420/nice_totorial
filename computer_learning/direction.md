---

# 前言 
 
* 最近兩三年我都在搞電力電子(柔切的Buck, 最近很夯的GaN MOS, 還有各類Inverter), 

--- 

# 各科心得  

##	讓理論有意義實作是不可少

## 	筆記無用 請寫代碼 ( trace and debug )  
##	數學科目例外 
 
---


#  計算機結構 
	* 算機結構 計算機組織 有什麼不一樣 

		* 計算機組織 - 
			* Computer Organization - 計算機結構 - 
				* Computer Architecture: Computer Organization and Design: The Hardware/Software Interface by David A. Patterson, John L. Hennessy 

				* 課本是知名的白算盤本
		*算機結構 - 
			*  Computer Architecture: A Quantitative Approach by Jonh L. Hennessy, David A. Patterson  
			* 作者同樣是Hennessy跟Patterson  


		* 一般大學部上課是 教前者, 到了研究所, 高等計算機結構這門課才會教後者. 


		* 把這兩個科目唸好 => 數位邏輯基礎打好. 
			* 多寫Verilog
			* 自幹一顆CPU
				* 自幹CPU不知道怎麼下手 可以考慮去下載 Xiline ISE WebPACK
 				* 我個人是Xilinx的用戶, 不過學界好像Altera比較 常見 
				* 用Verilog去敘述計組裡面那個MIPS CPU的各個部份, 最後再跑模擬. 

				* 有 $ 可以去買一片Spartan6 的開發版
 			*自幹Compiler(lex+yacc)
			*熟悉x86組語, 
---

# 作業系統 

*閱讀並修改一些教學用的作業系統
	* 例如: NachOS, 甚至是真正的作業 系統. 
	*台大是拿Linux教, 交大是拿Windows教. 
	* 我個人是看Windows, 直接請IDA吃ntoskrnl.exe跟ntdll.dll. 
		* 搭配 Mark Russinovich 的 Windows Internal 一起服用. 
	* OS應用的實作部份寫寫multi-thread 的程式
	* 用用mutex
	* 記憶體管理方面: VirtualAlloc() 跟mmap()系列API 了解
	* OllyDbg來看各個Process的Memory Mapping

* 恐龍本唸完 內含實作上 比較少見到的理論
---


# 資料結構 / 演算法

* 課本 Cormen  跟Horowitz 
* 所有資料結構/ 演算法手操一次 and 使用實際資料測試
* ACM題庫找 演算法/資料結構的基本題來實驗
* 指標 指標 指標
* 遞迴概念 
	*LeetCode OJ206 ( C作答, 20分鐘內 AC )
* 用遞迴解 LeetCode OJ206
* Cormen本證明 
	*遞迴 Big O 	 
---

# 線性代數 
	* 高斯消去找Inverse
	* Gilbert Strang 課本	
	* ![ 線性代數介紹 ](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
---


# 離散 
	* 把DS/Algo看完之後離散差不多 剩下議題再留心 

--- 

#  數論 
	* 排列組合/機率 - Binary Relation - 
	* Boolean代數
		* Rosen Rosen本
---

# 千萬別讓任何人告訴你你不行
# 強弱是你自己決定

--- 
