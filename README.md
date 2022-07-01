# StudyTCPIP
Linux, Tcp/ip 학습을 위한 리포지토리

## Day 1
  - VMware Workstation 설치, 실행
  - Ubuntu 설치, 실행
  - Putty 설치, 실행
  - Linux의 기본명령어 학습
  - make 명령어, makefile 생성 실습

## Day 2
  - TCP / IP 기본내용 이해
  - TCP 기본 Server, Client code 구축
  
## Day 3
  - TCP Socket type, protocol
  - 주소정보의 표현(sockaddr_in, in_addr struct 분석)
  - Endian Conversions, inet_addr, inet_aton, inet ntoa
  - socket(), bind(), listen(), accept(), read() / write() 함수를 통한 TCP 통신 학습
  - TCP protocol stack(Link => IP => TCP / UDP => APPLICATION)
  - TCP Server, Client code 분석
  - lterative 기반의 Server, Client 구현

## Day 4
  - UDP Socket의 특성(Best effort, Tcp와 Flow control 차이)
  - sendto(), recvfrom() 함수를 통한 UDP 통신 학습, TCP와 차이 습득
  - UDP Server, Client code 분석

## Day 5
  - Socket Half close를 위한 Socket, Stream, shutdown() 함수 이해
  - Domain => Ip Address(gethostbyname() 함수)
  - Ip Address => Domain(gethostbyaddr() 함수)
  - Socket의 Option과 입출력(getsockopt(), setsockopt())
  - 주소할당 에러(Binding Error) => Tiem-wait, SO_REUSEADDR
  - Nagle Algorithm 이해

## Day 6
  - Process의 이해(fork() 함수)
  - Zombie Process 발생과 해결 => wait(), waitpid(), siganl handling(sigaction() 함수)
  - Multitasking 기반 Multiple access Server 구현
  - Pipe 기반의 Process간 통신 이해
  - Message를 저장하는 형태의 Echo server 구현
