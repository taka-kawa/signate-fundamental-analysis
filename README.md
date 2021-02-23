# signate-fundamental-analysis

## Environment Setup

```
$ docker pull continuumio/anaconda3:2019.03
$ docker run --name signate-fundamental-analysis -d -it continuumio/anaconda3:2019.03
```

```
$ docker exec -it signate-fundamental-analysis /bin/bash
$ mkdir /root/user | cd /root/user
$ git clone https://github.com/taka-kawa/signate-fundamental-analysis.git
$ apt-get update
$ apt-get install -y --no-install-recommends g++ gcc
$ pip install requirements.txt
```

## log in container

```
$ docker exec -it signate-fundamental-analysis /bin/bash
```

## jupyter lab
Execute following command after login

```
$ jupyter lab --ip 0.0.0.0 --allow-root --no-browser --no-mathjax --NotebookApp.disable_check_xsrf=True  --NotebookApp.token='' --NotebookApp.password=''
```
