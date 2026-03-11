<div align="center">

🇰🇷 **한국어** | 🇺🇸 [**English**](./README.md)

<!-- 헤더 배너 -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:3B82F6,100:0D1117&height=230&section=header&text=GAYOUNG%20LEE&fontSize=65&fontColor=FFFFFF&animation=fadeIn&fontAlignY=33&desc=%EB%B3%B4%EC%95%88%20%EC%97%B0%EA%B5%AC%EC%9B%90%20%7C%20%EB%93%9C%EB%A1%A0%20%ED%95%B4%EC%BB%A4&descSize=20&descColor=93C5FD&descAlignY=55"/>

<!-- 타이핑 애니메이션 -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=60A5FA&center=true&vCenter=true&repeat=true&width=550&height=45&lines=%EC%B7%A8%EC%95%BD%EC%A0%90%EC%9D%84+%EC%B0%BE%EC%95%84+%EB%8D%94+%EC%95%88%EC%A0%84%ED%95%9C+%EC%84%B8%EC%83%81%EC%9D%84+%EB%A7%8C%EB%93%AD%EB%8B%88%EB%8B%A4.;%F0%9F%94%90+%EA%B3%B5%EA%B2%A9+%EB%B3%B4%EC%95%88+%7C+%EB%A6%AC%EB%B2%84%EC%8A%A4+%EC%97%94%EC%A7%80%EB%8B%88%EC%96%B4%EB%A7%81;%F0%9F%9A%81+%EB%93%9C%EB%A1%A0+%ED%95%B4%ED%82%B9+%7C+MAVLink+%EC%B7%A8%EC%95%BD%EC%A0%90+%EA%B3%B5%EA%B2%A9" alt="Typing SVG" /></a>

<br/><br/>

<img src="https://img.shields.io/badge/%EC%A3%BC%EB%A0%A5-%EA%B3%B5%EA%B2%A9%20%EB%B3%B4%EC%95%88-2563EB?style=for-the-badge&logo=hackaday&logoColor=white"/>
<img src="https://img.shields.io/badge/%EC%A0%84%EB%AC%B8-%EB%93%9C%EB%A1%A0%20%EB%B3%B4%EC%95%88-3B82F6?style=for-the-badge&logo=dji&logoColor=white"/>
<img src="https://img.shields.io/badge/%EB%8F%84%EA%B5%AC-%EB%A6%AC%EB%B2%84%EC%8A%A4%20%EC%97%94%EC%A7%80%EB%8B%88%EC%96%B4%EB%A7%81-6366F1?style=for-the-badge&logo=hackthebox&logoColor=white"/>

</div>

---

## $ 자기소개

```python
class 보안연구원:
    def __init__(self):
        self.이름     = "이가영 (Gayoung Lee)"
        self.역할     = "보안 연구원"
        self.관심분야 = [
            "🚁 드론 보안 & MAVLink 프로토콜 취약점 공격",
            "🔓 취약점 연구 & 리버스 엔지니어링",
            "🛡️ 보안 자동화 (KISA 컴플라이언스)",
            "🐳 DevSecOps & 컨테이너 보안",
        ]
        self.현재_작업 = "무인 시스템의 취약점을 사냥하는 중"

    def 인사(self):
        print("취약점을 찾아 더 안전한 세상을 만듭니다.")

me = 보안연구원()
me.인사()
```

---

## $ 기술 스택

<div align="center">

### 🗡️ 공격 (Offensive)

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/IDA_Pro-4B275F?style=flat-square&logo=hexrays&logoColor=white"/>
<img src="https://img.shields.io/badge/Ghidra-FF6600?style=flat-square&logo=nsa&logoColor=white"/>
<img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=portswigger&logoColor=white"/>
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white"/>
<img src="https://img.shields.io/badge/MAVLink-00BCD4?style=flat-square&logo=drone&logoColor=white"/>

### 🛡️ 방어 (Defensive)

<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/Shell_Script-121011?style=flat-square&logo=gnu-bash&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white"/>
<img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white"/>

### 💻 개발 (Development)

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>

</div>

---

## $ 주요 프로젝트

<table align="center">
<tr>
<td width="50%">

### 🚁 MAVLink Key Injection Attack
**드론 원격 제어권 탈취 연구**

ArduPilot 기반 드론의 MAVLink2 미서명 통신 취약점 발견 → 서명 키 주입으로 드론 제어권 탈취 공격 연구·구현

`Python` `pymavlink` `IDA Pro` `Firmware RE`

[![Repo](https://img.shields.io/badge/-저장소_보기-2563EB?style=flat-square&logo=github&logoColor=white)](https://github.com/young-ee30/MAVLink-Key-Injection-Attack)

</td>
<td width="50%">

### 🛡️ 보안 취약점 진단 자동화
**KISA 기반 엔터프라이즈 보안 플랫폼**

대규모 서버 환경에서 KISA 보안 취약점 점검 → 조치 → 보고서 생성까지 전 과정을 자동화

`Shell` `Ansible` `Python` `Linux`

[![Repo](https://img.shields.io/badge/-비공개_저장소-6366F1?style=flat-square&logo=github&logoColor=white)](https://github.com/young-ee30)

</td>
</tr>
<tr>
<td width="50%">

### 🛒 ShopEasy API 서버
**이커머스 백엔드 플랫폼**

사용자 인증, 상품 관리, 주문 처리 기능을 갖춘 RESTful API 서버 구축

`JavaScript` `Node.js` `MySQL` `REST API`

[![Repo](https://img.shields.io/badge/-비공개_저장소-6366F1?style=flat-square&logo=github&logoColor=white)](https://github.com/young-ee30)

</td>
<td width="50%">

### 🤖 Notion → Tistory 자동화 봇
**블로그 자동 발행 시스템**

노션 페이지를 티스토리 블로그 포스트로 자동 변환·업로드하는 파이썬 봇

`Python` `Notion API` `Tistory API` `Automation`

[![Repo](https://img.shields.io/badge/-비공개_저장소-6366F1?style=flat-square&logo=github&logoColor=white)](https://github.com/young-ee30)

</td>
</tr>
</table>

---

## $ 연락처

<div align="center">

<a href="mailto:eyoungblll30@gmail.com">
<img src="https://img.shields.io/badge/%EC%9D%B4%EB%A9%94%EC%9D%BC-eyoungblll30@gmail.com-2563EB?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://github.com/young-ee30">
<img src="https://img.shields.io/badge/GitHub-young--ee30-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:3B82F6,100:0D1117&height=120&section=footer&animation=twinkling"/>

</div>
