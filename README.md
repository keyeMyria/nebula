
![alt text](https://raw.githubusercontent.com/lk-geimfari/farbe/master/other/logo.png)


------

### Usage
Just use the following format {color, "Text"}
```erlang
farbe:cprint({red, "Colored text"}).
```

### Example
```erlang
-import(farbe, [cprint/1]).

update_something() ->
  %% ...
  %% ...
  %% ...
  cprint({green, "Something has been updated successfully!"}).
```


### Screenshot
![alt text](https://raw.githubusercontent.com/lk-geimfari/farbe/master/other/main.png)

