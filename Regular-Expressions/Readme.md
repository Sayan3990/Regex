# Regular Expressions

### Email Validation
- Any Email
  ```JS
  /^(([^<>()[\]\\.,;:\s@"]+(\.[^<>()[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/ 
  ```

### PAN Validation
- Any PAN Card
  ```JS
  /[A-Z]\{5\}[0-9]\{4\}[A-Z]/ig
  ```

### URL Validation
- Any URL
  ```JS
  /((www\.|(http|https|ftp|news|file)+\:\/\/)[_.a-z0-9-]+\.[a-z0-9\/_:@=.+?,##%&~-]*[^.|\'|\# |!|\(|?|,| |>|<|;|\)])/ 
  ```
  
### Detect HTML Objects
- links
  ```JS
  /<a.*?href="(.*?)".*?>(.*?)<\/a>/ig
  ```
- Tags
  ```JS
  /<\s*([a-z][a-z0-9]*)[^>]*>/ig 
  ```
- Attributes
  ```JS
  /<(\w+)(\s?.*?)>/g
  ```
