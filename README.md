# 프로젝트 소개
기존 [EbookToPDF](https://github.com/reji-0/EbookToPDF) 프로젝트를 개선합니다.

## 개선 사항
- 아래 방향키로 페이지를 넘길 수 있는 ebook_to_pdf_DownArrow.exe 파일 추가
- 개발 가이드 작성

## 참고 사항
- ebook_to_pdf_MouseClick.exe
    - 기존 프로그램입니다.
- ebook_to_pdf_DownArrow.exe
    - 개선된 프로그램입니다.
    - **"다음 페이지 버튼 좌표 저장" 단계에서 아무데나 눌러도 됩니다.**

## 개발 가이드
1. python, pip를 설치합니다.
    - **3.13.x 버전에서는 pynput 오류가 발생하므로 2021년 근처의 python 버전을 권장합니다.(제작자는 3.12.9 사용)**
2. 프로젝트 루트 경로에서 "pip install -r requirements.txt" 명령을 실행해서 모듈을 설치합니다.
3. 코드를 원하는데로 수정합니다.
4. "python ebook_to_pdf.py" 명령으로 프로그램을 디버깅합니다.
5. "pyinstaller.exe -F ebook_to_pdf.py" 명령으로 exe 파일을 뽑아냅니다.

    - **window 운영체제 안에서 명령을 실행해야 exe가 뽑아집니다.**