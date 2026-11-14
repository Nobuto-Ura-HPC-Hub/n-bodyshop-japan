# 4096 粒子の球状星団の衝突

<video src="../media/plummer-4096.mp4" controls loop muted playsinline width="520"></video>

2 つの球状星団（Plummer モデル）を衝突させました。

| 項目 | 値 |
|------|----|
| 粒子数 | 4096 |
| 初期条件 | Plummer 球 2 つ |
| 時間刻み | 1/64（0.015625） |
| ステップ数 | 2000 |
| ソフトニング（ε²） | 1/128（0.0078125） |
| 単位 | N 体の単位（G = 1） |
| エネルギーの相対誤差（最後） | 5.2 × 10^-4 |
| 1 ステップの時間 | 4.245 ms |
| 実行環境 | MN-Core 2（PFCP の実機）、Open MN-Core 2 SDK の MNCL（登戸浦版） |

[トップへ](../index.md)
