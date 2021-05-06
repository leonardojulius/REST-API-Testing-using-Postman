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

3. Install JSON Server `\\`

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
6. run command prompt or terminal 
7. type `cd documents` or some place you save the jsonfile
8. type `json-server --watch db.json`
output should like this

![image](https://user-images.githubusercontent.com/16941074/117301327-1fbd3180-aead-11eb-8630-70660bf64209.png)

9.then go to browser type the url output should like this

![image](https://user-images.githubusercontent.com/16941074/117301558-54c98400-aead-11eb-9695-a8e1a37080ed.png)

10. go to readme `https://github.com/typicode/json-server`

![image](https://user-images.githubusercontent.com/16941074/117334985-3ffce880-aecd-11eb-854b-022800731472.png)


11.




