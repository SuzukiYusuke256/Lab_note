- Porous Substrate Optimization for Efficient Water Electrolysis: Uncovering Electrocatalysts, Electrolyte, and Bubble Dynamics Effects
- K. Tsuburaya et al., *ACS Sustain. Chem. Eng.*, **12**, 16308 (2024).

keywords
- porous electrode / 3D electrode
- electrode thickness
- stacking number

- メッシュを重ねた電極で水電解
- 触媒についても結構書いてあり参考になる．
- 実験条件
	- 電極 Ni 
	- 電解液 KOH 1 mol/kg 353 K
	- 参照電極 Ag/AgCl
- やったこと
	- メッシュの網目の間隔 50, 100, 200 um
	- スタック数 何枚重ねたか thickness
	1. IV 曲線を測定 (実験)
		- 電極 Ni単体 / Ni +NiFeOx を蒸着の2種類で，Tafel slope の係数が違う
	2. 厚さ方向のポテンシャルと電流密度．1次元モデル (数値計算)
		- 抵抗過電圧を数値計算 $$j = - \sigma_{eff} \frac{d \phi}{dx}$$
	3. 実験との比較
		- 過電圧 が最小になるスタック数の存在
		  → 反応面積の増加と気泡による詰まりのバランスじゃね?
