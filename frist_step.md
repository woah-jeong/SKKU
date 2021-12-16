tmp- 2021-11-24
start Github

Vcxsr 방화벽 풀어주기 :
https://holeeman.github.io/windows/WSL-2%EC%97%90%EC%84%9C-%EB%A6%AC%EB%88%85%EC%8A%A4-GUI-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8-%EC%8B%A4%ED%96%89/

Broken pipe 해결하기
https://may0301.tistory.com/10
nano ~/.ssh/config (/etc/ssh/ssh_config 또는 /etc/ssh_config)
 Host * ServerAliveInterval 120 TCPKeepAlive no
