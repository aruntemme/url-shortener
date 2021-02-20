# Shrink Me

## url-shortener 

It is randomnly generated URL shrinker and shows no. of clicks (shrinked URL)

It also have login, logout functionality for security purposes.
For now the register option is hidden in UI but you can create new user by going into ```http://localhost:8000/register-signin```


![schreenshot1](screenshots/one.png "Login")
<br>
![schreenshot2](screenshots/two.png "Home")

you can simply run this in your local machine by typing below commands

```git clone https://github.com/aruntemme/url-shortener```<br>
```cd url-shortener```<br>
*make sure you have node and mongodb(local) installed*<br>
you can configure db settings in ```server.js``` <br>
```mongoose.connect('mongodb://localhost:27017/YOURDB_NAME').then(console.log("DB connected"))```<br>
change db name as per your wish<br>

Install all dependencies<br>
```npm i```<br>

Run <br>
```npm run devStart```<br>

check your localhost<br>
```http://localhost:8000/```<br>

# Tasks

- [x] table to list previous urls
- [x] no. of clicks
- [x] login, sign up
- [ ] random + given text to generate url


# Keep Support

## Arun 😋
