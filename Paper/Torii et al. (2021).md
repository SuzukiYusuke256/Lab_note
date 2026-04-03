- Three-dimensional coupling numerical simulation of two-phase ﬂow and electrochemical phenomena in alkaline water electrolysis
- K. Torii et al., _International Journal of Hydrogen Energy_, 46, 35088–35101 (2021). https://doi.org/10.1016/j.ijhydene.2021.08.101

### 何をした?
- [[格子ボルツマン法]]を拡張したLKSで混相流を計算
- 濃度場と流れ場を連成.

![[Paper/assets/Torii et al. (2021)/file-20260212174653989.png|400]]
### 何を評価した?
- 濃度分布
- 過電圧 activation / ohmic

### 結論は?
- 気泡運動で濃度勾配が緩和され，過電圧は減少する．
- 気泡が細かいほど過電圧が減少する．

### MEMO
- spurious current は問題ないのだろうか．
- 濃度場の方程式の導出が参考になる
- Marangoni力はなし．濃度分布が流体運動に与える影響については考慮されていない
	> In the coupling simulation, it is assumed that all variables used for the two-phase flow model **do not depend on the local KOH concentration** because it is very difficult to integrate their concentration dependence into the LKS model. Therefore, note that the hydrodynamic properties affect the electro- chemical properties but not vice versa

- 東工大の兒玉研究室



[^1]: 
