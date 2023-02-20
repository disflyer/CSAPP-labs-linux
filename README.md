# csapp-labs

Book: Computer Systems: A Programmer's Perspective, 3/E (CS:APP3e)

Labs for self-study, downloaded from: [http://csapp.cs.cmu.edu/3e/labs.html](http://csapp.cs.cmu.edu/3e/labs.html)

## Usage:

Use for study Computer Systems: A Programmer's Perspective's LAB.

## Quicky start

First of all, you should install docker on your computer. Just search `docker download` by google for install.
You should execute all those command under the root of the this repository.

```shell
  docker compose up -d
```

when container is created, run:

```shell
  docker exec -it csapp_ubuntu bash
```

then, go to the target folder:

```shell
  cd /csapp_lab
```

Now, you can modify code on your mac system by your IDE. And run the command in lab's README by the container. It should works.
