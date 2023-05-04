# AMReX
> [About AMReX](https://www.youtube.com/watch?v=4CvjtfvBhGs)
> [適合格子法](https://www.fluid.sci.waseda.ac.jp/crest/Presen_YMatsuo.pdf)

## 概要
AMReXは、時間発展型の偏微分方程式を解くためのツールであり、Adaptive Mesh Refinement (AMR) を特徴としている．  
その汎用性から，偏微分方程式の解法以外の用途にも適用可能である．例えば，PeleLMは反応性流体解析ソフトとして，AMReXを活用して開発されている．  
また，MFIX-Exaは，多相流れを解析するために，同様にAMReXを利用したツールである．

## AMRの特徴
  - メッシュの細分化アルゴリズムを個々の目的や要望に応じて，柔軟に設定することができる．
  - メッシュのレベルに応じて離散化を適用することができる．
  - 非構造メッシュのメモリコストに比べて，少ないメモリ消費量で済む.

## AMReXの特徴
  - C++14/Fortranで書かれている．
  - 多種の並列化に対応している（MPI，MPI+X）．


