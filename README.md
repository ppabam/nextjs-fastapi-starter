# 💾 🐈 나이계산기
- Korean President Yoon Suk Yeol unified the age calculation method to full age. Amid the resulting confusion, an age calculator was created.

### Use
- https://ac.sunsin.shop
### Dev
```bash
$ pyenv global
3.10.12
# $ python -m venv venv
$ source venv/bin/activate
$ uvicorn api.index:app --reload
```

### Contributing
- scenario #1
```bash
# setting ssh
$ git clone <URL>
$ git branch <VER>/<NAME>
$ git checkout <VER>/<NAME>
$ git push
# make PR
# doing ...
# dogng ...
$ git add <FILE_NAME>
$ git commit -m "<MESSAGE>"
$ git push

# merge main -> deploy
# releases & tag
```
- scenario #2
```bash
$ git branch -r
$ git checkout -t origin/<VER>/<NAME>
# doing ...
# dogng ...
$ git add <FILE_NAME>
$ git commit -m "<MESSAGE>"
$ git push

# merge main -> deploy
# releases & tag
```
### Ref
- https://docs.python.org/ko/3.10/library/datetime.html
