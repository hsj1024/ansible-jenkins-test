# Jenkins-Ansible Integration Demo

이 프로젝트는 macOS 환경에서 Jenkins와 Ansible을 연동하여, Ansible 플레이북을 Jenkins Job으로 실행하는 자동화 실습입니다.

---

## 📦 프로젝트 구성

- Jenkins 설치 및 초기 설정 (Homebrew 사용)
- Ansible 설치 및 간단한 테스트 플레이북 실행
- Jenkins에서 Ansible 플러그인을 통해 플레이북 자동 실행
- Jenkins Job 설정 및 빌드 테스트

---

## 🛠 기술 스택

| 항목     | 내용                            |
|--------|---------------------------------|
| OS     | macOS                           |
| 도구    | Jenkins (LTS), Ansible, Homebrew |
| 언어    | YAML, Shell Script               |

---

## 📁 주요 파일

| 파일명             | 설명                           |
|------------------|------------------------------|
| `playbook.yml`   | 로컬에서 테스트용 파일 생성 플레이북       |
| `.gitignore`     | 생성된 파일 무시 처리 설정               |
| `README.md`      | 프로젝트 개요 및 실행 가이드             |

---

## 📌 실행 방법 요약

1. Jenkins 설치:  
   `brew install jenkins-lts`

2. Ansible 설치:  
   `brew install ansible`

3. 플레이북 실행:  
   `ansible-playbook ~/playbook.yml`

4. Jenkins Job에서 Build Script 등록:  
   `/opt/homebrew/bin/ansible-playbook /Users/사용자명/경로/playbook.yml`

---

## 📚 Velog 가이드

👉 [Jenkins + Ansible 연동 실습 블로그 포스트 보기](https://velog.io/@tjeudeud/Jenkins-Ansible-%EB%A1%9C%EC%BB%AC-%EC%8B%A4%EC%8A%B5-%EC%A7%84%ED%96%89%ED%95%B4%EB%B3%B4%EA%B8%B0-Mac-%EC%9A%A9
)
