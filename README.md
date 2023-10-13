

- npx 어쩌고 저쩌고 프로젝트 만든 다음 (공식문서 참고)
- 프로젝트 실행 [참고](https://medium.com/@reachrasmus/react-native-on-macos-13-2-4f8c2f963d6e)

### 실행법

클론
```
$ git clone https://github.com/jisooround/RN-TEST.git
```

프로젝트 폴더 안에 들어가서
```
$ bundle install
```

후에 ios 디렉토리에서
```
$ cd ios
$ pod init
$ pod install
$ open $프로젝트이름.xcworkspace
```

그런다음
npx @react-native-community/cli doctor
이걸로 체크

권한 없을 경우 $ sudo chown -R woojisoo ~/react_native_project

```
$ sudo chown -R ${username} ~/${directory 위치}
```

---

### 버전 정보

```
$ node -v
v18.18.0
```

```

$ nvm --version
0.38.0

```

```
// ruby 버전 확인
$ ruby -v
ruby 3.0.2p107 (2021-07-07 revision 0db68f0233) [x86_64-darwin22]

```

```
// 변경 가능한 ruby 버전 확인
$ rbenv versions
  system
  2.7.4
* 3.0.2 (set by /Users/woojisoo/.rbenv/version)
  3.0.6
```

```
// ruby 특정 버전 설치
$ rbenv install 3.0.2

// ruby 버전 설정
$ rbenv global 3.0.2
```

```
$ brew -v
Homebrew 4.1.15
```

```
$ pod --version
1.13.0
```

만일 오류가 발생한다면 ios 디렉토리에 들어가서

- propject.xcworkspace파일 삭제
- [해결 법](https://positiveko-til.vercel.app/til/react-native/error65.html)

- 그 다음 ios 폴더에서 pos init이 안된다면 activesupports 버전 문제일 수 잇음
  [이거 해결법](https://juejin.cn/post/7287914129564680249)

- 그 담 나와서 yarn ios했는데 이런 에러 발생

```
fatal error: 'RCTAppDelegate.h' file not found
```
