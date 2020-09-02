# wechat_watcher
watches wechat

Steps

1. $ source venv/bin/activate
2. $ python3
3. >>> import itchat
5. >>> itchat.login()
4. >>> from get_waiting_list import *
6. >>> chatrooms = itchat.get_chatrooms()
7. >>> get_lrsg_rooms(chatrooms)
8. >>> get_waiting_list()
9. $ cat waiting_list.json
