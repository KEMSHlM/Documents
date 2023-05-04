Title: AMReX Build Memo  
Date: 2023-03-24  
Category: memo  
Tags: AMReX, spack, Cmake, Gnu Make  
Slug: amrex-build-memo  

# AMReX Build Memo
リモート(Linux), ローカル上にAMReX(Linux, mac)を構築する手段を示す．
AMReXの構築手段には，spack, Cmake, Gnu Makeを用いた３つの方法がある．

## spack
spackを用いることで，AMReXの依存関係を自動的に解決することができる．そのため，複数の環境下での構築が容易である．インストールは簡単．git cloneコマンドを叩くだけ．  
おそらく，ITOは対応していない．ログインノード内で構築を試みたが，一部のライブラリがインストールできなかった． しかしながら，ローカルでの構築には有用である．   

- 特徴
    1. 自身のパッケージと組み合わせることができる．
        参考: [spackのパッケージシステム](https://spack.readthedocs.io/ja/latest/getting_started.html#:~:text=System-,Packages,-Once%20compilers%20are)  

## Gnu Make
