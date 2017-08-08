- implement [projectname.py](https://github.com/londonhackspace/irccat-commands/blob/master/projectname.py)
- implement API call to check if name exists
```
https://crates.io/api/v1/crates/foobaz2 should return either 200 or 404
```
- should be able to do:
    - `cargo name -- --bin` to do `cargo new {name} --bin` 
    - `cargo name -- --vcs none` to do `cargo new {name} --vcs none`