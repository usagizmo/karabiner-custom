# Karabiner-custom (usagizmo-custom.json)

USキーボードで日本語を使用するための[Karabiner-Elements](https://karabiner-elements.pqrs.org/)の設定集です。

- `control` キーを単体で押したときに、`英数` キーも送信する
- `shift（左）` キーを単体で押したときに、`英数` キーも送信する
- `shift（右）` キーを単体で押したときに、`英数` キーも送信する
- `control` キーを押したときに、`英数` キーも送信する
- `escape` キーを押したときに、`英数` キーも送信する
- `control+c` を押したときに、`英数` キーも送信する
- `shift（左）` キーを単体で押したときに、`かな` キーも送信する
- `shift（右）` キーを単体で押したときに、`かな` キーも送信する
- `control+shift` を押したときに、`かな` キーを送信する
- `shift+space` を押したときに、`かな` キーを送信する
- `control+;` を押したときに、`enter` キーを送信する
- `alt（右）` を押したときに、`command` キーを送信する
- `control（右）` を押したときに、`alt` キーを送信する

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
