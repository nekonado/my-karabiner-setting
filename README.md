# my-karabiner-setting

## About

- Karabiner-Elements の config ファイルの最新版を格納

## Usage

- Mac の`~/.config/karabiner/`配下に設定ファイルを格納して使用
- 本リポジトリは memo, bkup, web 共有のために使用

## Basic Policy

- Windows キーボードは Mac 風にキーアサインする
- Mac 標準のキーバインドには極力干渉しないようにキーアサインする

### ThinkPad TrackPoint Keyboard II

- Bleetooth 接続時に Mac 内蔵キーボードを無効化

#### Simple Rules

| From          | To                             | Description |
| ------------- | ------------------------------ | ----------- |
| Caps Lock     | Left Control                   | Mac style   |
| Windows       | Left Option                    | Mac style   |
| Left Alt      | Left Command                   | Mac style   |
| Right Alt     | Right Command                  | Mac style   |
| Center Button | Enter                          | thumb enter |
| Print Screen  | Command + Option + Control + 4 | for dev     |
| Right Control | F12                            | for dev     |
| Delete        | Command + Control + q          | Lock Screen |

#### Combination Rules

| From                   | To          | Description        |
| ---------------------- | ----------- | ------------------ |
| Riht Shit + ;          | ←           | HHKB style         |
| Riht Shit + /          | ↓           | HHKB style         |
| Riht Shit + [          | ↑           | HHKB style         |
| Riht Shit + '          | →           | HHKB style         |
| Caps Lock + TrackPoint | Page Scroll | ThinkPad Key style |

## Reference

- [Karabiner-Elements で Thinkpad Bluetooth Keyboard II を使いやすく設定する](https://norabal.com/programming/1822/)
- [ThinkPad キーボードを Mac で使うための Karabiner Elements の設定 最新版](https://takezoe.hatenablog.com/entry/2020/07/11/011118)
- [Karabiner-Element の設定例について - Qiita](https://qiita.com/s-show/items/40ad22c4ee4a0465fad5#%E4%BB%BB%E6%84%8F%E3%81%AE%E3%82%AD%E3%83%BC%E3%81%AB%E3%83%9E%E3%82%A6%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%83%E3%82%AF%E3%82%92%E5%89%B2%E3%82%8A%E5%BD%93%E3%81%A6%E3%82%8B)
- [[Mac] 他のキーボードに接続したら内蔵キーボードを無効化する方法](https://bamka.info/keyboard-mukoka)
