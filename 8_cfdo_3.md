# フォルダ内文字列置換

Quickfix List に入れてから、`cfdo` する


ユーザ名 (skanehira) を置換してみる

1. まずは検索する

```
:vim skanehira dotfiles/**
```

2. Quickfix Listに対してcfdo

置換して保存するのを繰り返す

```
:cfdo %s/skanehira/gorilla/g | w
```
