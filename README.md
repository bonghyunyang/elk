# ELK

## 사용법 정리

### 1. git clone this repository

### 2. docker-compose up -d

### 3. kibana 컨테이너 로그 확인 및 처리 
- 로그 내 "Go to http://0.0.0.0:5601/?code=161462 to get started." 확인 및 진입

### 4. es 컨테이너에서 kibana 토큰 발급
- bin/elasticsearch-create-enrollment-token -s - kibana  명령어 이용, 토큰 발급
- http://0.0.0.0:5601/?code=161462 진입 후 토큰 입력

### 5. 세팅 확인 및 로그인