- Modelling two-phase flow in porous media at the pore scale using the volume-of-fluid method
- A. Q. Raeini et al., *J. Comput. Phys.*, **231**, 5653 (2012).
- Sharp Surface Force (SSF) model [[SSFモデル]]
- めちゃくちゃ疑似流れが低減される．
- 多孔体内の混相流 → microns to millimeter order
- 有限体積法, VOF
- semi-sharp surface force model
- gas-liquid interface, stationary bubble
	![[Pasted image 20260204112717.png|300]]
	<img src="" width="300">
- moving droplet, spurious current 
	![[Pasted image 20260204112752.png|300]]

filtered surface force (FSF) model
- limit pressure in one grid
- capillary force is solved with two filtering?

動く液滴の場合は，FSF, with smoothing がよい．

気泡を計算した論文


