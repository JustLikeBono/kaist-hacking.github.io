# kaist-hacking.github.io

## Setup environment
1. Install hugo (https://gohugo.io/getting-started/installing/)

2.
```sh
$ virtualenv venv
$ source venv/bin/activate
$ pip install -r ./requirements.txt
```

## Add a new publication
```sh
# update assets/pubs/{conf, pub}.bib
$ ./bin/make_pub.py
```

## Add a new person
Please add your profile in `content/author`.

## Add news
Modify `content/home/news.md`.

## Make it public
**Check again before you run this command**
```
$ ./publish.sh
```

## Reference
- https://github.com/wowchemy/starter-academic

