
---

## 🧑‍💼 자기소개 (요약)
- **이름**: 박현성  
- **소속/전공**: 전북대학교 컴퓨터공학과  
- **관심사**: 웹 프론트엔드, 정적 사이트 자동화, 추천 시스템  
- **소셜**: [GitHub](https://github.com/<USERNAME>)  

> 상세 소개와 연락처는 About 페이지 하단(연락하기) 섹션에 있습니다.

---

## 🧪 프로젝트 (예시 3개)
- **AI 캐릭터 생성기**: 인물 사진을 애니메이션 스타일로 변환  
- **화장품 추천 시스템**: 피부톤/선호도 기반 추천  
- **콘텐츠 추천 플랫폼**: 사용자 행동 데이터 기반 개인화 추천

각 프로젝트는 `content/<lang>/project/<name>/index.md`로 관리하며,  
썸네일 이미지는 `image.filename`에 지정합니다(없으면 placeholder).

---

## 🚀 배포 (GitHub Actions)

- **브랜치**: `main` → **Actions 빌드** → `gh-pages` 배포  
- Pages 설정: **Settings → Pages → Branch = `gh-pages`**  
- 캐시 이슈 시:
  ```bash
  hugo mod clean && hugo mod tidy
