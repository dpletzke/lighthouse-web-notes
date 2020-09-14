# Using process.argv

Link to [article](https://stackabuse.com/command-line-arguments-in-node-js/)

You can pass args directly into a program by using `process.argv` in the program and passing in variables from the command line like below: 

```bash
$ node processargv.js tom jack 43
```

> `process.argv` is an array


```bash
vagrant [d1-focal]> node sum.js 10 25
[ '/home/vagrant/.nvm/versions/node/v10.20.1/bin/node',
  '/vagrant/w1/d1-focal/sum.js',
  '10',
  '25' ]



```
