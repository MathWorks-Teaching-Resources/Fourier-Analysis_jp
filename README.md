
<a id="T_DEF03274"></a>

# <span style="color:rgb(213,80,0)">フーリエ解析</span>
<a id="H_053613DF"></a>

[![View on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/182739?s_tid=prof_contriblnk) or [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Fourier-Analysis_jp&project=fourier-analysis.prj&file=README.mlx)

[![MATLAB Versions Tested](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FMathWorks-Teaching-Resources%2FFourier-Analysis_jp%2Frelease%2FImages%2FTestedWith.json)](https://MathWorks-Teaching-Resources.github.io/Fourier-Analysis_jp)

**Curriculum Module**

_Created with R2021b. Compatible with R2024a and later releases._

# 情報

このカリキュラムモジュールには、フーリエ解析の基本概念を教えるインタラクティブな[MATLAB® ライブスクリプト](https://www.mathworks.com/products/matlab/live-editor.html)と[MATLAB® アプリ](https://www.mathworks.com/products/matlab/app-designer.html)が含まれています。

<a id="H_F00D98E4"></a>

## 背景

このモジュールは、信号処理の観点から、入門レベルの信号システムのコースに適したレベルで教えられます。最初のレッスンでは、学生はアプリを使ってフーリエ級数を視覚化し、周波数領域についての直感を養います。続くレッスンでは、複素フーリエ級数、フーリエ変換、離散フーリエ変換を学びます。学生が進むにつれて、アプリの利用から自分でコードを書いて信号を解析する段階へと移行します。モジュール全体を通して、学生は録音された音声信号の解析にフーリエ解析を用います。


ライブスクリプト内の指示により、演習や実際の操作の手順を案内します。各ライブスクリプトは、セクションごとに実行しながら始めてください。スクリプトやセクションの実行を途中で停止したい場合（例：アニメーションが進行中の場合）、MATLABツールストリップの**ライブエディター**タブ内の**実行**セクションにある<img src="./Images/image_0.png" width="19" alt="image_0.png">停止ボタンを使用してください。

このモジュールは英語から自動翻訳されています。

## お問い合わせ

解答は教員からのリクエストに応じて提供可能です。解答のリクエスト、フィードバックの提供、ご質問がある場合は、[MathWorks 教育リソースチーム](mailto:onlineteaching@mathworks.com)までご連絡ください。

<a id="H_30BC7141"></a>

## 前提条件

このモジュールは、これらのスクリプトに必要な最小限のMATLAB知識を前提としていますが、[MATLAB入門](https://matlabacademy.mathworks.com/details/matlab-onramp/gettingstarted)を活用することで、ライブスクリプトやMATLAB構文に慣れるためのリソースとして利用できます。

<a id="H_330E72C3"></a>

## はじめに
### モジュールへのアクセス
### **MATLAB Onlineの場合:**

[<img src="./Images/image_1.png" width="136" alt="image_1.png">](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Fourier-Analysis&project=fourier-analysis.prj&file=README.mlx)リンクを使用してモジュールをダウンロードしてください。ログインまたはMathWorksアカウントの作成を求められます。プロジェクトが読み込まれ、開始するための複数のナビゲーションオプションを備えたアプリが表示されます。

### **デスクトップの場合:**

このリポジトリをダウンロードまたはクローンしてください。MATLABを開き、これらのスクリプトが含まれるフォルダーに移動し、[fourier\-analysis.prj](<matlab: openProject("fourier-analysis.prj")>)をダブルクリックします。必要なファイルがMATLABパスに追加され、開始場所を尋ねるアプリが開きます。


必要なすべての製品（[下記に一覧](#H_E850B4FF)）がインストールされていることを確認してください。製品を追加する必要がある場合は、Add\-On Explorerを使って追加してください。アドオンをインストールするには、**ホーム**タブに移動し、<img src="./Images/image_2.png" width="16" alt="image_2.png"> **アドオン** > **アドオン入手**を選択します。

<a id="H_E850B4FF"></a>

## 製品

MATLAB®、Symbolic Math Toolbox™

<a id="H_E8C62B23"></a>

# スクリプト
## [**FourierSeries.mlx**](./Scripts/FourierSeries.mlx)
|  | **このスクリプトで学生は...** <br>  | **実験課題** <br>   |
| :-- | :-- | :-- |
| <img src="./Images/image_3.png" width="267" alt="image_3.png"> <br>  | $\bullet$ 時間領域と周波数領域で信号を比較 <br> $\bullet$ 周波数領域で音声信号を解析 <br> $\bullet$ フーリエ級数を視覚化 <br> $\bullet$ フーリエ級数における位相シフトの表現方法を説明 <br> $\bullet$ 振幅と位相について議論 <br>  | [Lab1\_FourierSeries.mlx](./Scripts/Lab1_FourierSeries.mlx) <br>   |

## [**ComplexFourierSeries.mlx**](./Scripts/ComplexFourierSeries.mlx)
|  | **このスクリプトで学生は...** <br>  | **実験課題** <br>   |
| :-- | :-- | :-- |
| <img src="./Images/image_4.png" width="267" alt="image_4.png"> <br>  | $\bullet$ 時間領域と周波数領域で信号を比較 <br> $\bullet$ 周波数領域で音声信号を解析 <br> $\bullet$ フーリエ級数を視覚化 <br> $\bullet$ フーリエ級数における位相シフトの表現方法を説明 <br> $\bullet$ 振幅と位相について議論 <br>  | [Lab2\_ComplexFourierSeries.mlx](./Scripts/Lab2_ComplexFourierSeries.mlx) <br>   |

## [**FourierTransform.mlx**](./Scripts/FourierTransform.mlx)
|  | **このスクリプトで学生は...** <br>  | **実験課題** <br>   |
| :-- | :-- | :-- |
| <img src="./Images/image_5.png" width="267" alt="image_5.png"> <br>  | $\bullet$ 時間領域と周波数領域で信号を比較 <br> $\bullet$ 周波数領域で音声信号を解析 <br> $\bullet$ フーリエ級数を視覚化 <br> $\bullet$ フーリエ級数における位相シフトの表現方法を説明 <br> $\bullet$ 振幅と位相について議論 <br>  | [Lab3\_FourierTransform.mlx](./Scripts/Lab3_FourierTransform.mlx) <br>   |

## [**DiscreteFourierTransform.mlx**](./Scripts/DiscreteFourierTransform.mlx)
|  | **このスクリプトで学生は...** <br>  | **実験課題** <br>   |
| :-- | :-- | :-- |
| <img src="./Images/image_6.png" width="267" alt="image_6.png"> <br>  | $\bullet$ 時間領域と周波数領域で信号を比較 <br> $\bullet$ 周波数領域で音声信号を解析 <br> $\bullet$ フーリエ級数モードを視覚化 <br> $\bullet$ フーリエ級数における位相シフトの表現方法を説明 <br> $\bullet$ 振幅と位相について議論 <br>  | [Lab4\_DFT.mlx](./Scripts/Lab4_DFT.mlx) <br>   |

# アプリ
| [フーリエ級数アプリ(sinまたはcosのみで波形の重ね合わせを表現)](<<matlab:run SinCosSeries.mlapp>;>)  <br>  | [フーリエ級数アプリ(sin項およびcos項の係数変更による合成波形の可視化)](<<matlab:run InteractiveFourierSeries.mlapp>;>) <br>  |  [振幅と位相での表現を可視化するアプリ](<<matlab:run MagnitudePhase.mlapp>;>)  <br>  | [複素フーリエ級数を可視化するアプリ](<<matlab:run ComplexFourierSeries.mlapp>>) <br>   |
| :-- | :-- | :-- | :-- |
| [<img src="./Images/image_7.png" width="186" alt="image_7.png">](<matlab:run SinCosSeries.mlapp>) <br>  | [<img src="./Images/image_8.png" width="186" alt="image_8.png">](<matlab:run InteractiveFourierSeries.mlapp>) <br>  | [<img src="./Images/image_9.png" width="186" alt="image_9.png">](<matlab:run MagnitudePhase.mlapp>) <br>  | [<img src="./Images/image_10.png" width="185" alt="image_10.png">](<<matlab:run ComplexFourierSeries.mlapp>>) <br>   |


# 教育者向けリソース
-  [MATLABを使って教える](https://www.mathworks.com/academia/educators.html) 


Copyright 2025 The MathWorks™, Inc

