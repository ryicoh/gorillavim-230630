# ファイル検索

`path` で設定して`:find` で検索する


1. dotfiles のファイルを再帰的に検索対象にする

```vimscript
:set path=dotfiles/**
```

2. vimrc を検索してみる

<C-d>で候補が見れる vだけだとこんな感じ

```vimscript
:find v<C-d>
./dotfiles/vim/     sonictemplate/vim/  vimrc               vue/
```

vimr まで入れると一つに絞れる

```vimscript
:find vimr<C-d>
vimrc
```

<Tab> と <S-Tab> で選ぶ
```vimscript
:fin vi<C-d><S-Tab>
```

