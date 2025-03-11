# 🚀 자동차 불량 이미지 데이터를 이용한자동차 외관 하자 자동 검사 프로그램

---

## 📌 프로젝트 개요 및 주제 선정 배경
- 프로젝트 목표
  - ai허브에서 제공하는 **자동차 불량 이미지를** 기반으로 **AI 모델을 학습시켜** 입력된 이미지의 **차량의 하자 여부를 판별**하는 모델 제작
  - 모델을 구축 후 **웹캠으로 실제 자동차 촬영하여 하자를  판별**하는 시스템을 구축
- 주제 선정 이유
  - 센서(웹캠)를 통하여 이미지를 입력받아 인공지능에 접목시켜 분류하는 기술은 스마트 팩토리 구현에 중요한 요소임
  - 자동차는 대한민국을 대표하는 산업 중 하나로 그 중 **검사공정에서 유용하게 사용 가능**
- 참고 자료 및 링크
  - AI허브: https://aihub.or.kr/aihubdata/data/dwld.do?currMenu=115&topMenu=100
    
---

## 🛠️ 주요 기술 스택
- **사용 언어**: Python(VScode 기반 학습 프로그램 작성)
- **프레임워크**: YOLO ver. 8 and 11(이미지 데이터 학습 알고리즘)
- **라이브러리**: numpy(데이터 전처리), openCV(테스트 데이터 수집), Matplotlib(시각화), scikit-learn(성능 측정), PIL(이미지 불러오기)

---

## 👥 팀 구성 및 역할 분담
| 이름 | 역할 | 주요 업무 | GitHub 프로필 |
|------|------|----------|----------|------------|
| **유승태** | 팀장 | PM, 모델 학습 및 구축, 성능평가 지표 구현, 발표 | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/dawoonykim) |
| **김다운** | 데이터 관리, 모델 구축 | 데이터 수집(다운로드, feature 선정), 모델 학습 및 구축 | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/Yoo-Seung-Tae) |
| **한용찬** | 모델 및 서비스 시스템 구축 | 데이터 입/출력 구현, 모델 학습 및 구축, openAI 구현 | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/KYEONGJUN-LEE) |
| **신예지** | 선행연구, 데이터 전처리, 모델 구축 | 선행연구, 데이터 전처리(json → csv) , 모델 학습 및 구축 | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/hyerin00) |
---

## 📌 주요 기능



  <img src="https://github.com/user-attachments/assets/942058bd-109b-41e5-82b0-926f6d335d6a" width="800">

---

## 📚 개발 일정
| 마일스톤 | 목표 날짜 | 설명 |
|------------|-------------|---------------------------------|
| 사전 기획 | 2025-01-15 | 프로젝트 기획 및 주제 선정 |
| 데이터 수집 및 전처리 | 2025-01-15 ~ 2025-01-21 | AI허브 내 데이터 다운로드 및 전처리 |
| YOLO 분류 모델 학습 | 2025-01-20 ~ 2025-01-23 | YOLO 8 or 11 기반 학습 시행 |
| OpenCV 기반 프로그램 구현 | 2025-01-22 ~ 2025-01-24 | 웹캠을 통해 이미지를 입력받아 분류하는 프로그램 구축 |
| PPT 작성 | 2025-01-23 ~ 2025-01-24 | 자료 종합 및 발표준비 |
| 발표 | 2025-01-25 | 프로젝트 최종 발표 |

---

## 🔧 개발 플로우 차트
  <img src="https://github.com/user-attachments/assets/405d9218-dc39-42dd-9fe8-08849c901ca7" width="800">
  
---

## 🏆 수상 내역
- 코딩온 KDT 과정 팀 프로젝트 우수상
  
  <img src="https://github.com/user-attachments/assets/914d29e8-b9bf-4f26-8edc-f531107bc5c5" width="600">
