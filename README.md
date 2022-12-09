# 基本操作

- 起動

```
tmux
```

- セッション一覧

```
tmux ls
```

- セッション再開

```
tmux a
```

```
tmux a -t 対象セッション名
```

- セッション終了

```
tmux kill-session
```

```
tmux kill-session -t 対象セッション名
```

(`tmux kill-session`は最新のセッション1つをkill)

- 名前つきセッションを作成

```
tmux new -s セッション名
```

# ショートカットキー

|コマンド|役割|
|----|----|
|`prefix+?`|キーバインド一覧|
|`prefix+s`|セッションの一覧表示|
|`prefix+c`|新規ウィンドウの作成・追加|
|`prefix+w`|ウィンドウの一覧|
|`prefix+&`|ウィンドウの破棄|
|`prefix+n`|次のウィンドウへ移動|
|`prefix+p`|前のウィンドウへ移動|
|`prefix+\|`|左右にペインを分割|
|`prefix+-`|上下にペイン分割|
|`prefix+h`|左のペインに移動|
|`prefix+j`|下のペインに移動|
|`prefix+k`|上のペインに移動|
|`prefix+l`|右のペインに移動|
|`prefix+H`|ペインを左にリサイズ|
|`prefix+J`|ペインを下にリサイズ|
|`prefix+K`|ペインを上にリサイズ|
|`prefix+L`|ペインを右にリサイズ|
|`prefix+x`|ペインを破棄|
|`prefix+space`|ペインのレイアウト変更|
|`prefix+C-o`|ペインの入れ替え|
|`prefix+{`|ペインの入れ替え(上方向)|
|`prefix+}`|ペインの入れ替え(下方向)|
|`prefix+[`|コピーモードの開始|
|`prefix+v`|コピー開始位置決定(viモード)|
|`prefix+y`|コピー終了位置決定(viモード)|
|`prefix+C-p`|コピー内容の貼付け|

