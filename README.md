# vite를 이용한 포트폴리오 사이트 만들기

## vite를 사용하는 이유

Vite는 JavaScript 프레임워크 및 빌드 도구로, 빠른 개발 및 효율적인 웹 애플리케이션을 만드는 데 도움을 주는 몇 가지 장점을 가지고 있습니다:

빠른 개발 속도: Vite는 개발 서버를 통해 빠르게 라이브 리로드를 제공하며, 변경된 코드만 다시 컴파일하여 개발 시간을 단축시킵니다. 이로 인해 개발자는 변경 사항을 실시간으로 확인할 수 있어 빠른 개발을 할 수 있습니다.

빠른 초기 빌드: Vite는 모듈 의존성을 효율적으로 처리하여 초기 로드 속도를 최적화합니다. 이는 사용자가 애플리케이션을 처음 로드할 때 더 빠른 성능을 제공합니다.

단일 파일 컴포넌트: Vite는 Vue.js와 함께 사용되는 경우, 단일 파일 컴포넌트 (SFC)를 지원합니다. 이를 통해 컴포넌트 기반의 개발을 간편하게 할 수 있으며 코드를 모듈화하고 재사용성을 높일 수 있습니다.

더 나은 모듈 시스템: Vite는 ES 모듈 (ECMAScript 모듈)을 사용하며, CommonJS나 AMD와 같은 다른 모듈 시스템과 비교해 더 효율적이고 간결한 코드를 작성할 수 있게 합니다.

다양한 프레임워크 지원: Vite는 Vue.js, React, Svelte 및 기타 프레임워크와 함께 사용할 수 있습니다. 이는 다양한 프로젝트에서 선택적으로 Vite를 도입할 수 있음을 의미합니다.

TypeScript 지원: Vite는 TypeScript를 기본적으로 지원하므로 타입 안정성을 확보하고 더 강력한 코드 검사를 수행할 수 있습니다.

플러그인 생태계: Vite는 다양한 플러그인을 사용하여 빌드 프로세스를 확장하고 사용자 정의할 수 있도록 확장성을 제공합니다.

이러한 이점들은 Vite를 선택할 때 고려할 만한 이유 중 일부입니다. 그러나 프로젝트의 특정 요구 사항과 개발 스택에 따라 다른 도구와의 비교 검토가 필요할 수 있습니다.

1. [vite](https://ko.vitejs.dev/guide/why.html)

## 구현기능

- 구글 폰트 적용 https://github.com/studio-freight/lenis
- smooth 효과 적용
- 자바스크립트 메뉴 클릭 이동 효과 적용
- GSAP를 이용한 가로 효과
- 웹표준 준수를 위한 스킵 메뉴 및 aira, role 적용

## 트러블 슈팅

<details>
<summary>git 업로드 버그</summary>
권한으로 인한 업로드 버그 현상이 생김 > 해결
 git push -u origin main  
fatal: unable to access 'https://github.com/ojs104/vite-project2023.git/': The requested URL returned error: 403
</details>
