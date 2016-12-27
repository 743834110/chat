# chat
A Chat Scaffold based on antd and dva:

Screenshots:
-----

![](https://cloud.githubusercontent.com/assets/566097/21448864/2dc1a59c-c922-11e6-9b80-726593d8163d.png)

![](https://cloud.githubusercontent.com/assets/566097/21494490/f28c2eb0-cc4c-11e6-83b8-723ae1423328.png)

Firebase Structure
-----

```
root: {
  conversations: { // conversations
    '-2h6WJbFPBxUs15iB15DnSAIRTyP2-1482823102860': {
      participants: {
        '2h6WJbFPBxUs15iB15DnSAIRTyP2': user,
        '1482823102860': user
      },
      chats: {
        '-KZzCufnRDtS4h0q9fL': {
          content: '',
          time: '',
          user: {}
        }
      }
    },
    ...
  },
  user: { // online users
    '2h6WJbFPBxUs15iB15DnSAIRTyP2': user,
    ...
  }
}
```


Install
------

```
git clone https://github.com/RaoHai/chat.git
cd chat
npm install
npm start // enjoy :D

```
