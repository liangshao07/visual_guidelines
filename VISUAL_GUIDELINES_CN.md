# GitHub 開源專案配圖規範 / Visual Content Guidelines

本文檔總結了 GitHub 開源專案中普遍認可的配圖規範，幫助專案創建專業、一致的視覺展示效果。

## 📋 目錄

- [核心原則](#核心原則)
- [圖片類型與用途](#圖片類型與用途)
- [技術規格](#技術規格)
- [設計標準](#設計標準)
- [檔案管理](#檔案管理)
- [內容要求](#內容要求)
- [平台適配](#平台適配)
- [最佳實踐](#最佳實踐)

## 🎯 核心原則

### 1. 專業性 (Professionalism)
- 高品質的視覺效果
- 一致的設計風格
- 清晰的資訊傳達
- 避免業餘或隨意的外觀

### 2. 可存取性 (Accessibility)
- 高對比度，確保可讀性
- 支援色盲使用者的色彩選擇
- 清晰的字體和適當的字號
- 簡潔明瞭的介面佈局

### 3. 一致性 (Consistency)
- 統一的配色方案
- 相同的尺寸和格式
- 一致的截圖風格
- 標準化的命名規則

### 4. 國際化 (Internationalization)
- 英文介面優先（國際受眾）
- 避免文化特定的元素
- 通用的圖示和符號
- 簡潔的視覺語言

## 📸 圖片類型與用途

### 1. README 展示圖片

#### Hero Image / 封面圖
```
- 用途: README頂部展示，專案第一印象
- 尺寸: 1200x630 (GitHub Social Preview標準)
- 格式: PNG/JPG
- 內容: 專案Logo + 簡潔描述 + 核心功能展示
- 位置: README.md 頂部
```

#### Feature Showcase / 功能展示
```
- 用途: 展示主要功能和特性
- 尺寸: 1280x720 (16:9比例)
- 格式: PNG/WebP
- 內容: 功能介面截圖或功能示意圖
- 數量: 3-5張，涵蓋核心功能
```

#### Demo GIF / 演示動畫
```
- 用途: 展示互動流程和使用方法
- 尺寸: 800x600 (最大)
- 格式: GIF/WebP動畫
- 檔案大小: <3MB
- 時長: 5-15秒
- 影格率: 10-15 FPS
```

### 2. 文檔配圖

#### Installation Screenshots / 安裝截圖
```
- 用途: 展示安裝過程和步驟
- 尺寸: 原始介面尺寸 (保持真實比例)
- 格式: PNG
- 標註: 清晰的步驟標記
```

#### Tutorial Images / 教學圖片
```
- 用途: 使用教學和說明文檔
- 尺寸: 適合文檔展示
- 格式: PNG
- 要求: 清晰的操作指示
```

### 3. Release Assets / 發佈資源

#### App Store Screenshots / 應用程式商店截圖
```
- 用途: 外掛程式/應用程式商店展示
- 尺寸: 根據平台要求 (通常1280x720+)
- 格式: PNG/JPG
- 品質: 最高品質，無壓縮損失
```

## ⚙️ 技術規格

### 圖片格式選擇

| 用途 | 推薦格式 | 備選格式 | 說明 |
|------|----------|----------|------|
| 截圖 | PNG | WebP | 無損品質，支援透明度 |
| 照片 | JPG | WebP | 適合複雜色彩，檔案較小 |
| 圖示 | SVG | PNG | 向量格式，可縮放 |
| 動畫 | GIF | WebP | 相容性好，檔案大小適中 |

### 尺寸標準

#### 響應式尺寸體系
```
- 超大螢幕: 1920x1080 (桌面顯示器)
- 大螢幕: 1280x720 (標準展示)
- 中螢幕: 800x450 (文檔嵌入)
- 小螢幕: 400x225 (縮圖)

寬高比優先選擇:
- 16:9 (通用)
- 4:3 (傳統)
- 1:1 (頭像/圖示)
- 自訂 (保持原始比例)
```

#### 檔案大小限制
```
- 單張圖片: <5MB (推薦<2MB)
- GIF動畫: <3MB (推薦<1MB)
- README總圖片: <20MB
- 頭像/Logo: <500KB
```

### 解析度要求
```
- 最小解析度: 72 DPI (網頁顯示)
- 推薦解析度: 144 DPI (高清顯示)
- 列印品質: 300 DPI (如需列印)
- 色彩空間: sRGB (網頁標準)
```

## 🎨 設計標準

### 1. 色彩規範

#### GitHub深色主題適配
```css
/* 主色調 */
--bg-primary: #0d1117;     /* GitHub深色背景 */
--bg-secondary: #161b22;   /* 次要背景 */
--text-primary: #f0f6fc;   /* 主要文字 */
--text-secondary: #8b949e; /* 次要文字 */
--accent: #238636;         /* 強調色(綠色) */
--border: #30363d;         /* 邊框色 */
```

#### 通用色彩建議
```
- 使用高對比度配色
- 避免純黑(#000000)和純白(#ffffff)
- 主色調不超過3種
- 保持品牌色的一致性
- 考慮色盲友善的配色
```

### 2. 字體規範

#### 推薦字體

```
英文: 
- 無襯線: Inter, Roboto, Source Sans Pro
- 等寬: JetBrains Mono, Fira Code, Monaco

中文:
- 無襯線: 思源黑體, 蘋方, 微軟正黑體
- 等寬: Source Han Mono, 等距更紗黑體
```

#### 字號標準
```
- 標題: 24px+ (清晰可讀)
- 內文: 16px+ (舒適閱讀)
- 說明: 14px+ (最小可讀)
- 程式碼: 14px+ (等寬字體)
```

### 3. 佈局原則

#### 網格系統
```
- 使用8px基礎網格
- 保持元素對齊
- 適當的留白空間
- 層次分明的資訊架構
```

#### 構圖技巧
```
- 三分法則構圖
- 黃金比例分割
- 對稱或平衡佈局
- 引導線和焦點設計
```

## 📁 檔案管理

### 目錄結構
```
project-root/
├── .github/
│   └── images/           # GitHub專用圖片
│       ├── hero.png     # 社群媒體預覽圖
│       └── logo.svg     # 專案Logo
├── docs/
│   └── images/          # 文檔配圖
│       ├── installation/
│       ├── tutorials/
│       └── screenshots/
├── assets/              # 通用資源
│   ├── icons/          # 圖示檔案
│   ├── screenshots/    # 應用程式截圖
│   └── demos/          # 演示檔案
└── README.md
```

### 命名規範

#### 檔案命名模式
```bash
# 功能型命名
feature_[功能名稱]_[狀態].[副檔名]
# 範例: feature_stitching_result.png

# 序號型命名
[序號]_[描述].[副檔名]
# 範例: 01_main_interface.png

# 語義型命名
[用途]_[詳細描述].[副檔名]
# 範例: hero_banner_dark_theme.png
```

#### 命名最佳實踐
```
✅ 推薦:
- installation_step_1.png
- demo_video_editing.gif
- icon_app_logo.svg
- screenshot_main_ui.png

❌ 避免:
- 螢幕截圖2023.png
- IMG_001.jpg
- 圖片1.png
- Untitled.png
```

## 📝 內容要求

### 1. 隱私和安全

#### 敏感資訊處理
```
需要避免或模糊處理:
- 個人姓名和聯絡方式
- 真實的電子郵件地址
- API金鑰和權杖
- 私人檔案路徑
- 敏感的業務資料
```

#### 範例資料使用
```
推薦使用:
- Lorem ipsum文字
- 範例電子郵件 (example@example.com)
- 虛構的公司名稱
- 開源或免費的範例圖片
- 測試使用者名稱 (testuser, demo, etc.)
```

### 2. 版權合規

#### 圖片使用準則
```
✅ 安全使用:
- 自己創建的原創內容
- CC0授權的免費圖片
- 開源專案的官方素材
- 購買的商業授權圖片

❌ 避免使用:
- 網路隨意下載的圖片
- 有版權爭議的內容
- 他人專案的截圖 (未授權)
- 商業軟體的介面 (未授權)
```

#### 素材來源推薦
```
免費圖片:
- Unsplash (unsplash.com)
- Pexels (pexels.com)
- Pixabay (pixabay.com)

圖示資源:
- Feather Icons (feathericons.com)
- Heroicons (heroicons.com)
- Tabler Icons (tabler-icons.io)

字體資源:
- Google Fonts (fonts.google.com)
- Adobe Fonts (fonts.adobe.com)
```

### 3. 內容品質

#### 介面截圖要求
```
✅ 高品質截圖:
- 完整的功能介面
- 清晰的文字和圖示
- 真實的使用場景
- 合理的資料展示
- 統一的介面狀態

❌ 低品質截圖:
- 模糊不清的畫面
- 不完整的介面
- 空白或無內容介面
- 錯誤狀態的介面
- 開發者工具痕跡
```

## 🌐 平台適配

### 1. GitHub平台最佳化

#### Social Preview最佳化

```
尺寸: 1200x630
格式: PNG/JPG
要求:
- 清晰的專案標題
- 簡潔的功能描述
- 吸引人的視覺設計
- 品牌元素展示
```

#### README顯示最佳化

```
- 使用相對路徑引用圖片
- 如若必要提供高清和普通兩個版本
- 考慮深色主題的顯示效果
- 最佳化行動裝置顯示效果
```

### 2. 多平台考慮

#### 外掛程式/應用程式商店
```
VS Code Marketplace:
- 推薦: 1376x768
- 最小: 1200x600
- 格式: PNG
- 品質: 高品質無損

Apple App Store (iOS/macOS):
- iOS截圖: 1290x2796 (iPhone 16 Pro)
- iPad截圖: 2048x2732 (12.9" iPad Pro)
- macOS截圖: 1280x800 (最小)
- 格式: PNG/JPG
- 要求: 實際裝置截圖，展示真實使用場景

Google Play Store (Android):
- 手機截圖: 1080x1920 (最小)
- 平板截圖: 1200x1920 (7吋) / 1600x2560 (10吋)
- 格式: PNG/JPG
- 數量: 最少2張，最多8張

Microsoft Store (Windows):
- 截圖: 1366x768 (最小)
- 推薦: 1920x1080
- 格式: PNG/JPG/JPEG
- 比例: 16:9 推薦

Chrome Web Store:
- 截圖: 1280x800 或 640x400
- 宣傳圖片: 440x280
- 格式: PNG/JPG
- 品質: 高解析度

Firefox Add-ons:
- 截圖: 最大1425x750
- 圖示: 64x64, 32x32
- 格式: PNG/JPG
- 要求: 清晰展示功能
```

#### 社群媒體分享
```
Twitter: 1200x675 (16:9)
LinkedIn: 1200x627
Facebook: 1200x630
Reddit: 1200x630
```

## 🏆 最佳實踐

### 1. 截圖技巧

#### 準備工作
```bash
# 1. 環境準備
- 使用高解析度顯示器 (2K/4K)
- 設定100%縮放比例
- 關閉不相關應用程式
- 清理桌面和工作列

# 2. 瀏覽器設定
- 使用無痕模式
- 停用擴充功能
- 設定標準視窗大小
- 隱藏開發者工具
```

#### 截圖工具推薦
```
macOS:
- 系統內建截圖 (Cmd+Shift+4)
- CleanShot X (專業工具)
- Skitch (帶標註功能)

Windows:
- 系統截圖工具 (Win+Shift+S)
- Greenshot (開源免費)
- Snagit (專業工具)

跨平台:
- LightShot
- Flameshot (開源)
```

### 2. 圖片最佳化技巧

#### 壓縮最佳化

```bash
# ImageOptim (macOS)
imageoptim *.png

# TinyPNG (線上)
# 造訪 tinypng.com

# 命令列工具
# PNG最佳化
pngquant --quality=65-80 input.png
optipng -o7 input.png

# JPG最佳化
jpegoptim --max=85 input.jpg

# WebP轉換
cwebp -q 80 input.png -o output.webp
```

#### 批次處理
```bash
# 批次調整尺寸
mogrify -resize 1280x720 *.png

# 批次格式轉換
for file in *.png; do
    cwebp -q 80 "$file" -o "${file%.png}.webp"
done

# 批次重新命名
rename 's/Screenshot/screenshot/' *.png
```

### 3. 可存取性最佳化

#### Alt Text撰寫

```markdown
<!-- ✅ 好的Alt Text -->
![主介面顯示圖片拼接參數，頂部裁切設定為20%，底部設定為15%](screenshots/main_interface.png)

<!-- ❌ 差的Alt Text -->
![截圖](screenshots/main_interface.png)
```

#### 響應式顯示
```html
<!-- 提供多尺寸版本 -->
<picture>
  <source media="(max-width: 600px)" srcset="screenshot_mobile.png">
  <source media="(max-width: 1200px)" srcset="screenshot_tablet.png">
  <img src="screenshot_desktop.png" alt="Description">
</picture>
```

### 4. 版本控制

#### Git LFS使用
```bash
# 初始化LFS
git lfs install

# 追蹤大檔案
git lfs track "*.png"
git lfs track "*.gif"
git lfs track "*.jpg"

# 提交LFS設定
git add .gitattributes
git commit -m "Add LFS tracking for images"
```

#### .gitignore設定
```gitignore
# 忽略暫存圖片檔案
*.tmp
*_temp.*
*_backup.*

# 忽略原始高清檔案 (如果有壓縮版本)
*_original.*
*_hd.*

# 忽略系統產生的縮圖
Thumbs.db
.DS_Store
```

## 📊 品質檢查清單

### 發佈前檢查
```markdown
## 技術品質
- [ ] 圖片格式正確 (PNG/JPG/WebP/SVG)
- [ ] 檔案大小合理 (<2MB普通圖片, <3MB動畫)
- [ ] 解析度足夠 (最小800px寬度)
- [ ] 色彩空間正確 (sRGB)

## 視覺品質
- [ ] 圖片清晰，無模糊
- [ ] 色彩飽和，對比度適中
- [ ] 構圖合理，重點突出
- [ ] 風格統一，專業美觀

## 內容品質
- [ ] 介面完整，功能清晰
- [ ] 文字可讀，資訊準確
- [ ] 無敏感資訊洩露
- [ ] 使用合規的範例內容

## 功能完整性
- [ ] 涵蓋主要功能點
- [ ] 展示核心價值主張
- [ ] 包含使用場景演示
- [ ] 提供操作流程指引

## 國際化考量
- [ ] 使用英文介面 (如果多語言)
- [ ] 避免文化特定元素
- [ ] 圖示含義通用明確
- [ ] Alt text描述準確
```

## 📚 參考資源

### 設計靈感
- [GitHub Explore](https://github.com/explore) - 優秀開源專案
- [Product Hunt](https://producthunt.com) - 產品展示案例
- [Dribbble](https://dribbble.com) - UI設計作品
- [Behance](https://behance.net) - 品牌設計案例

### 工具推薦
- **設計工具**: Figma, Sketch, Adobe XD
- **截圖工具**: CleanShot X, Greenshot, Flameshot
- **最佳化工具**: ImageOptim, TinyPNG, Squoosh
- **動畫製作**: LICEcap, GIPHY Capture, ScreenToGif

### 學習資源

- [GitHub Docs - Social Preview](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/customizing-your-repositorys-social-media-preview)
- [Material Design Guidelines](https://material.io/design)
- [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/)

