# 📚 독서 타이머

독서 시작과 완료 시간을 기록하고, 사진을 촬영하여 인증 이미지를 생성하는 웹 애플리케이션입니다.

## 기능

- ⏱️ **독서 타이머**: 독서 시작 시간부터 실시간으로 경과 시간 표시
- 📸 **사진 촬영**: 독서 완료 시 웹캠으로 인증 사진 촬영
- 📊 **기록 표시**: 시작 시간, 완료 시간, 독서 시간 자동 기록
- 🎨 **인증 이미지 생성**: 모든 정보가 포함된 인증 이미지 자동 생성 및 다운로드

## 사용 방법

1. **독서 시작하기** 버튼을 클릭하여 독서를 시작합니다.
2. 독서가 끝나면 **독서 완료하기** 버튼을 클릭합니다.
3. 카메라 권한을 허용하고 인증 사진을 촬영합니다.
4. **공유하기** 버튼을 클릭하여 인증 이미지를 다운로드합니다.

## GitHub Pages 배포 방법

### 1. GitHub 저장소 생성

```bash
# 저장소 초기화
git init
git add .
git commit -m "Initial commit: 독서 타이머 웹앱"
```

### 2. GitHub에 푸시

1. GitHub에서 새 저장소를 생성합니다.
2. 다음 명령어로 푸시합니다:

```bash
git remote add origin https://github.com/사용자명/저장소명.git
git branch -M main
git push -u origin main
```

### 3. GitHub Pages 활성화

1. GitHub 저장소 페이지로 이동합니다.
2. **Settings** 탭을 클릭합니다.
3. 왼쪽 메뉴에서 **Pages**를 선택합니다.
4. **Source**에서 **Deploy from a branch**를 선택합니다.
5. **Branch**에서 `main` 브랜치와 `/ (root)` 폴더를 선택합니다.
6. **Save**를 클릭합니다.

### 4. 배포 확인

몇 분 후 `https://사용자명.github.io/저장소명/` 주소로 접속하면 배포된 웹사이트를 확인할 수 있습니다.

## 기술 스택

- HTML5
- CSS3
- Vanilla JavaScript
- Web APIs: `getUserMedia`, `Canvas API`, `File API`

## 브라우저 호환성

- Chrome/Edge (권장)
- Firefox
- Safari
- 모바일 브라우저 (iOS Safari, Chrome Mobile)

**참고**: 카메라 기능을 사용하려면 HTTPS 환경이 필요합니다. GitHub Pages는 자동으로 HTTPS를 제공하므로 문제없이 사용할 수 있습니다.

## 라이선스

MIT License

