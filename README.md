# ANTI ADHD - 4분할 체크리스트

아이젠하워 매트릭스를 기반으로 한 할 일 관리 도구입니다. ADHD가 있는 사용자를 위해 설계되었으며, 중요도와 긴급도에 따라 할 일을 효과적으로 관리할 수 있습니다.

## 📥 다운로드

- [Windows 실행 파일 다운로드](https://github.com/octxxiii/4ADHD/releases/latest/download/ANTI_ADHD.exe)

## ✨ 주요 기능

### 기본 기능
- 4분할 체크리스트 (중요도/긴급도 기준)
- 자동 저장 (5분 간격)
- 항목 추가/수정/삭제
- 체크박스로 완료 표시
- 항목별 상세 메모 기능

### 편의 기능
- 창 고정 기능
- 불투명도 조절
- 프린트 기능
- 데이터 백업/복원

## 🖥️ 화면 구성

### 메인 화면
- **중요 & 긴급**: 즉시 처리해야 하는 중요한 일
- **중요**: 계획을 세워 처리할 중요한 일
- **긴급**: 빠르게 처리해야 하지만 중요도가 낮은 일
- **중요 X 긴급 X**: 나중에 처리해도 되는 일

### 하단 메뉴
- 📌 고정: 창을 항상 위에 표시
- 🔍 불투명도: 창의 투명도 조절
- ⚙️ 설정: 프로그램 설정 및 정보

## 💡 사용 방법

1. **항목 추가**
   - 각 분면의 입력창에 텍스트 입력
   - Enter 키 또는 추가 버튼 클릭

2. **항목 관리**
   - 체크박스 클릭: 완료 표시
   - 더블 클릭: 상세 메모 작성
   - 우클릭: 수정/삭제 메뉴

3. **데이터 관리**
   - 자동 저장: 5분마다 자동 저장
   - 수동 저장: 설정 메뉴에서 저장/불러오기
   - 프린트: 현재 체크리스트 인쇄

## ⚙️ 개발 정보

- 버전: 1.0
- 개발자: MinJun Kim
- 이메일: kdyw123@gmail.com

## 🛠️ 직접 빌드하기

### 요구사항
- Python 3.8 이상
- pip 패키지:
  ```
  pillow>=10.0.0
  pyinstaller>=6.0.0
  ```

### 빌드 방법
1. 저장소 클론
   ```bash
   git clone https://github.com/kdyw12/ANTI-ADHD.git
   cd ANTI-ADHD
   ```

2. 가상환경 설정
   ```bash
   python -m venv .venv
   .venv/Scripts/activate  # Windows
   source .venv/bin/activate  # Mac/Linux
   ```

3. 패키지 설치
   ```bash
   pip install -r requirements.txt
   ```

4. 실행 파일 생성
   ```bash
   pyinstaller --noconfirm --onefile --windowed --icon=app_icon.ico --name=ANTI_ADHD anti_adhd.py
   ```

## 📝 라이선스

MIT License 
