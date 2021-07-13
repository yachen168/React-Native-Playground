# React-Native-Playground

## 如何運行 
參考 [RN Docs](https://reactnative.dev/docs/environment-setup)
### Android
法一: 使用 android studio
- 開啟 android studio 模擬器
- 執行:
```shell
yarn android
```

法二: USB 連接實體裝置
- 在實體裝置開啟`開發者模式` (設定 -> 關於手機 -> 軟體資訊 -> 點擊版本號碼欄位 7 下)
- 返回設定 -> 開發者人員選項 -> 開啟 USB 偵錯
- 連接 USB
- 執行 `adb devices` 確認裝置有連接
- 執行:
```shell
yarn android
```
### ios
法一: 使用 xcode
```shell
yarn ios
```