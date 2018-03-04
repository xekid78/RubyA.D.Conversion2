# RubyA.D.Conversion2
システム日付の西暦から平成何年かを割り出す

## 処理
Timeクラスのyearメソッドを使い平成何年かを出力する。

## コード
```
seireki = Time.now.year
heisei = seireki - 1988
puts "西暦#{seireki}年は平成#{heisei}年です。"
```

## 出力例  
```
西暦2018年は平成30年です。
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
