# The Dragon Academy

영어 단어와 문법을 연습하는 React 기반 웹게임입니다.

## GitHub Pages에 올리는 방법

1. 이 ZIP 파일의 압축을 풉니다.
2. GitHub에서 새 저장소를 만들고, 압축을 푼 폴더 안의 파일을 **전부** 올립니다.
   - `package.json`, `index.html`, `src`, `.github` 등이 저장소 첫 화면에 보여야 합니다.
   - 바깥쪽 `the-dragon-academy` 폴더 자체가 한 단계 더 들어가지 않게 주의하세요.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Build and deployment → Source**를 `GitHub Actions`로 선택합니다.
5. 상단 **Actions** 탭에서 `Deploy to GitHub Pages` 작업이 완료될 때까지 기다립니다.
6. 다시 **Settings → Pages**에 들어가 표시된 게임 주소를 엽니다.

주소는 보통 아래 형식입니다.

```text
https://깃허브아이디.github.io/저장소이름/
```

## 컴퓨터에서 먼저 실행해 보기

Node.js가 설치되어 있다면 프로젝트 폴더에서 다음 명령을 실행합니다.

```bash
npm install
npm run dev
```

## 참고

- 화면 이미지, 글꼴, 배경 질감과 BGM 일부는 외부 인터넷 주소에서 불러옵니다.
- 학교 네트워크에서 해당 주소를 차단하면 이미지나 음악이 나오지 않을 수 있지만 게임 자체는 실행됩니다.
- 브라우저의 자동 재생 정책 때문에 첫 화면에서 버튼을 누르기 전에는 음악이 재생되지 않을 수 있습니다.
