# hyper-js
setting file for hyper.js

## Create symbolic link
### for linux
```
rm ~/.hyper.js
ln -s ~/hyper-js/.hyper.js ~/.hyper.js
```

### for windows

```
rm ~\AppData\Roaming\Hyper\.hyper.js
New-Item -Type SymbolicLink ~\AppData\Roaming\Hyper\.hyper.js -Value ~\hyper-js\.hyper.js
```
