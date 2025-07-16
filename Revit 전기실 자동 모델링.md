# Revit 전기실 기반 Cabinet/Tray/Booster Bus 자동 배치 및 Fitting 최적화 시스템

## 기간
2024.09 ~ 2024.11

## 목적
Revit(3D) 모델에서 Room(전기실) 데이터를 활용하여  
Cabinet, Tray, Booster Bus 생성 및 Fitting 적용·최적화,  
자동 배치 시스템 개발

## 팀원
- 1명 (개인 프로젝트)

## 사용 도구 및 기술
- **C#**
- **TortoiseSVN**
- **DevExpress**
- **Autodesk Revit**
- **AutoCAD**

## 주요 기능 및 구현 내용

- **전기실(Room) 기반 Cabinet 생성**
  - 전기실의 구조(위치, 형태, 크기 등)를 분석하여 Cabinet을 자동 생성

- **Tray 생성 및 Fitting 적용**
  - 좌표 정보를 활용해 Tray(트레이) 객체를 자동 배치
  - 경로에 따라 필요한 Fitting(피팅)을 자동 적용

- **Booster Bus 생성 및 Fitting 적용**
  - 좌표 데이터를 바탕으로 Booster Bus(부스터버스) 자동 배치
  - 적합한 Fitting과 Parameter를 자동 계산 및 적용

- **자동화 및 최적화 로직**
  - 대상 Room(전기실) 정보 추출 → Cabinet·Tray·Booster Bus 생성 → Fitting 최적 배치 순으로 자동화
  - 배치 결과의 공간 활용, 구조 간섭, 실무 배선 규정 등을 반영하여 최적화

---

> 본 프로젝트는 전기실 구조에 맞는 전기 자재(장비) 자동 생성·배치와 Fitting 최적화를 통해  
> Revit 기반 전기 설계의 생산성과 정확성을 크게 향상하는 데 중점을 두었습니다.
