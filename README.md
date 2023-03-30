
# [CS] network

## topology(토폴로지) : 링크가 어떻게 배치되어 있는지에 대한 방식이자 연결 형태

1. tree
2. bus - LAN에 사용, 스푸핑(Spoofing)이 가능한 문제점.
3. star
4. ring
5. mesh - 그물망 형태

## 네트워크 분류

1. LAN(Local Area Network)
2. MAN(Metropolitan Area Network)
3. WAN(Wide Area Network)

#### 성능 분석 명령어

1. ping
2. netstat
3. nslookup
4. tracert(리눅스 기반은 traceroute)

## TCP/IP 4계층

1. 애플리캐리션 계층(FTP, HTTP, SSH, SMTP, DNS) - 서비스를 사람들에게 제공하는 층
2. 전송 계층(TCP, UDP, QUIC) - TCP -> 가상회선 패킷 교환 방식 사용, UDP -> 데이터그램 패킷 교환 방식 사용
3. 인터넷 계층(IP, ARP, ICMP)
4. 링크 계층(이더넷(유선LAN,무선LAN) - 실질적으로 데이터 전달
<br>으로 구성


