# 準備

## ダウンロード
LAMMPS の最新版(12Dec2018)をダウンロード。

**(注)** ファイルサイズ **_400MB_** 

+ [LAMMPSのダウンロードページ](https://lammps.sandia.gov/download.html)


## インストール
```
tar xvf lammps-stable.tar.gz
cd lammps-${version}/src
make -jN mpi
```
`-jN` の N のところには数字が入る。1より大きい値を指定するとmakeが並列で実行されるためコンパイルが早く終わる。

**(注)** Nはmake時の並列数。lammps実行時の並列数とは関係無し。

# 内容
1. [Kremer-Grestモデルの実行 00bench](./00bench) 
1. [リスタート方法 01restart](./01restart)
1. [トラジェクトリーデータ出力＆可視化 02dump](./02dump)
1. [せん断変形、伸長変形の方法 03deform](./03deform)
1. [応力の相関関数 04corr](./04corr)

