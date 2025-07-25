# 🐾 동물 보호센터 웹사이트

> 유기동물 정보를 제공하고 입양을 돕는 반응형 웹사이트  
> [🔗 배포 링크 바로가기](https://jhm4591.github.io/animalcenter/)

---

## 📌 프로젝트 소개

- 개인프로젝트로 진행하였습니다.
- 전국 유기동물 보호센터의 정보를 제공하는 웹사이트입니다.
- 사용자는 지역별 보호소에 있는 유기동물 정보를 조회하고, 입양 가능 여부를 확인할 수 있습니다.
- 공공데이터 API를 활용하여 실시간 데이터를 가져옵니다.

---

## ⛏️ 사용 기술

| Category | Stack |
|---------|-------|
| Frontend | HTML, CSS, JavaScript |
| API | 공공데이터포털 유기동물 정보 API |
| Deployment | GitHub Pages |

---

## 🖥️ 주요 기능

- ✅ 지역별 보호 동물 정보 검색
- ✅ 보호소 정보 및 위치 확인
- ✅ 동물 상세 정보 페이지 제공
- ✅ 반응형 UI 지원 (모바일/태블릿/PC)
- ✅ 공공데이터 API 연동으로 실시간 정보 제공

---

## 📸 미리보기

| 메인 페이지 | 동물 목록 | 상세 정보 |
|------------|----------|-----------|
| ![main](<!-- 이미지 URL 넣기 -->) | ![list](<!-- 이미지 URL 넣기 -->) | ![detail](<!-- 이미지 URL 넣기 -->) |

<!-- 예시:
![main](./assets/images/main.png)
![list](./assets/images/list.png)
![detail](./assets/images/detail.png)
-->

---

## 📁 프로젝트 구조

```
animalcenter/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── assets/
│   └── images/
└── README.md
```

---

## 📮 API 출처

- 공공데이터포털 - [유기동물 조회 서비스](https://www.data.go.kr/data/15099892/openapi.do)

---

## 🧑‍💻 개발자

| 이름 | GitHub |
|------|--------|
| jhm4591 | [https://github.com/jhm4591](https://github.com/jhm4591) |

---

## 📌 향후 개선 사항

- [ ] 입양 신청 기능 추가
- [ ] 관리자 페이지 구현
- [ ] 동물 필터 기능 (품종/성별 등)
- [ ] 페이지네이션 기능 추가

---

## 📝 참고 사항

- 공공데이터 포털 API 사용 시 `서비스키` 필요 (JavaScript 코드에 직접 포함되어 있음)
- 일부 보호소 데이터는 사진이나 정보가 누락될 수 있음
- API 응답 속도에 따라 동물 목록이 늦게 로딩될 수 있음
