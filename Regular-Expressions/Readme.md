# Regular Expressions

- Any Email 
  ```JS 
  /^(([^<>()[\]\\.,;:\s@"]+(\.[^<>()[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/ 
  ```

### URL validation regular expression

- with or without http 
  ```JS
  /(http(s)?://)?([\w-]+\.)+[\w-]+[.com]+(/[/?%&=]*)?/
  ```
- Any URL 
  ```JS 
  /((www\.|(http|https|ftp|news|file)+\:\/\/)[_.a-z0-9-]+\.[a-z0-9\/_:@=.+?,##%&~-]*[^.|\'|\# |!|\(|?|,| |>|<|;|\)])/ 
  ```
