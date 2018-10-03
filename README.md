smart-room-WAS
===============

Kakao Chatbot 연동 투숙객 편의/보안 제공 스마트객실 IoT 플랫폼 WAS
<br>
WAS(Web Application Server) of smart room IoT platform for guest convenience and security interlocking with Kakao Chatbot
<br><br><br>


프로젝트 설명 (Project Description)
====================================

- 객실에 IoT 센서 구성 및 객실 관리자 웹 페이지 제작
- 체크 인 시 온라인 키 발급 (인원 수 제한 X) => Kakao Chatbot 이용
- 객실 무단 침입 발생 시 투숙객에게 즉시 문자 알림 및 실시간 CCTV 모니터링 지원
- 특정 시간 동안 객실 내 투숙객 미감지시 자동 전력 차단
- IoT 서버 불법 접근 방지 위해 MQTT 통신 시 SSL/TLS 보안 프로토콜 적용
<br>
- Each room is comprised of IoT sensors and admin web page for room manager.
- Online keys are issued when guests check in (no limit on the number of keys) => use Kakao Chatbot.
- Guests are notified by sms message and provided with real-time monitoring CCTV when a trespass occurs.
- Power interruption occurs after certain seconds if there was no human detect in room.
- SSL/TLS security protocol during MQTT communications for the prevention of illegal accesses.



프로젝트 구성 (Project Composition)
====================================

- smart-room-WAS
- MQTT Broker Server (Mosquitto SSL/TLS)
- [smart-room-IoT] (https://github.com/circleGlasses/smart-room-IoT) (Raspberry Pi codes)
<br><br><br>


WAS 구성 (WAS Composition)
===========================

- Node-red
- Firebase Real-Time Database (noSQL)
- Kakao Chatbot API
- SMS API (청기와LAB)
<br><br><br>


WAS 개발 환경 (WAS Development Environment)
============================================

- Windows 10 Pro, 64-bit
- Node.js v8.12.0
- Npm v6.4.1
- Node-Red v0.19.4
<br><br><br>


설치 (Install)
===============

1. Node-Red 설치
2. Node-Red [Projects 활성화] (https://nodered.org/docs/user-guide/projects/)
3. Clone Repository
4. 해독 키 입력
<br>
1. Install Node-Red
2. Node-red [Enable Projects] (https://nodered.org/docs/user-guide/projects/)
3. Clone Repository
4. Input decryption key
