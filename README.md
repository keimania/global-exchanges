# 🌐 Global Exchange & Order Types Architecture (전세계 주요 증권거래소 주문 유형 및 전산 아키텍처)

전세계 23개 주요 거래소(NYSE, NASDAQ, LSE, JPX, HKEX, Euronext, KRX 등)와 NASDAQ 옵션 시장(The Nasdaq Options Market)의 공식 규정집, 매칭 엔진 코어(INET, Optiq, Arrowhead, T7, Pillar, EXTRADE 등), 체결 알고리즘 및 호가 규칙을 총망라한 **이중 언어(한국어 🇰🇷 / English 🇺🇸)** 오픈 도큐멘테이션 프로젝트입니다.

📱 **모바일 & 웹 라이브 뷰어**: [https://keimania.github.io/global-exchanges/](https://keimania.github.io/global-exchanges/)

---

## 🏛️ 수록 거래소 목록 (Total 23 Exchanges + NOM Rules)

모든 문서는 **한국어 (`ko/`)** 및 **영어 (`en/`)** 버전으로 각각 완비되어 있으며, 웹 뷰어 상단 스위처를 통해 즉시 원클릭 전환이 가능합니다.

### 1. 북미 (North America)
- **[NASDAQ (미국 나스닥)](nasdaq.md)**: INET / Eqlipse 4세대 엔진, MELO 10ms 안티-스푸핑, Pegged 프라이싱, MOC/LOC NOII 최소자승법, NOM 옵션 10대 주문 유형 및 WAIT 1초 지연 챔버
- **[NYSE (뉴욕증권거래소)](nyse.md)**: Pillar 엔진, DMM/Floor Broker 동등 배분(Parity & Priority), D-Order 타임스탬프 은닉 난수 스플릿
- **[TMX (토론토증권거래소)](tmx.md)**: TSX Quantum 엔진, Seek Dark 다크풀 라우팅, Bypass 주문 OPR 회피

### 2. 아시아-태평양 (Asia-Pacific)
- **[KRX (한국거래소)](krx.md)**: EXTRADE 플랫폼, 2025 신설 중간가호가 및 스톱지정가호가, 최유리/최우선지정가호가, 킬스위치 및 자전거래방지
- **[HKEX (홍콩증권거래소)](hkex.md)**: OTP-C 플랫폼, 10호가 관통 ELO(Enhanced Limit Order), VCM 변동성 제어
- **[JPX (도쿄증권거래소)](jpx.md)**: 후지츠 Arrowhead 4.0 엔진, 특기세호가(Tokubetsu Kehai) 3분 동결 이타요세(Itayose)
- **[SSE (상하이증권거래소)](sse.md)**: 신세대 매칭 시스템, BOC (최우선 5호가 즉결 취소), ±10% 상하한 밴드 가드
- **[SZSE (선전증권거래소)](szse.md)**: 5세대 매칭 시스템, Counterparty Best Price 및 Own Side Best Price 전술 호가
- **[TWSE (대만증권거래소)](twse.md)**: 연속 매매 엔진, ROD/IOC/FOK 삼중 배열
- **[SGX (싱가포르거래소)](sgx.md)**: Titan 엔진, Synthetic Queue 스톱 방호막, 세션 상태 기반 경매
- **[ASX (호주증권거래소)](asx.md)**: ASX Trade & Centre Point 다크풀 스윕 라우터, 난수 변이 Iceberg 리필
- **[Bursa Malaysia (말레이시아거래소)](bursa_malaysia.md)**: BTS2 (나스닥 엔진 공급), LOO/LOC 장전/마감 단일가 타임스탬프

### 3. 유럽 (Europe)
- **[LSE (런던증권거래소)](lse.md)**: Millennium Exchange 코어, SETS Market to Limit, GTT(Good Till Time) 나노초 카운트다운
- **[Euronext (유로넥스트)](euronext.md)**: Optiq 플랫폼, Market to Limit (MTL) 1호가 격발 후 강제 지정가 전환, MiFID II 다크-아이스버그
- **[Deutsche Börse (독일거래소 - Xetra)](deutsche_borse.md)**: T7 아키텍처, OCO(One Cancels Other) 원자적 브라켓 킬스위치, Trailing Stop 추종
- **[SIX Swiss Exchange (스위스거래소)](six.md)**: SwissAtMid 중간가 스텔스 다크풀, Swiss Liquidity Sweep (SLS) 하이브리드 라우터
- **[Borsa Italiana (이탈리아 밀라노)](borsa_italiana.md)**: Optiq 통합 코어, Dynamic/Static Collar 변동성 서킷 브레이커
- **[BME (스페인거래소)](bme.md)**: SIBE 시스템, 정적 트리거 감시 모니터 큐
- **[Nasdaq Nordic (나스닥 노르딕)](nasdaq_nordic.md)**: INET Nordic, Nordic@Mid 다크 인클레이브, 스마트 오더 라우팅(SOR)

### 4. 신흥국 및 중동 (Emerging & Middle East)
- **[NSE India (인도국립증권거래소)](nse_india.md)**: NEAT+ 플랫폼, Disclosed Quantity(인도식 아이스버그), AMO(애프터 마켓 오더)
- **[BSE (봄베이증권거래소)](bse.md)**: BOLT Plus 아키텍처, 연쇄 플래시 크래시 방호 감시 노드
- **[JSE (요하네스버그거래소)](jse.md)**: MillenniumIT 개조 엔진, 다이내믹 페깅 및 LIS 히든 블록
- **[Saudi Tadawul (사우디 타다울)](tadawul.md)**: Nasdaq X-Stream INET, Negotiated Deals 오프북 장외 합의체 블록 결제

### 5. 특별 법률 및 규정집 (Special Regulatory Rules)
- **[NASDAQ Options Market Rules (한글 번역본)](ko/NASDAQ_OPTIONS_RULES.md)**: 208페이지 전권 대량 번역 (Chapter I ~ XIV)
- **[NASDAQ Options Market Rules (영문 원본 추출본)](en/NASDAQ_OPTIONS_RULES.md)**: 공식 규정집 원문 텍스트 데이터

---

## 🚀 주요 기능 (Web Viewer Features)
- **🇰🇷 / 🇺🇸 듀얼 랭귀지 원클릭 전환**: 상단 버튼 하나로 동일 문서의 한국어/영어 즉시 전환
- **반응형 모바일 UI & 완벽한 테이블 렌더링**: 테이블 깨짐 현상 완전 해결, 가로 터치 스크롤 지원
- **실시간 다크/라이트 모드**: 사용자의 눈 피로도를 낮추는 테마 토글 및 세션 저장
- **글자 크기 조절**: 모바일 환경에서 가독성을 극대화하기 위한 A- / A / A+ 조절기
- **목차(TOC) 바텀 시트**: 수백 줄에 달하는 기관급 기술 문서의 특정 섹션으로 원클릭 스무스 점프
- **실시간 거래소 검색**: 키워드 입력(Cmd+K / Ctrl+K 지원)을 통한 즉각적인 거래소 필터링
- **수식(KaTeX) 및 코드 렌더링**: 매칭 엔진 배분 수식 및 알고리즘 의사코드 완벽 렌더링
