# Karabiner-custom (usagizmo-custom.json)

USキーボードで日本語を使用するための[Karabiner-Elements](https://karabiner-elements.pqrs.org/)の設定集です。

- `control` を単体で押したときに、`英数` も送信する
- `caps_lock` を単体で押したときに、`英数` も送信する
- `command（左）` を単体で押したときに、`英数` も送信する
- `command（右）` を単体で押したときに、`英数` も送信する
- `shift（左）` を単体で押したときに、`英数` も送信する
- `shift（右）` を単体で押したときに、`英数` も送信する
- `option（左）` を単体で押したときに、`英数` も送信する
- `option（右）` を単体で押したときに、`英数` も送信する
- `control` を押したときに、`英数` も送信する
- `escape` を押したときに、`英数` も送信する
- `control+c` を押したときに、`英数` も送信する
- `option（左）` を押したときに、`英数` も送信する
- `option（右）` を押したときに、`英数` も送信する
- `command（左）` を単体で押したときに、`かな` も送信する
- `command（右）` を単体で押したときに、`かな` も送信する
- `shift（左）` を単体で押したときに、`かな` も送信する
- `shift（右）` を単体で押したときに、`かな` も送信する
- `control+shift` を押したときに、`かな` を送信する
- `shift+space` を押したときに、`かな` を送信する
- `control+;` を押したときに、`enter` を送信する
- `option（右）` を押したときに、`command` を送信する
- `option（右）` を押したときに、`command` を送信する（＋単体かな）
- `control（右）` を押したときに、`option` を送信する
- `control（右）` を押したときに、`option` を送信する（＋単体かな）

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
