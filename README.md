# signate-fundamental-analysis

## Environment Setup

```
$ docker pull continuumio/anaconda3:2019.03
$ docker run --name signate-fundamental-analysis -d -it continuumio/anaconda3:2019.03
```

```
$ docker exec -it signate-fundamental-analysis /bin/bash
// login
$ mkdir /root/user | cd /root/user
$ git clone https://github.com/taka-kawa/signate-fundamental-analysis.git
$ pip install requirements.txt
```
