# 組裝說明（Building Guide） （WIP）

## 安全注意事項

- 使用電烙鐵時注意環境通風。
- 部分零件在壓製熱壓螺母時需要用手做固定及公差微調，注意不要燙傷。
- 3D列印的部件相當脆弱，務必不要過度用力彎折、摔、掉落、螺絲硬鎖等行為。

### 工具準備

- 溫控電烙鐵及相關工具配件。
- 剝線鉗。
- 美工刀及切割墊。
- 精密螺絲起子。
- 寬頭鑷子。
- 烙鐵工作臺（帶夾子固定、吸磁固定為佳）
- 熱風槍。
- 1u鍵帽若干。

### 材料準備

- 熱壓螺母及螺絲的使用量相當高，推薦直接買一包備著用。
- 能夠在同一個賣場買就在同一個賣場買，比較省錢。
- 推薦使用單格電路板組裝，邏輯比較好懂，也比較好拉矩陣。

| 材料名稱 | 左右手合計最大用量 | 相關連結 |
| -------- | ---- | ------ |
| M2x3x3.2mm 熱壓螺母 | 76 | [Link](https://detail.tmall.com/item.htm?_u=n3lhas116742&id=673922235027&spm=a1z09.2.0.0.18132e8d8onSZm) |
| M3x3x4.2mm 熱壓螺母 | 60 | [Link](https://detail.tmall.com/item.htm?_u=n3lhas116742&id=673922235027&spm=a1z09.2.0.0.18132e8d8onSZm) |
| M2x5mm 薄頭螺絲 | 50 | [Link](https://detail.tmall.com/item.htm?_u=n3lhas111f9d&id=595144522232&spm=a1z09.2.0.0.18132e8d8onSZm) |
| M2x8mm 薄頭螺絲 | 22 | [Link](https://detail.tmall.com/item.htm?_u=n3lhas111f9d&id=595144522232&spm=a1z09.2.0.0.18132e8d8onSZm) |
| M3x6mm 薄頭螺絲 | 52 | [Link](https://detail.tmall.com/item.htm?_u=n3lhas111f9d&id=595144522232&spm=a1z09.2.0.0.18132e8d8onSZm) |
| M3x8mm 薄頭螺絲 | 2 | [Link](https://detail.tmall.com/item.htm?_u=n3lhas111f9d&id=595144522232&spm=a1z09.2.0.0.18132e8d8onSZm) |
| M3x6mm 扁頭螺絲 | 8 | [Link](https://detail.tmall.com/item.htm?_u=n3lhas11735e&id=624733978863&spm=a1z09.2.0.0.18132e8d8onSZm) |
| 1/4" 高6.35mm 熱壓螺母 | 4 | [Link](https://item.taobao.com/item.htm?spm=a1z0d.6639537/tb.1997196601.82.3d385886uNMAFA&id=662099841891) |
| Pro Micro 5V16M | 2 | [Link](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.18132e8d8onSZm&id=682095206177&_u=n3lhas111158) |
| TRRS座 | 2 | [Link](https://detail.tmall.com/item.htm?_u=n3lhas11d3b2&id=609114863623&spm=a1z09.2.0.0.18132e8d8onSZm) |
| 28AWG 白色矽膠線 | N/A | [Link](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.18132e8d8onSZm&id=45709657945&_u=n3lhas114d82) |
| 28AWG 紅色矽膠線 | N/A | [Link](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.18132e8d8onSZm&id=45709657945&_u=n3lhas114d82) |
| 2.54mm 圓排針公 | N/A | [Link](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.18132e8d8onSZm&id=627707215622&_u=n3lhas11f450) |
| 2.54mm 圓排針母 | N/A | [Link](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.18132e8d8onSZm&id=627818679656&_u=n3lhas11659a) |
| 外徑1mm 熱縮套管 | N/A | [Link](https://shopee.tw/(%E5%8F%B0%E7%81%A3%E5%A4%A7%E5%BB%A0%E8%A3%BD)%E9%80%8F%E6%98%8E%E7%86%B1%E7%B8%AE%E5%A5%97%E7%AE%A1%E8%B3%A3%E5%A0%B4-%E7%86%B1%E7%B8%AE%E5%A5%97%E7%AE%A1-%E9%98%B2%E5%A1%B5%E5%A5%97-%E7%B5%95%E7%B7%A3%E7%AE%A1-%E7%AB%AF%E5%AD%90%E7%AE%A1-%E7%B5%95%E7%B7%A3-%E7%86%B1%E7%B8%AE%E7%AE%A1-%E7%86%B1%E7%B8%AE%E8%86%9C-%E7%86%B1%E7%B8%AE%E5%A5%97-%E8%9D%A6%E7%AB%BF-%E9%87%A3%E7%AB%BF-%E7%AB%AF%E5%AD%90-i.42958561.3656848147) |
| 單格電路板 | 56 | [Link](https://www.pragmatic.com.tw/shop/single-switch-pcb-101#attr=) |
| IN1418 貼片式T4 開關二級管 | 56 | [Link](https://detail.tmall.com/item.htm?_u=n3lhas111e26&id=614392649945&spm=a1z09.2.0.0.18132e8d8onSZm) |

## 列印注意事項

- 根據需求先決定自己需要3x5、3x6或4x5、4x6等鍵盤主配列，如果不清楚的話，請先決定自己的鍵盤要幾排（Row）按鍵。
- 不知道拇指要幾顆按鍵，請全部列印出來。
- 這把鍵盤叫做探索者，就如其名，它需要你慢慢探索鍵盤按鍵中的奧祕。

## 配列部件表

- 部分組件為對稱設計，但檔案數量龐大，還是將組件建立成左右區分，方便大家列印時參考用。

| 部件名稱 | 左右區分 | 選項A | 選項B | 備註 |
| ------- | ------- | ----- | ----- | ---- |
| 直列定位板（column） | - | 3x1 | 4x1 | 5列鍵盤需列印10組、6列12組 |
| 底殼（bottom case） | Yes | 3x5 | 4x5 | - |
| 底殼拓展（bottom expand case） | Yes | 3x1 | 4x1 | - |
| 上框架（upper main frame） | Yes | 3x5 | 4x5 | 3x5、4x5不共用 |
| 共用下框（lower main frame） | Yes | - | - | 3x5、4x5通用 |
| 拓展框架（x1-main frame） | - | - | - | 一組左右拓展需列印4組 |
| 前方雲台插件（front basepart） | Yes | - | - | 左右邊可通用 |
| 拇指區基座（thumb area basepart） | Yes | - | - | - |
| 拇指定位板（x1-thumb plate） | - | - | - | 依據拇指按鍵數量列印 |
| 拇指底板AX（thumb AX plate） | Yes | AA（長板） | AB（短板） | 可連結基座 |
| 拇指底板BX（thumb BX plate） | Yes | BA（長板） | BB（短板） | 純拓展，左右通用 |
| 連結器（linker） | - | - | - | 左右通用，2組按鍵需用1組連結器 |

## 組裝步驟

- 3x5、3x6及4x5、4x6鍵盤配列安裝大同小異，這裡會以3x6+3鍵盤演示為主。


## 矩陣及手拉線



## QMK韌體修正
