- Euler-Lagrangian Modeling of H2 Bubbly Flows in an Alkaline Water Electrolysis Cell
- A. Li et al., *Chem. Eng. Sci.*, **325**, 123423 (2026).

- Euler-Lagrange model に基づいてアルカリ水電解の気液二相流を解いている．
- OpenFOAM の DPMFoam (Descrete Phase Model) を使用
- 式が丁寧に書いてある．
	- 液相から気泡にはたらく力
	  $$F_{lb} = F_p + F_D + F_L + F_{VM} + F_{TD}$$
	- 気泡同士の衝突はバネ-ダッシュポッドのモデル．DEMとかでよくある手法?
- RANS と LES で計算．
- わかったこと
	- RANS は乱流散逸項 $F_{TD}$ が支配的．
	- LES は 圧力勾配項 $F_p$ が支配的．← モデルによって変わってええんか?
	- 気泡径が小さいので，揚力 $F_L$ の影響は小さいらしい．
![[file-20260330155631667.png|300]]![[file-20260330155555006.png|300]]
