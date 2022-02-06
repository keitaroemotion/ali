# ali

Alias manager script.

You gotta create the ~/.ali file as:

```
money
    [alias] [URL] [Description]
    ra https://www.rakuten-sec.co.jp/session_error.html 楽天証券
    sbi https://www.netbk.co.jp SBI証券

manga
    cc https://ssl.dlsite.com/circle/circle/worklist DLSite(一覧)
```

## how to install

```
./install.sh
```

## usage

```
$ali
```

can let you select the root category, then once you selected the number of category
then you are navigated to the list of alias and url.

or

```
$ali [alias]
```

can lead you to open the URL without selecting categories.
