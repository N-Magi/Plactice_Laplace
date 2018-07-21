# Plactice_Laplace
ラプラス方程式の課題計算ソフトです。
## 注意事項
安易にマルチスレッド化しているので収束回数にばらつきが生じています。

なので、収束回数を数回取り、平均化して使用ください。

## コンポーネント情報
計算アルゴリズムは、 `Model/Laplace.cs`　にあります。
表示アルゴリズムは、 `Model/Images.cs`　にあります。   

## 使用方法
- 計算したい計算方法で計算を行ってください。
- ラジオボタンで逐次代入法とガウス・ザイゼル法と切り替えられます。
- `収束基準`を使用する場合は`繰り返し回数`を十分に多きくして使用してください
- `収束基準`が`0`の時は`繰り返し回数`の回数分だけ計算を行います。
- `加速係数`を使用するときはその上の`加速を行わない`のチェックボックスのチェックを消してください。
- `加速係数`が`0`の時加速は行われず通常の計算を行います。

## 開発環境
- `Visual Studio 2017 Community`

## 規約
- MITLicence
