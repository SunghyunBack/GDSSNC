# Revit 기반 최적화 배관 자재 단가 자동 계산 및 횡주 배관 생성 시스템

## 기간
2023.12 ~ 2024.03

## 목적
최소한의 Excel 및 CAD 데이터만으로 Revit(3D) 모델에서  
배관 자재 단가를 자동으로 산출하고, 최적의 횡주 배관을 생성하는 시스템 개발

## 팀원
- 2명

## 사용 도구 및 기술
- **C#**
- **TortoiseSVN**
- **DevExpress**
- **Autodesk Revit**
- **AutoCAD**

## 주요 기능 및 구현 내용
- 저층/고층 구분, 세대 수, 압력 정보 등을 기반으로 각 시스템의 필요 압력 및 차압을 자동으로 계산
- 자동 산출된 결과값을 활용하여 Revit 내 배관 Family를 자동으로 생성

### 시스템별 기능
1. **급수 시스템**
    - 유속, 필요압력, 마찰손실, 배관압력 계산
2. **급탕 시스템**
    - 유속, 필요압력, 마찰손실, 배관압력, 급탕계수 계산
3. **환탕 시스템**
    - 유속, 필요압력, 마찰손실, 배관압력, 환탕계수 계산
4. **난방 시스템**
    - "4인 가구", "동", "전체" 기준으로  
      필요압력, 마찰손실, 배관압력, 난방계수, 차압 등 주요 변수 자동 계산

---

> 본 프로젝트는 Revit API 및 다양한 자동화 도구를 활용하여  
> 복잡한 배관 계산 및 Family 자동 생성을 효율적으로 처리하는 데 중점을 두었습니다.
