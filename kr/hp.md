# 🏢 HP 경력 상세 (2016.11 \~ 2021.08)

## ✅ 주요 역할

* ARM 기반 복합기 임베디드 시스템 펌웨어 개발
* Yocto 기반 RootFS 시스템 구축 및 자동화
* 옵션 키보드 펌웨어(STM32) 개발
* Docker 및 Jenkins 기반 빌드 환경 자동화

## 📌 주요 프로젝트 요약

### 🔹 Daily 통합 빌드 시스템 구축 (2019.01 \~ 2020.04)

* 복합기의 Boot/Print/Scan/Fax/Engine을 포함한 통합 빌드 시스템 개발
* 넥서스 서버에 업로드 후 VM에 펌웨어 배포 및 테스트 자동화

**성과:**

* 테스트 자동화 실현으로 신뢰성 향상
* 데일리 통합 품질 확보

**프로젝트 상세:**

* [✅ Daily 통합 빌드 시스템 구축](./projects/hp-daily-integrated-build.md)

### 🔹 Yocto 기반 RootFS 자동화 빌드 (2017.03 \~ 2018.06)

* 기존 레거시 빌드 방식을 Yocto 레시피 기반으로 전환
* SDK 배포 자동화 스크립트 개발 및 전사 공유

**성과:**

* 빌드 자동화 및 유지보수성 향상
* 툴체인 변경에 유연하게 대응 가능

**프로젝트 상세:**

* [✅ Yocto 기반 RootFS 자동화 빌드](./projects/hp-yocto-rootfs-automation.md)

### 🔹 옵션 키보드 펌웨어 개발 (2019.01 \~ 2020.07)

* STM32 기반의 복합기 키보드 펌웨어 개발
* 키 입력 처리, 옵션 디바이스 확장 대응

**성과:**

* 사용자 편의성 및 옵션 장치 확장성 향상

**프로젝트 상세:**

* [✅ 옵션 키보드 펌웨어 개발](./projects/hp-keyboard-firmware-stm32.md)

### 🔹 Storage Manager 및 Secure HDD 기능 구현 (2018.10 \~ 2019.01)

* eMMC trim / 디스크 포맷 / 클린 기능 구현
* Secure HDD(SATA/PCIe 기반 SED) 제어 및 보안 기능 강화
* 옵션 HDD 장착 시 포맷 및 설치 자동화

**성과:**

* 민감 정보 보안 강화
* 사용자 신뢰성 향상

**프로젝트 상세:**

* [✅ Storage Manager 및 Secure HDD 기능 구현](./projects/hp-secure-hdd-storage.md)

### 🔹 로그/디버깅 시스템 개선 (2020.10 \~ 2021.03)

* 프린터/스캔/팩스 로그 수집 기능 구현 (RPC 기반)
* Crash log, Journal log, 디스크 사용량 기반 압축 로직 구현

**성과:**

* 복합기 장애 대응력 향상
* 디스크 공간 최적화

**프로젝트 상세:**

* [✅ 로그/디버깅 시스템 개선](./projects/hp-log-debug-system.md)

### 🔹 RPC 통신 라이브러리 및 샘플 앱 구현 (2017.03 \~ 2018.03)

* 멀티코어 복합기 환경에서의 RPC 통신 라이브러리 설계
* 샘플 애플리케이션 작성 및 타 팀 배포

**성과:**

* 안정적인 멀티코어 통신 체계 구현
* 협업 환경 강화 및 생산성 증가

**프로젝트 상세:**

* [✅ RPC 통신 라이브러리 및 샘플 앱 구현](./projects/hp-rpc-library-sample-app.md)

[🔙 돌아가기](./README.md)
