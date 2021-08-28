# Karabiner-custom (usagizmo-custom.json)

USキーボードで日本語を使用するための設定集です。

- controlキーを単体で押したときに、英数キーも送信する
- controlキーを押したときに、英数キーも送信する
- escapeキーを押したときに、英数キーも送信する
- control+cを押したときに、英数キーも送信する
- shiftキーを単体で押したときに、かなキーも送信する
- control+shiftを押したときに、かなキーを送信する
- shift+spaceを押したときに、かなキーを送信する
- control+;を押したときに、enterキーを送信する

## Karabiner への登録方法

```bash
cd ~/.config/karabiner/assets/complex_modifications
curl -O https://raw.githubusercontent.com/usagizmo/karabiner-custom/main/usagizmo-custom.json

# Developer
cd ~/.config/karabiner/assets/complex_modifications
ghq get git@github.com:usagizmo/karabiner-custom.git
ln ~/ghq/github.com/usagizmo/karabiner-custom/usagizmo-custom.json .
# シンボリックリンクだと動作しないためハードリンク
```