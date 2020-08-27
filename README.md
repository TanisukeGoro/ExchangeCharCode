ファイルの文字コード一括変換スクリプト  
Batch conversion of the character code of the specified file extension in the folder.
====

> * プログラミング学習した本当に最初の頃に書いたのでリーダブルコードとはかけ離れています。ごめんね


研究データの一括変換が非常に厄介だったのでフォルダを与えるとその中の指定拡張子ファイルの文字コードを変換するスクリプトを作成した。  
Macでのみ検証済み。Windowsでも動作はするようだが、出力文字のカラー化に対応していない。

## Useage

### Exchange File Char Code

`sh ConvertCharCode.sh pathToFolder1 pathToFolder2 pathToFolder3` 

### Option

- `-r` :  Replace the converted file with the original
- `-e value`: Convert a file with a specified extension (default: .TXT) 

## Author

[TanisukeGoro](https://github.com/TanisukeGoro)
