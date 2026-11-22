# LG Aimers 8기

ZIP중력팀의 **EXAONE-4.0-1.2B 모델 경량화 온라인 해커톤** 제출 코드입니다.

- [대회 사이트 · DACON](https://dacon.io/competitions/official/236673/overview/description)
- **방법:** Linear 레이어에 W8A8 INT8 양자화 적용, `lm_head`는 양자화 대상에서 제외
- **도구:** PyTorch, Transformers, llmcompressor, Hugging Face Datasets
- **결과:** 모델 크기 약 50% 감소, 최종 점수 0.6343 (제출 노트북 기록 기준)

## 실행

GPU 환경에서 `ZIP중력코드(온라인).ipynb`의 셀을 순서대로 실행합니다. 모델 저장 후 `submit_ZIP중력.zip`이 생성됩니다.

개발 환경과 라이브러리 버전은 노트북 첫 셀에 정리되어 있습니다. 모델 가중치와 제출 ZIP은 저장소에 포함하지 않습니다.
