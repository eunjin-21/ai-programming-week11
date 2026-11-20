# ai-programming-week11

# (프로그램 이름을 적으세요)
성적관리 프로그램입니다.


## ① 무엇을 하나요 (What)

성적 CSV를 읽어 유효한 점수만 골라 냅니다.



## ② 왜 만들었나요 (Why)          ★ AI는 이 칸을 못 씁니다
실제 파일에는 빈 칸 · 범위 밖 점수 · 중복 이름이 섞여 있어 그냥 읽으면 프로그램이 죽기 때문입니다.


## ③ 어떻게 쓰나요 (How)
python -m load_scores scores.csv


## ④ 어떻게 테스트하나요
python –m pytest


## ⑤ 파일 구성
| 파일 | 하는 일 |
| --- | --- |
| load-scores.py | 함수가 있는 파일 |
| test_load_socres.py | pytest용 파일 |
| *.csv | 데이터 파일 |

## ⑥ 만든 사람 · AI를 어디에 썼는지
- 만든 사람 : 이은진(2026100390)
- AI를 쓴 곳 : load-scores.py
- 내가 직접 판단한 것 : GitHub Copilot

## 라이선스
MIT License (LICENSE 파일 참고)