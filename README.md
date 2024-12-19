# StarProxy
스타프록시 - 서버를 잇다.
# 사용방법
```
java -jar StarProxy.jar
....
[06:00:00]         ^
[06:00:00]        / \
[06:00:00]   -----   -----
[06:00:00]   \ STARPROXY /
[06:00:00]    /  /\    \  MADE IN KOREA
[06:00:00]  /   /  \     \
[06:00:00] \   /    \    /
[06:00:00]   V        V
[06:00:00] 스타프록시 버전 1
[06:00:00] Starting proxy server
[06:00:01] Binded Proxy to 0.0.0.0:25565
```
# 스타프록시 스페셜스타
스페셜스타는 스타프록시를 확장해주는 JAR입니다.\
ViaProxySync: ViaProxy와 연동합니다. 완전연동(AUTH/ADDR/BOTH) 활성화한경우 스타프록시 javaagent가 ViaProxyAuthHook를 사용하여야 하며(AUTH/BOTH) 기존의 서버주소;서버포트+서버버전.starpoxy.주소:포트 양식은 효력을 잃게됩니다!(ADDR/BOTH)
# 주소
스타프록시를 공개서버 모드로 하고 사용하려면, 다음과 같이 주소를 입력하세요.
```
서버주소;서버포트+서버버전.starproxy.주소:포트
```
예시:
```
astn.kr;25565+Bedrock-1.21.40.starproxy.approximasterhosting2004.ddnsgeek.com:25565/19132
```
경고: ;, +가 있는 경우에는 
