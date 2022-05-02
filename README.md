# linebot
## Design
![image](https://user-images.githubusercontent.com/39373272/166206974-8eeec7a7-01fe-415f-8e9c-995120da6342.png)
- Linebot ID: @695pxvkb
- To create a more flexible maintained linebot
- seperate message responsing content and message responsing functions

## Tools
- @line/bot-sdk
- crypto
- express



## Files

`index.js`: 
1. set up the environment
2. handle the events  

`messageContents.js`:
1. Being Flexible used inside messageResponse.js
2. To create customized response


`messageResponse.js`:
1. create customized response function for particilar response strings


`messageTypes.js`:
1. To create specific events such as following or messaging, or getfiles...
