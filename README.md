# HSPCL32 minor Version 2.1

HSPCL32 minor Version 2.1は、pippi氏が開発したHSPCL version 2.0 をHSP3.6bate5以降でも使えるようにした修正版マイナーバージョンです。

OpenGLを使用していないため、OpenGL系HSP3モジュールとの併用が可能です。

# HSPCL32 minor Version 2.1 とは
HSPCL32 minor Version 2.1 は、HSP3でOpenCLを扱う拡張モジュールです。OpenCL C言語を扱えます。

モデル化された配列変数（行列）を非常に高速に処理できる他、並列計算もできるようになります。

例えば、このようなことが可能になります。

標準HSP3で画像処理を高速に行える

HGIMG3やHGMG4で大量のパーティクルの処理が高速に行える

独自の物理演算エンジンを実装できる

モデル化されたAIの処理を高速に行える

顔認識処理を高速に行える

また、単にOpenCLで処理を行うだけでも、HSP3言語と比較して非常に高速に処理できるようになります。

# HSPCL32_FIX(HSPCL32 Version 4.02)との比較
HSPCL32_FIX(HSPCL32 Version 4.02)とは、HSPCL32 Version 4.02をHSP3.6bate5以降でも使えるようにした修正版です。

HSPCL32_FIX(HSPCL32 Version 4.02)はOpenCLと同時にOpenGLも扱える高性能なモジュールですが、その反面、OpenGLを使った他のHSP3モジュールと連携が取れないというデメリットがありました。

それに対してこのHSPCL32 minor Version 2.1はOpenGLを扱っていないため、OpenGLを使っている他のHSP3モジュールと連携が取れるようになっています。例えば、HGIMG4と連携が取れることを確認済みです。
