# zero-foundry – Protocol: Zero 社群外觀倉庫

本儲存庫為競技 FPS 遊戲 [Protocol: Zero](https://github.com/thumb2086/Protocol-Zero) 的官方社群外觀資料庫。

想做外觀？歡迎！
但官方限定槍皮永遠只會比你帥（因為老大會加粒子特效）

## 這裡只能放
- blueprints/weapons/ 裡的「外觀覆寫」JSON
  - 必須有 "baseWeapon": "vandal" 這類欄位
  - 可以改模型、零件尺寸、CSG 參數、皮膚、顏色、作者、槍名
  - 絕對不能改任何平衡數值（會被 Actions 自動擋掉）

## 範例檔案
- thumb2086-Vandal-Default.json        ← 官方預設外觀
- community-Phantom-White.json          ← 示範用

## 目前待辦（大家一起打勾）
- [x] 建立資料夾結構
- [x] 放官方預設外觀（Default 版）
- [x] 放一個範例皮膚（白色幻影）
- [ ] 更多社群創作（等你們來！）

## 自動檢查
GitHub Actions 會檢查：
- 有沒有偷偷改傷害、射速等欄位 → 直接擋 PR
- JSON 格式對不對

快來貢獻你的瘋狂外觀吧！
