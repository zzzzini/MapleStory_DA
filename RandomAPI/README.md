# 📌 Info.
메이플스토리 OpenAPI를 사용해 원하는 레벨 구간의 유저를 랜덤으로 선별해 심볼 데이터를 조회하는 코드입니다.

# 🧐 How?
사전에 수집한 캐릭터들의 레벨과 닉네임 데이터를 이용하여

각 그룹별로 1000개의 랜덤 표본을 추출한 뒤,

OpenAPI를 통해 OCID 👉🏻 심볼 데이터 순으로 조회를 진행했습니다.

# 🛠️ Tools
## 사용된 주요 라이브러리

```python
import requests
```

```python
from urllib.parse import urlparse
```

```python
import pandas as pd
```
