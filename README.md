# CHOIAE QUEST — GitHub Pages 배포

## 1. 저장소 만들기
GitHub에 로그인한 뒤 **New repository**를 선택하고, 저장소 이름을 정해 **Public**으로 생성합니다. 예: `choiae-quest`.

## 2. 파일 올리기
이 배포 폴더 안의 `index.html`과 `README.md`를 저장소 **최상위(root)** 에 업로드하고 커밋합니다. ZIP을 푼 경우에도 두 파일이 저장소 최상위에 오도록 올려 주세요.

## 3. Pages 설정
저장소에서 **Settings → Pages**로 이동합니다. **Build and deployment**에서 Source를 **Deploy from a branch**로 선택하고, Branch는 `main`, 폴더는 `/(root)`로 지정한 뒤 **Save**를 누릅니다.

## 4. 배포 후 접속
Pages 화면에 표시되는 사이트 주소를 엽니다. 보통 `https://깃허브사용자명.github.io/저장소이름/` 형식입니다. 처음 배포는 몇 분 걸릴 수 있습니다.

게임 진행 데이터는 접속한 브라우저의 `localStorage`에 저장됩니다. 사진은 HTML에 포함되지 않고 외부 이미지 주소에서 불러옵니다.