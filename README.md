- npx 어쩌고 저쩌고 프로젝트 만든 다음 (공식문서 참고)
- 프로젝트 실행 [참고](https://medium.com/@reachrasmus/react-native-on-macos-13-2-4f8c2f963d6e)

폴더안에 들어가서
bundle install

후에 cd ios
pod install
bundler install

그런다음
npx @react-native-community/cli doctor
이걸로 체크

권한 없을 경우 $ sudo chown -R woojisoo ~/react_native_project

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

$ ruby -v
ruby 3.0.2p107 (2021-07-07 revision 0db68f0233) [x86_64-darwin22]

```

```
$ rbenv versions
  system
  2.7.4
* 3.0.2 (set by /Users/woojisoo/.rbenv/version)
  3.0.6
```

```
$ brew -v
Homebrew 4.1.15
```

```
$ pod --version
1.13.0
```
