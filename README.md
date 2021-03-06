# METRO_Redux_Start_Fixed_Tools
ツール名：METRORedux_IME問題回避ツール  
製作者：メトロスキー

## 概要
- システムの⾔語設定を⽇本語にしている状態でMETRO Reduxを起動した場合に、  
  ⽇本語IME(CTFローダー)のCPU/メモリ使⽤率が⾼騰する問題を回避するためのツールです。
- システムの⾔語設定を事前に変更することで回避できることがわかっており、  
  それを⾃動で実施してからゲームを起動する処理を⾏います。

## IME問題によるデメリット
- ⽇本語IME(CTFローダー)のCPU/メモリ使⽤率が⾼騰することで、下記のデメリットが発生する
  - ゲーム終了後に⽇本語⼊⼒ができなくなる
  - ゲームのパフォーマンスが落ちる
  - CPUの温度が上がりファンの⾳がうるさくなる
  - 電気を無駄に消費する
    

## ツールの機能
1. ゲーム起動後の⽇本語IME(CTFローダー)の問題が起こらないようにするため、  
   ゲーム起動前にシステムの⾔語設定を英語優先にする。  
   ⇒⼿動で設定する必要がなくなります
2. ゲームを起動する  
   ⇒このツールを起動すると、ゲームも起動します
3. ゲーム終了時にはシステムの⾔語設定を起動前の状態に戻す。  
   ⇒⼿動で戻す必要がなくなります
4. ⾔語設定の初期化ツールを⽤意  
   ⇒初回起動時の⾔語設定をバックアップしておきます。何らかの問題が発⽣した際に  
   　この初期化ツールを利⽤することで、⾔語設定を初回起動時の状態に戻せます。

## 利用規約

- 本ツールを利⽤したことで、万が⼀お使いのPCやゲームデータが破損した場合でも、  
  責任は取りかねます。⼤変恐縮ですが⾃⼰責任での利⽤としてください。
- 再配布は禁⽌です。
