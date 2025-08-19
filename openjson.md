這是一些關於 JSON 資料類型的學習筆記：

## JSON 支援的資料類型

- 字符串：用雙引號括起來的字串，如 `"name": "Alice"`
- 數字：有效的整數或浮點數，如 `"age": 25`
- 布林值：`true` 或 `false`
- null：表示空值，如 `"value": null`

## JSON 不支援的元素
- `NaN` 和 `undefined` 不是合法的 JSON 值。

## 解決方案
- 將 `NaN` 改為 `null`
