### start
* check mysql status
    ```
    brew services list
    ```
    shows:
    ```
    Name    Status
    mysql   stopped
    ```
    
* start
    ```
    brew services start mysql
    ```
* stop
    ```
    brew services stop mysql
    ```
**if wanna use other versions may add @ after mysql**

### login
```
mysql -u root -p
```
shows:
```
Enter password
```
default no password