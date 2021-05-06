# REST-API-Testing-using-Postman

1.Download POST-man 

https://www.postman.com/downloads/

2.add postman chrome extension 

https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop


Setting Up Project

1. Install Node JS https://nodejs.org/en/download/ 
    -Choose your operating System
 
2. After downloading and installed, go to terminal or command prompt and type npm
    if you can see this following it means installation is successful
   -npm <command> -h  quick help on <command>
   -npm -l            display full usage info
   -npm help <term>   search for help on <term>
   -npm help npm      involved overview

3. Install JSON Server `npm install -g json-server`

4. Create new Json File `db.json`

`{

  "posts": [
    {
      "id": 1,
      "title": "Updated Title",
      "author": "Updated Author"
    }
  ],
  "comments": [
    {
      "id": 1,
      "body": "some comment",
      "postId": 1
    }
  ],
  "profile": {
    "name": "typicode"
  }
}`

5. save it on my documents
