from maxrubika import Messenger
from datetime import datetime
import time

SESSION = "mySession"
GROUP = "GROUP_GUID"

with Messenger(SESSION) as app:
    while True:
        now = datetime.now()

        title = now.strftime("🕒 %H:%M | %Y/%m/%d")

        try:
            result = app.set_voice_chat_setting(
                GROUP,
                title=title
            )
            print("Updated:", title)

        except Exception as e:
            print("Error:", e)

        time.sleep(60)
