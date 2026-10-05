# invitation to mj's birthday party

민재님을 위한 픽셀 생일 초대장. 검정 터미널 화면, 한글 픽셀 폰트, 타이핑 애니메이션, 정답에 따른 대화 진행, 컨페티를 포함합니다.

별도의 설치나 빌드가 필요 없는 HTML/CSS/JavaScript 웹앱입니다.

## GitHub Pages

저장소 Settings → Pages → Source에서 **GitHub Actions**를 선택하세요. main에 push하면 포함된 배포 워크플로가 웹앱을 배포합니다.

## Vercel

Vercel에서 이 저장소를 Import하고 Framework Preset을 Other로 선택하세요. 빌드 명령은 비워두고 Output Directory는 `.`로 설정하면 됩니다. 같은 설정이 vercel.json에 포함되어 있습니다.

## 편집

`index.html`의 `stages` 배열에서 대화와 선택지를 수정할 수 있습니다. 숫자 정답은 `password` 함수에 있습니다.

폰트: Galmuri (SIL Open Font License), jsDelivr에서 로드. 편지봉투: 생성한 픽셀 이미지.

비밀번호 입력은 초대장의 퀴즈 연출이며 모든 정답이 공개 소스에 들어 있습니다.
