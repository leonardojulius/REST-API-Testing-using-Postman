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

```
{
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
}
```

5. save it on my documents
6. run command prompt or terminal 
7. type `cd documents` or some place you save the jsonfile
8. type `json-server --watch db.json`
output should like this

![image](https://user-images.githubusercontent.com/16941074/117301327-1fbd3180-aead-11eb-8630-70660bf64209.png)

9.then go to browser type the url output should like this

![image](https://user-images.githubusercontent.com/16941074/117336042-5d7e8200-aece-11eb-912e-9253e64922bb.png)


10. go to readme `https://github.com/typicode/json-server`

![image](https://user-images.githubusercontent.com/16941074/117334985-3ffce880-aecd-11eb-854b-022800731472.png)


POST REQUEST

11. Insert below using POST method in postman

    ```
     {
        "id": 2,
        "title": "POST Title",
        "author": "POST Author"
     }
    
    ````

![image](https://user-images.githubusercontent.com/16941074/117338412-1a71de00-aed1-11eb-8ecb-cb7dbd405283.png)

12.Basic PUT Request

 ```
 {
    "id": 1,
    "title": "My Title",  // Previously "Updated Title"
    "author": "Updated Author"

 }
 
 ```

![image](https://user-images.githubusercontent.com/16941074/117344563-16958a00-aed8-11eb-8b00-e4ff5e54d805.png)

13. Basic Delete Request


![image](https://user-images.githubusercontent.com/16941074/117346430-4e053600-aeda-11eb-8d3c-742ab1c3147b.png)

  ```
 {
    "id": 1,
    "title": "My Title",
    "author": "Updated Author"
 }

```

14. Basic Verification
after patch

15.nodejs

16.api
