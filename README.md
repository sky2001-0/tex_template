##

私用 LaTeXテンプレート

## 備考
which, lsが通ってもパスが通っていない場合がある。以下解決法。

~/.bash_profile を開き、以下を追加。

    export PATH=/Library/TeX/texbin:$PATH

ターミナル上で、以下を実行。

    source ~/.bash_profile


## 参考

https://zenn.dev/umi_mori/books/72d30926afbc24/viewer/473920
https://zenn.dev/umi_mori/books/72d30926afbc24/viewer/c4f8a3