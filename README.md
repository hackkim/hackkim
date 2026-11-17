# 김성훈 (SungHoon Kim)

모의해킹 · 모의침투 · 취약점 분석 | Security Researcher

웹 애플리케이션과 인프라 모의해킹, 취약점 분석을 하는 보안 연구원입니다. 현재 whysecurity(주식회사와이시큐리티) 보안 컨설팅팀에서 정보보안 컨설턴트로 일하며, KISA 「주요정보통신기반시설 기술적 취약점 분석·평가 방법 상세가이드」를 기준으로 제조, 중공업, 에너지, 통신/방산 분야 고객사의 웹과 인프라를 진단합니다.

독자 연구로 CVE 9건을 할당받았습니다. 제보는 유지보수 담당자, GitHub Security Advisory, WPScan을 통한 책임 있는 공개로 진행합니다. 서울에서 모의해킹, 모의침투, 취약점 분석 포지션을 찾고 있으며, 대면 또는 하이브리드로 근무할 수 있습니다. 다음 목표는 OSCP입니다.

I am a security researcher focused on web and infrastructure penetration testing and vulnerability analysis. I work as a security consultant at whysecurity, and I have been assigned 9 CVEs through independent research and responsible disclosure. I am based in Seoul and currently preparing for OSCP.

**[LinkedIn](https://www.linkedin.com/in/sunghoon-kim-53369137b/)** · **[TryHackMe](https://tryhackme.com/p/kimsunghoon)** · **[GitHub](https://github.com/hackkim)**

---

## 연구 · 실무 초점 / Focus

- 웹 애플리케이션 모의해킹 (OWASP Top 10, 수동 재현)
- 인프라 취약점 진단 (서버 · 네트워크 · 시스템 · 보안장비)
- 취약점 연구와 책임 있는 공개 (Responsible Disclosure)
- 이전 패치의 불완전 수정(Incomplete Fix) 분석

## CVE (9)

공식 출처(NVD) 기준으로, 제품 · 취약점 유형 · CVSS만 적습니다.

| CVE | 제품 | 유형 | CVSS | NVD |
| --- | --- | --- | --- | --- |
| [CVE-2025-11307](https://nvd.nist.gov/vuln/detail/CVE-2025-11307) | WP Go Maps | Stored XSS | 8.8 High | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2025-11307) |
| [CVE-2025-48095](https://nvd.nist.gov/vuln/detail/CVE-2025-48095) | Survey Maker | Stored XSS | 5.9 Medium | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2025-48095) |
| [CVE-2026-14568](https://nvd.nist.gov/vuln/detail/CVE-2026-14568) | WP User Frontend | Improper Access Control | 6.5 Medium | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-14568) |
| [CVE-2026-66065](https://nvd.nist.gov/vuln/detail/CVE-2026-66065) | ouroboros-ai | Incomplete Fix | v4 8.4 High | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-66065) |
| [CVE-2026-77007](https://nvd.nist.gov/vuln/detail/CVE-2026-77007) | HEL Online Classroom | Sensitive Data Exposure | 7.5 High | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-77007) |
| [CVE-2026-77008](https://nvd.nist.gov/vuln/detail/CVE-2026-77008) | HEL Online Classroom | Improper Access Control | 6.5 Medium | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-77008) |
| [CVE-2026-77010](https://nvd.nist.gov/vuln/detail/CVE-2026-77010) | HEL Online Classroom | Access Control Bypass | 6.5 Medium | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-77010) |
| [CVE-2026-54567](https://nvd.nist.gov/vuln/detail/CVE-2026-54567) | Flask-Reuploaded | Incomplete Fix | 7.5 High | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-54567) |
| [CVE-2026-67325](https://nvd.nist.gov/vuln/detail/CVE-2026-67325) | GitPython | Incomplete Fix | 8.8 High | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-67325) |

GitPython, WP Go Maps, ouroboros-ai, Flask-Reuploaded, HEL Online Classroom에서 High 등급 취약점을 확인했습니다. 이 중 GitPython, Flask-Reuploaded, ouroboros-ai 3건은 이전 패치의 불완전 수정 사례입니다. GitHub Security Advisory에서 reporter credit을 받았습니다.

## 경력 / Experience

**정보보안 컨설턴트 (주임)** — whysecurity(주식회사와이시큐리티) 보안 컨설팅팀

- 약 10여 개 중견 고객사의 인프라 진단을 자산 식별부터 위험도 평가, 조치방안, 보고서 작성까지 수행했습니다.
- OWASP Top 10 기반 웹 모의해킹을 수행하며, 스캐너 결과를 수동으로 재현해 실제 악용 가능 여부를 확인합니다.
- 악성메일 모의훈련 기획·결과 분석과 임직원 보안 인식 진단도 담당합니다.

## 자격 · 교육 / Certifications & Training

- **eJPT** (INE Security, 2024.11)
- **K-Shield Junior 13기** 취약점 분석 전문가 과정 (200시간, 2024.08–2024.10)
- **KISA 헌팅 마스터 2차** B트랙 Web2·Web3 (192시간, 2025.06–2025.08)
- **KISA 버그헌팅 실습 훈련** 스타트업연계과정 (28시간, 2024.06–2024.07)
- **Start-Up K-Shield Jr.** 스타트업 연계 과정 (80시간, 2024.08)
- **Find the Gap** 취약점 연구 및 버그헌팅 활동 인증 (2025.12)
- **TryHackMe** Cyber Security 101 (2025.04), Jr Penetration Tester (2025.05) — 대한민국 5위, 글로벌 상위 1%(Guardian)
- **정보보호관리사 1급** (2022.08)
- **해킹보안전문가 1급 · 3급** (2022.08)
- **Securiti AI Security & Governance**
- **OSCP** 준비 중

## 주요 도구 / Tools

Burp Suite, Nmap, Nessus, Wireshark, FFUF, Metasploit, AFL++, GDB  
Python, C, C++, SQL

---

![GitHub stats](https://github-readme-stats.vercel.app/api?username=hackkim&show_icons=true&theme=transparent)
