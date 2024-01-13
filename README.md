# 🍁 메이플스토리 육성 컨텐츠 방향 제안 (레벨, 심볼 데이터를 중심으로)

## 💡 Motivation
메이플스토리에는 레벨 성장에 필요한 경험치량이 급격히 증가하거나,

경험치 획득을 위한 컨텐츠인 사냥에 필요한 스펙이 급격히 높아지는 '정체구간'이 존재합니다.

많은 유저들이 위와 같은 정체구간에서 게임에 급격히 흥미를 잃으며, 심하면 게임에 손을 떼기도 합니다.

따라서 현재 메이플스토리에서 완화가 필요한 정체구간을 파악하고,

해당 구간을 적절히 조정하거나,필요한 요소를 제공하는 새로운 컨텐츠를 출시하면 좋을 것 같다 생각했습니다.

## 🛠️ How?
전체월드(리부트, 버닝 제외)의 캐릭터 닉네임 수집 👉🏻 메이플스토리 공식 홈페이지 [[월드 랭킹]](https://maplestory.nexon.com/N23Ranking/World/Total) 항목 Crawling

경험치 정보 수집 👉🏻 나무위키 [[메이플스토리/시스템/경험치]](https://namu.wiki/w/%EB%A9%94%EC%9D%B4%ED%94%8C%EC%8A%A4%ED%86%A0%EB%A6%AC/%EC%8B%9C%EC%8A%A4%ED%85%9C/%EA%B2%BD%ED%97%98%EC%B9%98) 문서 Crawling

어센틱포스 정보 수집 👉🏻 나무위키 [[어센틱포스]](https://namu.wiki/w/%EC%96%B4%EC%84%BC%ED%8B%B1%ED%8F%AC%EC%8A%A4) 문서 Crawling

캐릭터의 레벨 및 기타 정보 수집 👉🏻 NEXON Open API [[메이플스토리]](https://openapi.nexon.com/game/maplestory/?id=22) 캐릭터 식별자, 장착 심볼 정보 조회

일일퀘스트 경험치 정보 수집 👉🏻 메이플 인벤 [[일일퀘스트 클리어 경험치 표]](https://www.inven.co.kr/board/maple/2304/34182) 글 참고

몬스터파크 경험치 정보 수집 👉🏻 메이플 인벤 [[몬파 클리어 경험치 표]](https://www.inven.co.kr/board/maple/2304/34218) 글 참고

몬스터 사냥 경험치 정보 수집 나무위키 👉🏻 [[메이플스토리 / 일반 몬스터]](https://namu.wiki/w/%EB%A9%94%EC%9D%B4%ED%94%8C%EC%8A%A4%ED%86%A0%EB%A6%AC/%EC%9D%BC%EB%B0%98%20%EB%AA%AC%EC%8A%A4%ED%84%B0) 문서 참고

데이터 수집 및 전처리 👉🏻 Python

데이터 분석 및 시각화 👉🏻 Tableau

## 📚 참고 문헌

👉🏻 [한국컴퓨터정보학회 하계학술대회 논문집 제 31권 2호] 국내 PC MMORPG 게임의 이용자 감소 현상에 대한 연구 - 윤준, 이종원

👉🏻 [Mastering Retention Playbook] - Amplitude Co.

👉🏻 메이플 인벤 자유게시판
