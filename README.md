# Merge Table Test

PyMuPDF를 사용하여 PDF 내 테이블을 탐지하고, GPT를 활용해 병합 해제 및 표 구조화 테스트

## 주요 파일
- `main.py` : PDF 테이블 추출 및 GPT 호출 샘플 코드
- `merge_table_test.ipynb` : Jupyter Notebook 기반 실험 코드
- `삼성생명약관.pdf` : 테스트용 PDF 문서
- `pyproject.toml` : 프로젝트 설정

## 실행 환경
- Python 3.10+
- [PyMuPDF](https://pymupdf.readthedocs.io/)
- Azure OpenAI SDK

## 실행 방법
1. 가상환경 생성 및 패키지 설치
   ```bash
   uv venv
   uv pip install -r requirements.txt