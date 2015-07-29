# display-none-behavior-in-ie9

IE9での display:none/block の切り替え処理で軽くハマったのでメモ。

IE9はレンダリング初期に display:none の要素の子要素を読み込んでいないかもしれない。
その可能性の検証と、同様の現象を回避する実装例。

# 実装例

http://bathtimefish.github.io/display-none-behavior-in-ie9
