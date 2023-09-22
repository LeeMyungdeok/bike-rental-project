# 공공자전거 대여 서비스 구현

<br>

<p align="center">
<img width="400px" src="https://github.com/LeeMyungdeok/bike-rental-project/assets/115915362/8a87e8d2-42c2-4415-9613-8fcdd53744d2">
<br><br>
<img src= "https://img.shields.io/badge/Javascript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white" />
<img src= "https://img.shields.io/badge/nodedotjs-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src= "https://img.shields.io/badge/mysql-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src= "https://img.shields.io/badge/mongodb-47A248?style=flat-square&logo=mongodb&logoColor=white" />
<img src= "https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white" />
<img src= "https://img.shields.io/badge/inux-FCC624?style=flat-square&logo=linux&logoColor=white" />

<br>
</p>

## 주제 선정 이유

서울의 공공 자전거 서비스인 '따릉이'의 이용률이 최근 증가하고 감소함에 따라 사람들의 건강에 대한 관심이 높아지고 있습니다. 이에 우리 팀은 이러한 요즘 핫한 주제인 건강에 관한 프로젝트를 진행하고자 합니다. 이 프로젝트의 목표는 '따릉이' 서비스를 대상으로 한 자전거 대여 서비스를 제공하는 것입니다.

### Installing / 설치

#### npm 모듈 설치 

```
apt install -y npm
```
```
npm install -g nodemon
```
```
npm init -y
```
```
npm install express morgan path body-parser cookie-parser mongoose
```
#### mongodb 설치

```
wget -qO - https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -
```
```
echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/4.4 multiverse" | tee /etc/apt/sources.list.d/mongodb-org-4.4.list
```
```
wget http://archive.ubuntu.com/ubuntu/pool/main/o/openssl/libssl1.1_1.1.1f-1ubuntu2_amd64.deb
```
```
dpkg -i libssl1.1_1.1.1f-1ubuntu2_amd64.deb
```
```
rm -rf libssl1.1_1.1.1f-1ubuntu2_amd64.deb
```
```
apt -y update; apt -y upgrade
```
```
apt -y install mongodb-org
```
```
systemctl start mongod
```
```
systemctl status mongod
```
```
mongod --version
```
```
mongo
```
#### nodejs install
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
```
```
cat ~/.bashrc
```
```
source ~/.bashrc
```
```
nvm --version
```
```
nvm ls-remote
```
```
nvm install v18.15
```
```
nvm install v16.20
```
```
npm install sync-mysql dotevv async axios
```

## back-end 아키텍쳐 설계

<img width="592" alt="스크린샷 2023-09-22 오후 9 31 23" src="https://github.com/LeeMyungdeok/bike-rental-project/assets/115915362/4ac3590d-024c-4318-8427-0a00966efda1">

### 테스트는 이런 식으로 동작합니다
<img src = https://github.com/LeeMyungdeok/bike-rental-project/assets/115915362/05684f2f-010e-4fcc-af81-01fc0040910b>



|                Survey              |                Check Mail               |
| :----------------------------------: | :----------------------------------: |
| <img src='https://user-images.githubusercontent.com/71132893/126994394-48932076-50be-401f-b81a-2e8d63bb5fb8.gif' width='400px' height='200px'>                                 | <img src='https://user-images.githubusercontent.com/71132893/126994395-ed3de24a-a19b-4875-8b02-6ca4b7086aa5.gif' width='400px' height='200px'>                                 |

## Deployment / 배포

Add additional notes about how to deploy this on a live system / 라이브 시스템을 배포하는 방법

## Built With / 누구랑 만들었나요?

* [이름](링크) - 무엇 무엇을 했어요
* [Name](Link) - Create README.md

## Contributiong / 기여

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us. / [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) 를 읽고 이에 맞추어 pull request 를 해주세요.

## Acknowledgments / 감사의 말

* Hat tip to anyone whose code was used / 코드를 사용한 모든 사용자들에게 팁
* Inspiration / 영감
* etc / 기타
