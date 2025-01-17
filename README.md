# Genshin Artifacter

これは[Genshin Artifacter BOT](https://github.com/FuroBath/ArtifacterImageGen)の再現版です。
<br>Hyugoさんによると「画像のデザインのテンプレートコードを今後公開する」とのことなので、
<br>それに合わせて更新していく予定です。
<br>
<br>__**py-cordなので注意してください**__
<br>discord.py版は[こちら](https://github.com/celely-discord-bot/Genshin-Artifacter-BOT-dpy)

# 動作環境

作者の動作確認環境
<br>Python : 3.10.8
<br>Py-cord : 2.4.0
<br>
<br>

## 前提条件

Discord BOTのTOKENを取得


モジュールインストール<br>
```
pip install -r requirements.txt
```

`main.py`と同じディレクトリに`.env`ファイルの
```
TOKEN = "Your Discord BOT token"
```
の""内にDiscord BOTのtokenを貼り付け
<br>


# commands

```
/build
```
artifacterとほぼ同じ仕様です。
<br>使い方は[こちら](https://youtu.be/q3P5zTf38DA)が参考になると思われます。
<br>
<br>キャラの詳細情報が公開されてない場合などはビルドカードが作成できません。

# 使用させていただいてるもの
[Genshin Artifacter BOTの画像生成](https://github.com/FuroBath/ArtifacterImageGen)
<br>[Enka Network](https://enka.network/)
<br>[Kuroneko ServerのGenshin API](https://support.kuroneko6423.com/)（いずれこれが無くても使えるようにする）


# LICENSE
[MIT License](https://github.com/ActCelely/ArtifacterImageGen/blob/master/LICENSE)です。