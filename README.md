<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:0d1117,100:00ff9c&height=220&section=header&text=SungHoon%20Kim&fontSize=58&fontColor=00ff9c&fontAlignY=38&desc=Penetration%20Tester%20%C2%B7%20Vulnerability%20Researcher&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<a href="https://github.com/hackkim">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=900&color=00FF9C&center=true&vCenter=true&width=640&lines=%24+whoami;%3E+%EB%AA%A8%EC%9D%98%ED%95%B4%ED%82%B9+%C2%B7+%EB%AA%A8%EC%9D%98%EC%B9%A8%ED%88%AC+%C2%B7+%EC%B7%A8%EC%95%BD%EC%A0%90+%EB%B6%84%EC%84%9D;%3E+9+CVEs+via+responsible+disclosure;%3E+Security+Consultant+%40+whysecurity;%3E+Next+target%3A+OSCP" alt="typing"/>
</a>

<br/>

<a href="https://www.linkedin.com/in/sunghoon-kim-53369137b/"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00ff9c"/></a>
<a href="https://tryhackme.com/p/kimsunghoon"><img src="https://img.shields.io/badge/TryHackMe-0d1117?style=for-the-badge&logo=tryhackme&logoColor=00ff9c"/></a>
<a href="https://github.com/hackkim"><img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=00ff9c"/></a>
<img src="https://img.shields.io/badge/CVE-9-00ff9c?style=for-the-badge&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Seoul-KR-00ff9c?style=for-the-badge&labelColor=0d1117"/>

</div>

---

```bash
┌──(hackkim㉿seoul)-[~]
└─$ cat about.txt
```

```yaml
name      : 김성훈 (SungHoon Kim)
role      : 정보보안 컨설턴트 (주임) @ whysecurity (주식회사와이시큐리티)
focus     : [Web Pentest, Infra Assessment, Vulnerability Research, Incomplete-Fix Analysis]
standard  : KISA 주요정보통신기반시설 기술적 취약점 분석·평가 방법 상세가이드
disclosure: Maintainers · GitHub Security Advisory · WPScan
status    : 서울 · 모의해킹/모의침투/취약점 분석 포지션 탐색 중 (대면 · 하이브리드)
next      : OSCP
```

> 웹 애플리케이션과 인프라 모의해킹, 취약점 분석을 하는 보안 연구원입니다. 제조, 중공업, 에너지, 통신/방산 분야 고객사의 웹과 인프라를 진단하고, 독자 연구로 CVE 9건을 할당받았습니다.
>
> Security researcher focused on web & infrastructure penetration testing. 9 CVEs assigned through independent research and responsible disclosure.

---

```bash
└─$ ./list_cves --source nvd
```

<div align="center">

