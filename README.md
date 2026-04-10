# Multiple AWS lambda version control with AWS SAM
# 다중 람다 버전 관리 CI/CD 환경 구현

## 실행 전 build 방법
sam build --use-container
![alt text](<img/스크린샷 2026-04-10 오후 4.15.59.png>)


## 각 Function 실행
sam local invoke [함수명]

실행결과

{"statusCode": 200, "body": "{\"message\": \"hello world\"}"}

{"statusCode": 200, "body": "{\"message\": \"bye world\"}"}

![alt text](<img/스크린샷 2026-04-10 오후 4.18.42.png>)

## 배포 방법
sam deploy --guided

단순 반영 후
![alt text](image.png)

s3에 버킷 자동생성된 모습
![alt text](image-1.png)