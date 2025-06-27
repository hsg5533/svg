# SVG 레포지토리

이 저장소는 웹 프로젝트에서 사용 가능한 다양한 SVG 리소스(아이콘, 일러스트, 예제 등)를 제공합니다.

## 📑 목차

- [소개](#소개)
- [특징](#특징)
- [설치](#설치)
- [사용법](#사용법)

## 소개

이 레포지토리에는 다음과 같은 SVG 리소스가 포함되어 있습니다:
프로젝트에 벡터 기반 이미지를 손쉽게 통합할 수 있습니다.

## 특징

- **해상도 무관**: 고해상도 디스플레이에서도 선명함
- **경량 파일**: 최적화된 SVG로 빠른 로딩
- **커스터마이징**: 색상, 크기, 애니메이션 적용 가능
- **잘 정리된 구조**: 카테고리별로 파일 관리 용이

## 설치

```bash
git clone https://github.com/hsg5533/svg.git
cd svg
```

## 사용법

### 1. 외부 파일로 불러오기

```html
<img src="./icons/icon-name.svg" alt="아이콘 설명" />
```

### 2. 인라인 SVG 사용

```html
<div class="icon">
  <!-- 인라인 SVG 예제 -->
  <svg
    width="24"
    height="24"
    viewBox="0 0 24 24"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path d="..." fill="#000" />
  </svg>
</div>
```

### 3. CSS 배경으로 사용

```css
.icon-bg {
  width: 48px;
  height: 48px;
  background-image: url("../icons/icon-name.svg");
  background-size: contain;
  background-repeat: no-repeat;
}
```

## 컨트리뷰션

1. 이 저장소를 Fork 합니다.
2. 새로운 브랜치를 만듭니다: `git checkout -b feature/your-feature`
3. 변경사항을 커밋합니다: `git commit -m "Add new SVG resource"`
4. 원격 저장소에 푸시합니다: `git push origin feature/your-feature`
5. Pull Request를 생성합니다.
