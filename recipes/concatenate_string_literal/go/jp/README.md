文字列リテラル（ダブルクォーテーション（"）で囲んだ文字列）を結合します。
単純に結合するには、＋演算子を使用します。
ただし、＋演算子で結合すると、結合するたびに文字列オブジェクトが生成されます。
bytes.Bufferを使用すると、文字列はバッファ内に保持され、無駄に文字列オブジェクトが生成されることを防ぎます。
