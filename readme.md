  배포 URL: https://ratm01.github.io/adhoc/

  다음에 IPA/APK 업로드할 때 할 일

  1. ios/app.ipa, android/app.apk 파일을 각 폴더에 넣기 (LFS로 자동 처리됨)
  2. ios/manifest.plist에서 실제 값으로 수정:
    - bundle-identifier: 실제 번들 ID
    - bundle-version: 버전 문자열
    - title: 앱 이름
  3. index.html에서 버전, 빌드 번호, 날짜 업데이트
  4. git add . && git commit && git push
