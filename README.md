# VUE VITE專案

使用 vue 3 vite進行開發

## 架構

```sh
vite.config.js 匯出設定(摸組化輸出的檔案名稱)

src/main.js 主要設定
src/views/view 各頁面撰寫區
src/views/layout 共用版型(商品樓層與手機版選單)
          - banner.vue 左右banner輪播翻轉
          - listF.vue 4小商品版型
          - listFCoverFlow.vue 展開扇形版型
          - listM.vue 2凸4小商品版型
          - listD.vue 5小商品版型
          - listH.vue 2凸3小版型
          - ProductTop.vue 上方商品輪播
          - mobile.vue 手機版置底選單
          - mobile2.vue 手機版置頂選單
          - mobileAi.vue 3c頁用手機版選單
          - mobile3.vue 熱門活動版本手機版選單

src/views/floor 樓層區
         - CommonFloor.vue 共用

src/views/components 常用功能
         - AllEvent.vue 全站活動
         - Tab.vue/TabContent.vue 頁籤
         - LeftAside.vue 左側選單+手機版
         - RightAside.vue 右側選單+手機版

src/AppComponent.vue 以這個vue來引入各頁面

src/globalMixin.js 撈取樓層商品api、與其他共用功能

```

## 此專案安裝步驟

```sh
環境建置:
*安裝node.js 可直接從官方下載(需要管理員權限進行安裝)，若沒有管理員權限可下載
nvs進行安裝(步驟如此連結:https://smlpoints.com/guide-nvs-switch-node-js-manager-without-admin-rights-windows-git-bash-cmd.html)
*安裝git bash(官網)
*安裝 git sourcetree(介面化檔案管理) 教學-> https://etrex.tw/free_chatbot_book/windows_dev/sourcetree.html

1. 在本機新增資料夾
2. git clone檔案下來(下載此專案或直接使用sourcetree載到本機資料裡)
3. 對此專案資料夾輸入 npm init 後 npm install 進行安裝npm 套件安裝
```
### 活動頁使用規則:https://tk3ctsannkuen-my.sharepoint.com/:w:/g/personal/tp030164_tk3c_tsannkuen_com/EdJQiERIf-FAnbtPJ2u8Ud4BJ1MY_heCTBu7PXLZb5oisA?e=awolNT

### 此專案在本機運作指令

```sh
npm run dev
```

### 此專案打包匯出檔案指令

```sh
npm run build
```

### 專案初始化

```sh
npm run init
```
