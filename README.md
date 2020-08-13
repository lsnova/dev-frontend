# LSN JavaScript / TypeScript interview

### Task - user management module

Please provide a webpage with a user management module.

The module should provide main functionality described below:

* list all of the users in a table
* ability to add a new user and delete / modify existing one
* list filtering by a search phrase (preferably with a debounce on a keypress)
* list filtering by role
* data paging (please generate some initial random user data)

Any kind of automatic tests (unit, end to end) will be appreciated.

You can use the following example as a data interface:

```
interface UserInterface {
    username: string;
    firstName: string;
    lastName: string;
    role: 'admin' | 'user';
    enabled: boolean;
}
```

Solution can be written in vanilla JavaScript or using framework Angular (in a modern version). There is no backend solution in this task, so there is no need for storing the data persistently (refresh of the page can "erase" the state of the module into initial one). Additional points will be given for using a redux store (NGXS is preferred). 

Please do not focus on HTML side (there is no need for advanced CSS) of the module - we care only about the quality of the JavaScript / TypeScript code.
