- 課題として，2つ
	- 疑似流れの影響が大きい
	- 界面の成長
- SSF model 
	- Numerical simulation of continuum scale electrochemical hydrogen bubble evolution
		- Vachaparambil, Kurian J. 2021
		- SSF モデルを使って計算
- C-CSTモデル 界面を通じた濃度場の輸送
	- Numerical simulation of species transfer across fluid interfaces in free-surface flows using -OpenFOAM
		- [https://doi.org/10.1016/j.ces.2012.02.034](https://doi.org/10.1016/j.ces.2012.02.034)
	- Marangoni effect induced by dissolved gas concentration in single hydrogen bubble evolution process
		- Feng 2025
		- C-CST モデルを使っている
	- A new compressive scheme to simulate species transfer across fluid interfaces using the Volume-Of-Fluid method
		- Julien Maes, 2018
		- C-CST モデルの始祖?
- LKS
	- Inamuro [https://doi.org/10.1016/j.compfluid.2016.07.016](https://doi.org/10.1016/j.compfluid.2016.07.016) LKSモデルを作った
	- LKS (Lattice Kinetic Scheme) ポアソン方程式を解かなくて良いので，大規模化が容易 Kodama, [https://www.sciencedirect.com/science/article/pii/S0360319921032961?via%3Dihub](https://www.sciencedirect.com/science/article/pii/S0360319921032961?via%3Dihub)
- 末包先生 有限差分・有限体積法での弱圧縮性
- 青木先生 
	- 2023年の数値流体で沸騰のシミュレーションをしている


sharp interface
- VOF
- 体積保存性はいいが，界面曲率の計算性が
smooth interface
- Level-set method
- phase-field
いいとこどり
- CLS-VOF
- Smoothed-VOF

有限体積法
- 保存性がいい．複雑形状にも適用しやすい? メッシュを作るのが大変だけど
LKS 法
- 格子ボルツマンの拡張
- Poisson 方程式を解かなくてもいい → 並列性能が高い
- 別にメモリの観点からは利点はないかも

**Zero gap** 
- Alkaline zero gap bipolar water electrolyzer for hydrogen production with independent fluid path
	- https://doi.org/10.1016/j.egyr.2023.05.135
- The optimal electrode hole size in zero gap alkaline water electrolysis: A combined electrochemical, theoretical, and bubble imaging approach
	- https://doi.org/10.1016/j.ijhydene.2025.150919
- Multiphase alkaline water electrolysis simulations: The need for a solid pressure model to explain experimental bubble overpotentials
	- https://doi.org/10.1016/j.ijhydene.2024.12.252

過電圧
- Zouhri よく引用されてた




