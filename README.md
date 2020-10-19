# Utilizing Public-Key Cryptography

## Open Cryptochat -

Cryptography is important. Without encryption, the internet as we know it would not be possible - data sent online would be as vulnerable to interception as a message shouted across a crowded room. Cryptography is also a major topic in current events, increasingly playing a central role in [law enforcement investigations](https://en.wikipedia.org/wiki/FBI%E2%80%93Apple_encryption_dispute) and [government legislation](https://www.politico.com/tipsheets/morning-cybersecurity/2017/11/10/texas-shooting-could-revive-encryption-legislation-223290).

Encryption is an invaluable tool for journalists, activists, nation-states, businesses, and everyday people who need to protect their data from the ever-present threat of hackers, spies, and advertising agencies.

![Screenshot 5](https://cdn.patricktriest.com/blog/images/posts/e2e-chat/screenshot_5.png)

will walk through the basic concepts and implementation of an end-to-end 2048-bit [RSA encrypted](<https://en.wikipedia.org/wiki/RSA_(cryptosystem)>) messenger. We'll be utilizing [Vue.js](https://vuejs.org/) for coordinating the frontend functionality along with a [Node.js](https://nodejs.org/en/) backend using [Socket.io](https://socket.io/) for sending messages between users.

Project Stack:

- Front-end: Vue.js
- For sending messages: Socket.io
- Back-end: Node.js

- Live Preview - http://vue-crypto-chat.herokuapp.com/
- Github Repository - https://github.com/taseentanvir/open-cryptochat

This app is 100% open-source, feel free to utilize the code however you would like.

```
The MIT License (MIT)

Copyright (c) 2018 Taseen Tanvir

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
