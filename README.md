# 網頁上的尺寸

## CSS `width: 1cm`

- 為列印用途。
- 畫在不同螢幕上，可能會呈現不同的尺寸。

## JavaScript `window.devicePixelRatio`

- 為 CSS 裡的 `1 pixel` 對實際 `1 pixel` 的比值。
- `1 cm` 換算為 `N px`： 37.7952755906 * window.devicePixelRatio
- `1 pt` 換算為 `N px`: (96/72) * window.devicePixelRatio

## 參考文件

- [Dot-per-pixel 與 Dot-per-inch](https://pixelthing.medium.com/jonesing-for-dpi-and-dppx-45c6245f6ffc)
- [Resolution Takeaways](https://ryanve.com/_php/airve/chromosome/request.php?request=lab/resolution/)
