# Asset.sol

ERC20合約

功能：
- 擁有者可以設定
  - 最大發行量
  - 清算標準
- 標定可存入之抵押品
- 存入抵押品
- 借出合成資產
- 還回合成資產
- 提取抵押品
- 清算抵押品

## 路線
單 Colleteral 單 aAsset
單 Colleteral 多 aAsset
多 Colleteral 多 aAsset

## 進度
必要 functions
- [ ] 
- [ ] constructor set 
  - [ ] colletral rate
- [ ] set colletral rate
- [ ] set avalable colleteral asset
- [ ] deposite
- [ ] mint
- [ ] burn
- [ ] count colleteral rate
- [ ] liquidate

延伸 function
- [ ] set max supply
- [ ] 各種給項目方的 fee
 - [ ] liquidate
