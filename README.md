# haram_args_history
- parquet 파일의 정보를 cli 기반으로 조회

### 사용법
```
$ my-history -t 10 -d 2024-07-17
  cmd  cnt
pyenv 4256
   cd 3472
  git 3396
mkdir 1932
  pip 1592
  cat 1368
   vi 1356
 sudo 1320
  pdm 1220
   rm 1104
```

###Dev env setting
```
$ git clone <URL>
$ cd <PJT_NAME>
$ pdm install
$ [pdm test|pytest]

# option
$ pdm add -dG test pytest pytest-cov
```

###deploy
```bash
# dev branch
$ pip install git+https://github.com/HaramSs/args_history.git@0.2.0

# main
$ pip install git+https://github.com/HaramSs/args_history.git@main
```


### ref
- https://pdm-project.org/en/latest/usage/dependency/#add-development-only-dependencies
