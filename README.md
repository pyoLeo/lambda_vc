# Multiple AWS lambda version control with AWS SAM
## 다중 람다 버전 관리 CI/CD 환경 구현

sam build --use-container
![alt text](<img/스크린샷 2026-04-10 오후 4.15.59.png>)


### 각 Function 실행
sam local invoke [함수명]

실행결과

{"statusCode": 200, "body": "{\"message\": \"hello world\"}"}

{"statusCode": 200, "body": "{\"message\": \"bye world\"}"}

![alt text](<img/스크린샷 2026-04-10 오후 4.18.42.png>)

