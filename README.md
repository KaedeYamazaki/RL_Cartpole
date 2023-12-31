# 概要
強化学習の自主勉強のために製作したリポジトリ．以下を参考にした．
- [第15回　CartPole課題で深層強化学習DQNを実装](https://book.mynavi.jp/manatee/detail/id=89831)
- [強化学習（Q学習とQ-Network）によるCart Pole制御](https://colab.research.google.com/github/machine-perception-robotics-group/MPRGDeepLearningLectureNotebook/blob/master/14_rl/00_Q_Learning.ipynb#scrollTo=qzXWZYdawLJD)

# Cartpole_DQN/settings.jsonについて
LINE Notifyを使い学習後に通知が来るようにしている．`settings.json`には，自分が発行したトークンを記述する．
以下を参考にした．
- [PythonでLINEにメッセージを送る](https://qiita.com/moriita/items/5b199ac6b14ceaa4f7c9)

# 環境構築
好きな場所で仮想環境をつくり，以下のコマンドをターミナルで実行．
`pip install -r requirements.txt`