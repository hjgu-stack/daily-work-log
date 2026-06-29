# GitHub Pages 배포 방법

이 폴더의 파일을 GitHub 저장소 루트에 업로드하면 GitHub Pages로 배포할 수 있습니다.

## 포함 파일

- `index.html`: 사이트 첫 화면 파일
- `worklog-logo.png`: 업무일지 로고 PNG
- `.nojekyll`: GitHub Pages가 정적 파일을 그대로 배포하도록 하는 파일

## 배포 순서

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더 안의 파일 3개를 저장소 루트에 업로드합니다.
3. 저장소의 `Settings > Pages`로 이동합니다.
4. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
5. Branch는 `main`, Folder는 `/ (root)`로 설정합니다.
6. 저장 후 1~3분 기다립니다.

배포 주소 예시:

```text
https://계정명.github.io/저장소명/
```

