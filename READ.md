# 軟冰淇淋模擬器 | Soft Serve Simulator

可選顏色的 3D 軟冰淇淋模擬器網頁小遊戲。

受 [softserve.nog.cc](https://softserve.nog.cc/) 啟發製作。

## 功能

- 🍦 多種冰淇淋顏色可選（香草、巧克力、草莓、抹茶、藍莓、芒果 + 自訂顏色）
- 📱 支援滑鼠與觸控操作
- 📏 即時顯示高度（cm）
- 🏆 本地最高分紀錄
- 🎨 純前端，單一 HTML 檔案

## 操作方式

1. **移動甜筒**：滑鼠移動 / 手指拖曳
2. **擠冰淇淋**：按住滑鼠左鍵或手指按住
3. 把甜筒對準上方噴嘴，就能持續長高
4. 按「完成！」結束並記錄成績

## 如何遊玩

### 直接開啟
用瀏覽器打開 `index.html` 即可。

### 上傳到 GitHub Pages

1. 建立新的 GitHub Repository
2. 把 `index.html` 和 `README.md` 上傳
3. 到 Repository → Settings → Pages
4. Source 選擇 `main` branch → `/ (root)`
5. 儲存後等待幾分鐘，就能用 `https://你的帳號.github.io/倉庫名稱/` 遊玩

### 本機快速測試

```bash
# 如果有 Python
python -m http.server 8080

# 或用 npx
npx serve .
```

然後開啟 http://localhost:8080

## 技術

- Three.js r160
- 純 HTML + CSS + JavaScript（ES Module）
- 無需建置工具

## License

MIT — 隨意使用、修改、分享。
