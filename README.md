# reproduce-babel-13780

Without docker
```sh
$ npm install
$ npm test
```

With docker
```sh
[host:user] $ npm run container
[container:root] # ./INSTALL.sh
[container:node] $ npm install
[container:node] $ npm test
...

(Ctrl-D twice to exit container)
```
