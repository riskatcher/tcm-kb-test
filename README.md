# TCM-KB 번역 테스트 (100문장)

## 파일 구조
- `batch-001.json` ~ `batch-010.json`: 각 10문장씩 총 100문장
- `PROMPT.md`: 번역 프롬프트 (규칙 + 출력 형식)
- `result-001.json` ~ `result-010.json`: 번역 결과 (생성 예정)

## Claude Code에서 실행 방법

아래를 그대로 붙여넣기:

```
이 폴더의 batch-001.json부터 batch-010.json까지 순서대로 번역 작업을 해줘.

각 배치마다:
1. batch-NNN.json 읽기
2. PROMPT.md의 규칙에 따라 각 문장의 original을 한국어로 번역
3. 결과를 result-NNN.json에 저장 (형식: {"translations": [{"id": 숫자, "ko": "번역문"}, ...]})
4. 다음 배치로 진행

10개 배치 모두 완료할 때까지 계속해.
```

## 번역 완료 후
결과 파일들을 Noah에게 전달하면 DB에 import합니다.
