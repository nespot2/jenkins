# docker를 이용한 jenkins 설치 및 실행

- jenkins 설치 및 실행 명령어

```
docker-compose up -d
```

- awscli를 사용하기 위해 .aws 폴더에 credentials를 생성

```
[default]
aws_secret_access_key = <key>
aws_access_key_id = <key>
```


### 참조

- [Installing Jenkins](https://www.jenkins.io/doc/book/installing/)
- [Jenkins 와 Docker 그리고 AWS CLI 삽질기 정리하기](https://medium.com/@pks2974/jenkins-%EC%99%80-docker-%EA%B7%B8%EB%A6%AC%EA%B3%A0-aws-cli-%EC%82%BD%EC%A7%88%EA%B8%B0-%EC%A0%95%EB%A6%AC%ED%95%98%EA%B8%B0-e728986960e2)