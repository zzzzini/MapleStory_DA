# 📌 Info.
메이플스토리의 어센틱 심볼 관련 데이터를 수집하는 코드입니다.

# 🧐 How?
공식적으로 제공되는 데이터가 없다고 판단하여,

나무위키에 정리되어있는 데이터를 Web Crawling 기법으로 수집했습니다.

추후 공식 데이터가 확인되면, 수정 예정입니다.

👉🏻 어센틱포스 시스템의 경우, [[공식 가이드]](https://maplestory.nexon.com/Guide/N23GameInformation/377408#a)에서 공식 데이터 확인 후 이상 없음을 체크했습니다.

# 📝 Insight
1. 사냥터 어센틱 포스 요구량과 캐릭터 어센틱 포스 격차별 입히는 피해량

2. 어센틱 심볼 종류별 레벨당 성장 요구치와 필요 메소량

# 🛠️ Tools
## 사용된 주요 라이브러리

```python
import pandas as pd
```

```python
from bs4 import BeautifulSoup
```
