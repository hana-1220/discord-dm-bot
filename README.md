# discord-dm-bot

Discord DMでメッセージを自動送信するスクリプト

## 使い方

```bash
# 環境変数を設定
export DISCORD_DM_BOT_TOKEN=your-bot-token
export DISCORD_DM_USER_ID=your-user-id

# メッセージを送信
python3 discord_dm_send.py "メッセージ1" "メッセージ2" ...
```

## 環境変数

```
DISCORD_DM_BOT_TOKEN=  # Discord Bot トークン（DM Bot）
DISCORD_DM_USER_ID=    # 送信先ユーザーID
```
