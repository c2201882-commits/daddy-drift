# 爹地漂流記

用 Three.js 做的第三人稱城市走路小遊戲。用自訂角色模型在程式生成的城市裡探索，找到躲起來的 NPC 就完成任務。

## 玩法

- `W` / `S`：前進、後退
- `A` / `D`：左轉、右轉
- `Shift`：跑步
- 滾輪：縮放鏡頭

## 在本機執行

這個專案沒有建置流程，是純靜態網站，但角色模型檔案較大，用瀏覽器直接開啟 `index.html`（`file://`）會被瀏覽器的安全限制擋下 `fetch`。請用任何靜態伺服器在專案目錄下執行，例如：

```bash
python3 -m http.server 8080
```

然後開啟 `http://localhost:8080`。

## 素材來源

- 城市建築、路樹：[Kenney.nl](https://kenney.nl) City Kit (Commercial) 與 Nature Kit（CC0 授權）
- 角色模型：使用者提供
