# Exercises Security 

## Questions

**Q: What is the advantage (if any) for a REST-based API of using JWT’s compared to session Cookies** <br>
**A:** We can move the authentication to the client-side, and by passing the Token, given at the first login, we don't have to authenticate the user at every HTTP call. 

**Q: What is the disadvantage (if any) with the implemented JWT-solution** <br>
**A:** An issue with the JWT-solution is that when a token is given, it will keep being valid for the entire TTL. This means that if we want to make sure a token is valid, we need to track when a user is logging out and then invalidating the token, on the server side.

**Q: What will a client (Single Page WEB, Mobile App, etc.) have to do in order to use this API** <br>
**A:** The client will need to provide the login with a username and a password, if the user is created/active, the provided token will have to be saved on the client side (fx. local storage).

## Links to all assignments:
![30-03-2020](https://github.com/Paepke-cph/Flow3Week2Day1) <br>
![Exercises Security](https://github.com/Paepke-cph/Flow3Week2Day2) <br>
![Momondo-like Servers](https://github.com/Paepke-cph/Flow3Week2Day3) <br>
