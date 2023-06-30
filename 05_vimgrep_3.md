# フォルダ内文字列検索

`vimgrep` を使ってQuickfix Listに入れる


## autocmd を検索してみる

```vimscript
:vim /autocmd/ dotfiles/**
```

`:cwindow` で開いて、`:cclose`で閉じる
次のマッチは、`:cnext`、ファイルをまたぐ次のマッチは、`:cnfile`