| CVE | Product | Type | CVSS |
| :-- | :-- | :-- | :--: |
| [`CVE-2025-11307`](https://nvd.nist.gov/vuln/detail/CVE-2025-11307) | WP Go Maps | Stored XSS | ![](https://img.shields.io/badge/8.8-HIGH-ff3860?style=flat-square&labelColor=0d1117) |
| [`CVE-2026-67325`](https://nvd.nist.gov/vuln/detail/CVE-2026-67325) | GitPython | Incomplete Fix | ![](https://img.shields.io/badge/8.8-HIGH-ff3860?style=flat-square&labelColor=0d1117) |
| [`CVE-2026-66065`](https://nvd.nist.gov/vuln/detail/CVE-2026-66065) | ouroboros-ai | Incomplete Fix | ![](https://img.shields.io/badge/v4_8.4-HIGH-ff3860?style=flat-square&labelColor=0d1117) |
| [`CVE-2026-54567`](https://nvd.nist.gov/vuln/detail/CVE-2026-54567) | Flask-Reuploaded | Incomplete Fix | ![](https://img.shields.io/badge/7.5-HIGH-ff3860?style=flat-square&labelColor=0d1117) |
| [`CVE-2026-77007`](https://nvd.nist.gov/vuln/detail/CVE-2026-77007) | HEL Online Classroom | Sensitive Data Exposure | ![](https://img.shields.io/badge/7.5-HIGH-ff3860?style=flat-square&labelColor=0d1117) |
| [`CVE-2026-14568`](https://nvd.nist.gov/vuln/detail/CVE-2026-14568) | WP User Frontend | Improper Access Control | ![](https://img.shields.io/badge/6.5-MEDIUM-ffb000?style=flat-square&labelColor=0d1117) |
| [`CVE-2026-77008`](https://nvd.nist.gov/vuln/detail/CVE-2026-77008) | HEL Online Classroom | Improper Access Control | ![](https://img.shields.io/badge/6.5-MEDIUM-ffb000?style=flat-square&labelColor=0d1117) |
| [`CVE-2026-77010`](https://nvd.nist.gov/vuln/detail/CVE-2026-77010) | HEL Online Classroom | Access Control Bypass | ![](https://img.shields.io/badge/6.5-MEDIUM-ffb000?style=flat-square&labelColor=0d1117) |
| [`CVE-2025-48095`](https://nvd.nist.gov/vuln/detail/CVE-2025-48095) | Survey Maker | Stored XSS | ![](https://img.shields.io/badge/5.9-MEDIUM-ffb000?style=flat-square&labelColor=0d1117) |

<sub>Source: NVD · 3 of 9 are incomplete-fix bypasses of prior patches · GHSA reporter credit</sub>

</div>

---

```bash
└─$ cat experience.log
```

```diff
+ [whysecurity] 정보보안 컨설턴트 (주임) · 보안 컨설팅팀
  > 약 10여 개 중견 고객사 인프라 진단: 자산 식별 → 위험도 평가 → 조치방안 → 보고서
  > OWASP Top 10 기반 웹 모의해킹, 스캐너 결과 수동 재현으로 실제 악용 가능성 검증
  > 악성메일 모의훈련 기획·결과 분석, 임직원 보안 인식 진단
```

---

```bash
└─$ ls ./arsenal
```

<div align="center">

![Burp Suite](https://img.shields.io/badge/Burp_Suite-0d1117?style=for-the-badge&logo=burpsuite&logoColor=00ff9c)
![Nmap](https://img.shields.io/badge/Nmap-0d1117?style=for-the-badge&logoColor=00ff9c)
![Nessus](https://img.shields.io/badge/Nessus-0d1117?style=for-the-badge&logo=tenable&logoColor=00ff9c)
![Wireshark](https://img.shields.io/badge/Wireshark-0d1117?style=for-the-badge&logo=wireshark&logoColor=00ff9c)
![FFUF](https://img.shields.io/badge/FFUF-0d1117?style=for-the-badge&logoColor=00ff9c)
![Metasploit](https://img.shields.io/badge/Metasploit-0d1117?style=for-the-badge&logo=metasploit&logoColor=00ff9c)
![AFL++](https://img.shields.io/badge/AFL++-0d1117?style=for-the-badge&logoColor=00ff9c)
![GDB](https://img.shields.io/badge/GDB-0d1117?style=for-the-badge&logo=gnu&logoColor=00ff9c)
<br/>
![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=00ff9c)
![C](https://img.shields.io/badge/C-0d1117?style=for-the-badge&logo=c&logoColor=00ff9c)
![C++](https://img.shields.io/badge/C++-0d1117?style=for-the-badge&logo=cplusplus&logoColor=00ff9c)
![SQL](https://img.shields.io/badge/SQL-0d1117?style=for-the-badge&logo=mysql&logoColor=00ff9c)

</div>

---

```bash
└─$ cat certs_and_training.txt
```

```text
[✔] eJPT ............................................. INE Security · 2024.11
[✔] K-Shield Junior 13기 취약점 분석 전문가 과정 ........ 200h · 2024.08–2024.10
[✔] KISA 헌팅 마스터 2차 B트랙 (Web2·Web3) ............. 192h · 2025.06–2025.08
[✔] KISA 버그헌팅 실습 훈련 스타트업연계과정 ............ 28h · 2024.06–2024.07
[✔] Start-Up K-Shield Jr. 스타트업 연계 과정 ........... 80h · 2024.08
[✔] Find the Gap 취약점 연구 및 버그헌팅 활동 인증 ...... 2025.12
[✔] TryHackMe Cyber Security 101 / Jr Penetration Tester · 2025.04 / 2025.05
    └─ 대한민국 5위 · Global Top 1% (Guardian)
[✔] 정보보호관리사 1급 ................................. 2022.08
[✔] 해킹보안전문가 1급 · 3급 ............................ 2022.08
[✔] Securiti AI Security & Governance
[ ] OSCP ............................................. in progress_
```

---

<div align="center">

<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=hackkim&theme=github_dark"/>
<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=hackkim&theme=github_dark"/>

<img src="https://streak-stats.demolab.com?user=hackkim&theme=dark&hide_border=true&background=0d1117&ring=00ff9c&fire=00ff9c&currStreakLabel=00ff9c&sideLabels=00ff9c&dates=8b949e" width="70%"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=hackkim&bg_color=0d1117&color=00ff9c&line=00ff9c&point=ffffff&area=true&area_color=00ff9c&hide_border=true" width="100%"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff9c,50:0d1117,100:000000&height=120&section=footer" width="100%"/>

</div>
