# Tello Scratch Extension for Chinese

## Thank mather for this better version than the factory default scripts
  below is the original instruction from mather

This is an extenstion scripts for [Scratch2 Offline Editor](https://scratch.mit.edu/download) to control [Tello](https://www.ryzerobotics.com/tello)

## Usage

See `Scratch README` at [Tello Downloads](https://www.ryzerobotics.com/tello/downloads).

- Use `TelloKanji.s2e` for `Tello.s2e`.
- Use `TelloScratchHelper.js` for `Tello.js`

## Difference from official scripts

- Japanese blocks.
- All Scratch blocks will pause until the command ends.

# Newly added by yiupa

- make speed setting workable
- change the Japanese to Chinese
- scratch can now read battery level and speed back from tello

# 繁體中文版Tello Scratch Extension

這是經改寫的繁體中文版Tello Scratch Extension

源於mather改寫的日語版本

相比廠家原版，mather版本引入了跟據當前飛行速度為每個命令加入了適當的延時。

原有版本沒有延時的，若多個命令從scratc快速傳給Tello就會因tello正在執行命令時，

因不能接收其後的命令引致程序執行錯誤。

mather改寫的版本speed命令有個bug已更正，
現版本加入了scratch可讀tello 電量和當前飛行速度。

## 使用

- 安裝 Scratch2 Offline Editor( https://scratch.mit.edu/download )

- 按於 (https://www.ryzerobotics.com/tello/downloads) 下載的 `Scratch README` 內指示做

- 用 `TelloKanji.s2e` 取代 `Tello.s2e`
- 用`TelloScratchHelper.js` 取代 `Tello.js`

