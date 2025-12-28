Revit 지하 횡주 배관(오배수, 위생/공조, 소화) 최적화 경로 모델링 시스템
기간
2025년 7월 ~ 12월

목적
기존 Revit(3D) 모델에서 AutoCAD 파일과 최적화된 dll파일의 좌표 정보, 사용자의 UI 정보를 활용하여
최적화 경로 확인 및 경로 생성 이후 조건에 맞는 오배수, 위생/공조, 소화 배관 생성

팀원
1명 (개발자)
사용 도구 및 기술
C#
TortoiseSVN
DevExpress
Revit API
AutoCAD

주요 기능 및 구현 내용
Excel 정보, 사용자 UI 정보 기반 자동 모델링

dll 정보와 Excel 정보를 통해로부터 Level, 패밀리 타입, Workset, systemType등  정보를 읽어들여 해당 도면의 Default 값을 설정

각 패밀리와 Level, 공종, 건축 법에 따라 Conduit 객체들을 연결
Revit API와 Connector를 활용해 자동 연결 생성 및 경로 최적화[1][3][5]
Conduit 연결 시 패밀리 특성에 맞춰 자동으로 Fitting(피팅: 엘보, 티 등) 적용
Tray(케이블 트레이) 자동 연결

트레이 경로, 패밀리 위치, 건축 정보에 따라 케이블 트레이 구간 및 Fitting 자동 배치[2][4][6]
트레이와 Conduit의 연결을 위한 자동 Elevation(고도) 조정 및 위치 정렬
특정 구역 진로 회피 로직

예시: 화장실 벽 등 회피 구역 정보를 바탕으로
Conduit 및 Tray 경로가 장애물(벽 등)을 자동으로 우회하도록 경로 산출[4][6]
자동화 프로세스

AutoCAD/Excel에서 필수 정보 분석 및 추출
Revit 패밀리 객체 자동 생성 및 지정 위치/Level로 배치
관련 법규 및 특성을 반영한 Conduit/Tray 자동 연결 및 피팅 적용
장애물 회피 및 연결 최적화 처리
본 프로젝트는 Revit API의 고급 Connector 관리와 피팅 자동 배치, 장애물 자동 회피 로직 등
건축 법규와 실무 프로세스를 최적화하여, BIM 환경의 도면 작업 자동화 수준을 크게 높였습니다.
