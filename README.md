# Viking Rise Auto Scripts
Viking Rise Scripts for BlueStacks simulator
- 維京崛起 BlueStacks 模擬器掛機腳本

## 前期設定
1. 安裝 BlueStacks 模擬器 (作者使用 BlueStacks 10)
2. 開啟模擬器安裝好 `維京崛起` 遊戲，並登入帳號
3. 確保可以正常進入使用後，開始進行以下設定

## 鍵盤位置設定
請照操作，設定快速鍵位置。【很重要絕對不可以跳過!】
1. 開啟模擬器右手邊 `鍵盤控制` (從上往下數第 4 個)

![image](https://github.com/yunchang1986/VikingRiseAutoScripts/blob/main/images/keyboard_1.png)

2. 進入 `操控配置編輯器`

![image](https://github.com/yunchang1986/VikingRiseAutoScripts/blob/main/images/keyboard_2.png)


2. 點選 `匯入` 按鈕，將 keyboards 資料夾中的 `com.igg.android.vikingriseglobal.cfg` 匯入，匯入後畫面請參考下圖。
- `Default` 配置為新手專用，給搜尋畫面中沒有 `魔物` 的角色使用
- `4隊` 配置給搜尋畫面中有 `魔物` 的角色使用

![image](https://github.com/yunchang1986/VikingRiseAutoScripts/blob/main/images/keyboard_3.png)

3. 匯入完成後，回到大地圖點開搜尋介面，點擊鍵盤確保以下每個功能鍵都有作用
- `空白鍵`: 大地圖小地圖切換
- `S`: 搜尋
- `1`: 食物
- `2`: 木頭
- `3`: 食材
- `4`: 金幣

4. 如果以上鍵盤快捷鍵沒有作用，請進入 `鍵盤控制` 的 `操控配置編輯器`，檢查快捷鍵是否有移位


## 腳本使用
1. 開啟 BlueStacks 的資料夾，複製所有 `UserScripts` 中檔案到路徑中
路徑：C:\ProgramData\BlueStacks_nxt\Engine\UserData\InputMapper\UserScripts

2. 使用方法
- 執行腳本前，確保畫面在大地圖上(試著按下Space切換大小地圖)

![image](https://github.com/yunchang1986/VikingRiseAutoScripts/blob/main/images/keyboard_4.png)

- 開啟模擬器右手邊 `打開腳本管理器` (從上往下數第 5 個)

![image](https://github.com/yunchang1986/VikingRiseAutoScripts/blob/main/images/keyboard_1.png)

- 單純採集使用 `3隊採集2次` 或 `純採集`，都會執行食物、木頭、石材各一次的搜尋跟派兵，其他 scripts 都有用處請不要刪除

![image](https://github.com/yunchang1986/VikingRiseAutoScripts/blob/main/images/scripts_1.png)

- 點擊幫助可使用 `幫助15s_採集5m_3隊`，預設執行20次幫助點擊後，回到大地圖搜尋並派出採集隊。使用前請先確認主堡內 `部族殿堂` 放在按鍵R的位置下方。

![image](https://github.com/yunchang1986/VikingRiseAutoScripts/blob/main/images/keyboard_1.png)

