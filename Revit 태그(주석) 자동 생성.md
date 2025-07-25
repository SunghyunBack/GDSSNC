# Revit Family 기반 자동 태그(주석) 생성 시스템

## 기간
2024.04 ~ 2024.08

## 목적
Revit(3D) 모델에서 사용자가 Family를 선택하면, 해당 객체에 맞는 태그(주석)를 자동으로 생성하고 배치하는 시스템 개발

## 담당 인원
- 1명

## 사용 기술 및 도구
- **C#**
- **TortoiseSVN**
- **DevExpress**
- **Autodesk Revit, Revit API**
- **AutoCAD**

## 주요 기능
- 사용자가 Family(예: 벽, 문, 바닥 등)를 선택하면, **태그(주석)의 모양·형태·내용을 자유롭게 설정 및 수정**
- 입력한 설정값을 건축, 구조, 설비, 전기 등 다양한 분야의 Revit 객체에 적용하여 태그 자동 생성  
  - **건축:** 벽, 문, 바닥(FL,SL), 방, 천장  
  - **구조:** 벽, 바닥(SL), 기둥, 파운데이션, 프레임  
  - **설비:** 파이프, 덕트, 피팅, 전기 객체  
  - **전기:** 컨듀잇, 트레이, 전기 장치  
- 특정 예시  
  - **FL**: 해당 층(Level) 기준 건축 바닥 간 거리 자동 산정 및 표시  
  - **SL**: 구조 바닥 간 거리 자동 산정 및 표시
- Family와 연동된 **Element의 방향성**에 따라 태그(주석) 방향·기울기 자동 조정
- 태그 생성 시, **기존 태그와 겹침 감지 시 자동 위치 이동**  
- DevExpress UI 활용으로 **사용성 및 작업 효율성** 향상
- **버전 관리** 및 **코드 협업**을 위해 TortoiseSVN 사용

## 주요 성과
- 카테고리별 자동 태그 생성 로직 구현
- 태그 중첩 방지·위치 재조정 알고리즘 개발
- 실무자 맞춤형 UI와 작업 흐름 구축

---

> 해당 프로젝트는 Revit API 활용 및 복잡한 태그 자동 배치 규칙 구현 등,  
> 실무 BIM 프로세스에서의 효율적인 주석/정보 관리의 자동화에 중점을 두었습니다.
