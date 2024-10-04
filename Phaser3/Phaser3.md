# Phaser 3

## 목차

Phaser 3 시작하기
    웹 서버 설치
    에디터 선택
    Phaser 다운로드
    전 세계 여러분 안녕하세요!
    Phaser 예제
    다음 단계
배우다
    API 문서
    첫 번째 게임 만들기
    디스코드 게임 만들기
    Facebook 인스턴트 게임
    개발 로그
    자습서

### 웹 서버 설치

Python

    import sys
    import BaseHTTPServer
    from SimpleHTTPServer import SimpleHTTPRequestHandler


    HandlerClass = SimpleHTTPRequestHandler
    ServerClass  = BaseHTTPServer.HTTPServer
    Protocol     = "HTTP/1.0"

    if sys.argv[1:]:
        port = int(sys.argv[1])
    else:
        port = 8000
    server_address = ('127.0.0.1', port)

    HandlerClass.protocol_version = Protocol
    httpd = ServerClass(server_address, HandlerClass)

    sa = httpd.socket.getsockname()
    print "Serving HTTP on", sa[0], "port", sa[1], "..."
    httpd.serve_forever()

### 에디터 선택

Vscode

### Phaser 다운로드

번들로 하는게 좋다는데 그게 뭐지?

### 

일단 WSL로 개발할지 Window로 개발하지 찾아보자

### 첫 번째 Phaser 3 게임 만들기