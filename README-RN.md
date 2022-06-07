# LSN React-Native coding task

### Task - user management app

Please provide a ReactNative application code with a user management module. You can send a zip package or a link to a public GitHub repository. 
In either case please **provide a readme file with instructions on how to run the app**.

####Main goals:
The module should provide main functionality described below:

* list all the users
* user details screen
* ability to add a new user and delete / modify existing one
* list filtering by a search phrase (preferably with a debounce on a keypress)
* provide user data - please generate some initial random user data.
You can use the following example as data interface:

```
interface User {
    username: string;
    firstName: string;
    lastName: string;
    role: 'admin' | 'user';
    enabled: boolean;
}
```

####Bonus goals:
* list filtering by role
* implement redux store
* instead of generating random data connect the app to some public API (e.g. https://randomuser.me/ )
* generate/fetch more data on reaching end of the list
* provide tests

####HINTS:
There is no need to persist data (refresh of the app can "erase" the state of the module into initial one). 

**Please prioritize code quality and readability over visual design.**
