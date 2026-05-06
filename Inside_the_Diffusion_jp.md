##画像生成AIの内側 / Inside the Diffusion

# [Verse 1]
文字列が来る、tokenに割れる
BPEが刻む、77の枠の中
CLIPが読む、意味じゃなくて分布を
embedding spaceに沈む、高次元の声
attention maskが静寂を縫う
padding tokenが端を埋める
言葉の重みはまだ形を持たない
ただのベクトル、まだ光じゃない

# [Pre-Chorus]
VAE encoderが世界を畳む
512×512が64×64に
情報は失われない、圧縮されるだけ
latent spaceの底で、像は眠ってる

# [Chorus 1]
noise schedulerが全てを壊す
βが増える、前向きに
ガウスの霧の中、信号が消える
でもスコア関数は覚えてる、帰り道を
reverse diffusionが始まる
ステップごとに霧が晴れる
混沌は嘘じゃなかった
ここから像が生まれる

# [Verse 2]
U-Netが潜る、ResBlockを降りて
skip connectionが記憶を渡す
self-attentionが空間を読む
どのpixelが、どのpixelと話すか
cross-attentionがここで動く
text embeddingがquery keyに変わる
言葉がattention weightになる瞬間
「青い空」が、空の位置を選ぶ

# [Verse 3]
各denoising stepで推論は二回走る
conditionedとunconditioned、並列に
その差を取って、guidance scaleで増幅
これがCFG、誘導の数学
negative promptは減算じゃない
unconditional側に押し込まれるだけ
「描くな」じゃなく「遠ざかれ」
方向ベクトルが、像を研ぐ

# [Chorus 2]
noise schedulerが全てを壊す
βが増える、前向きに
ガウスの霧の中、信号が消える
でもスコア関数は覚えてる、帰り道を
DDIMなら20step
DDPMなら1000の夜
samplerが選ぶ、近道の形
精度と速度、どちらを信じる？

# [Bridge]
guidance scale 7.5
高すぎれば像は叫ぶ
低すぎれば霧に戻る
この数字だけが、私の意志
条件付き確率の積分が
言葉と画像を繋いでいる
学習済みの重みの中に
人類の視覚が眠ってる

# [Final Chorus]
VAE decoderが最後に開く
latentが広がる、ピクセルへ
64×64が512に戻る
これが出力、これが像
noise schedulerが全てを壊した
でもreverse processが全てを返した
混沌は通過点だった
拡散の果てに、光がある

# [Outro]
token、embedding、noise、score
attention、guidance、decode、restore
言葉が光になるまでの
見えない階段、全部正しい
ただのプロンプトじゃない
ただの画像じゃない
その間に眠る数学が
今日も静かに、世界を描く
