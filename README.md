# 체스 게임

## 환경 설정

python 3.9.13을 사용합니다.

```shell
pyenv install 3.9.13
pyenv local 3.9.13
python -V
```

가상환경 설정
```shell
python -m venv venv
```

in mac
```shell
source venv/bin/activate
```

in window
```shell
venv\Scripts\activate
```


poetry를 사용해 가상환경을 관리합니다.
```shell
pip install poetry
poetry install
```

pre-commit으로 commit 전 포맷을 확인하고 pytest를 실행합니다.

```shell
pre-commit install
```

pytest 동작 확인

```shell
pytest
```

## 요구사항

### 1차
- [ ] 장기말을 생성합니다.
- [ ] 체스 기물이 이동 할 수 있는 위치를 알 수 있다.
