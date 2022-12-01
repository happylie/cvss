# cvss
## CVSS v3.1 Calculator Korean description version site
- CVSS(Common Vulnerability Scoring System)
<hr>

### 1. 관련 내용 설명
해당 내용은 chandanbn의 cvss를 다운로드 받아 수정 하였습니다.
<br>
chandanbn에게 감사 인사 드립니다.
- Bootstrap을 이용하여 외간을 조금 변경 및 검색 기능을 추가 하였습니다. 
- 영문화 된 설명 부분에 대해서 한국어로 번역 하였습니다.
- Docker 이미지를 만들었고 Docker Hub에 배포 하였습니다. 

I downloaded and modified the cvss of Chandanbn.
<br>
Thank you to Chandanbn.
- I changed the outer space a little bit and added a search function using Bootstrap. 
- I translated the English-language explanation into Korean.
- I created a Docker image and distributed it to Docker Hub.

### 2. Docker Build & Image Run
```bash
$ docker pull docker.io/happylie/web-cvss-calc:latest
latest: Pulling from happylie/web-cvss-calc
ca7dd9ec2225: Already exists
76a48b0f5898: Already exists
2f12a0e7c01d: Already exists
1a7b9b9bbef6: Already exists
b704883c57af: Already exists
4342b1ab302e: Already exists
8f3030c135be: Already exists
Digest: sha256:abc104428528d7762dd63b242444e31a6baca41fa1f22fa197ba4e25e3b18a5c
Status: Downloaded newer image for happylie/web-cvss-calc:latest
docker.io/happylie/web-cvss-calc:latest

$ docker images
REPOSITORY             TAG       IMAGE ID       CREATED          SIZE
happylie/web-cvss-calc   latest    9263ecd35ca0   7 minutes ago   24.8MB

$ docker run -p 80:80 9263ecd35ca0
```

### 3. 참고 URL
- https://github.com/chandanbn/cvss
- https://cvssjs.github.io
- https://happylie.tistory.com/131