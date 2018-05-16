# hssh
Bash function for Laravel Homestead SSH with entering the project directory on the same time 

Use it like this to connect to Homestead Vagrant machine and enter the `myapplication` directory:

```
$ hssh myapplication
```

You will end up in `vagrant@homestead:~/myapplication$ `

Note: Your Homestead VM should be up and running (`homestead up`)
