# 🍪 간식뺏기: 감옥탈출

Streamlit으로 만든 초고난도 잠입 게임.

## 게임 흐름
- 교실에서 시작
- 복도를 지나 학생부실 진입
- 학생부실에서 정보실 열쇠 획득
- 다시 복도를 지나 정보실 진입
- 정보쌤의 시야를 피하면서 간식 획득
- 들키면 경계 수치가 올라가며, 100%가 되면 목숨을 잃음

## 실행
```bash
pip install -r requirements.txt
streamlit run app.py
```

## 조작
- `WASD` / 방향키: 이동
- `Shift`: 빠르게 이동 (소음 증가)
- `Space`: 숨기

## GitHub + Streamlit Cloud
저장소에 `app.py`, `requirements.txt`, `README.md`를 올린 뒤 Streamlit Community Cloud에서 `app.py`를 앱 파일로 지정한다.
