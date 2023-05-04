# GMRES法の利用方法
    sampleプログラムを利用する上で，わからなかったことをまとめる．  
    参考文献:[Intel MKL 反復解法(大阪大学)](http://www.hpc.cmc.osaka-u.ac.jp/wp-content/uploads/2018/10/seminar21Nov2018suzuki.pdf)
  
  1. Matrix file (MTX)  
    [Matrix Market](https://math.nist.gov/MatrixMarket/index.html)にて，サンプル係数行列が公開されている．  
    ここで公開されているファイル形式をmtxファイル形式といい，ヘッダー部分を除けば非ゼロ要素の配列位置型で表すCOO型となっている．  
  
  2. Metis  
    サンプルプログラムは，Metisに依存している．Metisがなんの機能かよくわからない．  

  3. Intel MKL  
