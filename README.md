docker-gopy
===========

Docker image which provide a goPy installation

Hello World
------------

To run the image execute the following...

```
$ docker run --rm -ti qnib/gopy /bin/bash
root@10515b87b862:/# su -
root@10515b87b862:~# gopy simple.go 
root@10515b87b862:~# python simple.py 
simple.example: [hello map[123:true]]
root@10515b87b862:~# gopy parallel.go 
root@10515b87b862:~# python parallel.py 
x = [1, 2, 3, 4]
```

