# 📌 Info.
메이플스토리 전 서버를 대상으로 260레벨 이상인 캐릭터의 레벨, 닉네임을 수집하는 코드입니다.

# 🧐 How?
메이플스토리 공식 홈페이지의 랭킹 페이지를 이용하였습니다.

서버벌로 랭킹 페이지 url을 통해 Web Crawling 기법으로 수집했습니다.

일반 월드(버닝 월드, 리부트 월드 제외)를 대상으로 진행하였습니다.

# 📝 Insight
1. 캐릭터 레벨

2. 캐릭터 닉네임

# 🛠️ Tools
## 사용된 주요 라이브러리

```python
import requests
```

```python
import pandas as pd
```

```python
from bs4 import BeautifulSoup
```

```python
import time
```
