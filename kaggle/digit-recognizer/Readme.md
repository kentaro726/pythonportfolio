画像データの基本的な認識問題である, digit-recognizernに取り組んだ.

kerasを用いたCNNモデルでは98.271%の正確性, pytrchを用いたCNNモデルでは98.542%の正確性が得られた.

kerasではImageDatagenaratorでデータを水増ししたり, 訓練時に検証用のデータを与えたりしたので, kerasでの正確性の方がたかくなると予想したがpytorchで構築したモデルのほうが適していたという結果が得られた。
