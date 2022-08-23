## install guide

- `$ pip install -r requirements.txt`

## error 발생 시 guide

### 1. pip install django-environ

```
import environ
env = environ.Env()
environ.Env.read_env()
```

## 환경변수 적용 하는 방법

- .env 생성 후 -> development.env에 있는 변수들을 .env에 넣고 테스트할 값들을 넣어주면 된다.
