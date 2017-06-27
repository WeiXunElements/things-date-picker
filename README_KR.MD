# things-date-picker
## 이는 프로그램에 설정된 포맷에 따라 날짜를 입력 받아 시간을 표현하는 컴포넌트이다.

  Example:

```html
    <things-date-picker
      label="Date Picker"
      locale="ko"
      read-format="YYYY-MM-DD">
    </things-date-picker>
```

# things-date-from-to
## 이는 From Date와 To Date를 입력 받아 기간을 표현하는 컴포넌트이다.

Example:
```html
    <things-date-from-to
      locale="ko"
      read-format="YYYY-MM-DD">
    </things-date-from-to>
```

# things-date-time-picker
## 이는 프로그램에 설정된 포맷에 따라 Date Time을 입력 받아 시간을 표현하는 컴포넌트이다.

Example:
```html
    <things-date-time-picker
      label="Date Time"
      locale="ko"
      read-format="YYYY-MM-DD hh:mm:ss">
    </things-date-time-picker>
```

# things-time-picker
## 이는 프로그램에 설정된 포맷에 따라 Time을 입력 받아 시간을 표현하는 컴포넌트이다.

Example:
```html
    <things-time-picker
      label="Time Picker"
      read-format="hh:mm:ss">
    </things-time-picker>
```

# things-date-time-range-picker
## 이는 From Datetime과 To Datetime을 입력 받아 기간을 표현하는 컴포넌트이다.

Example:
```html
    <things-date-time-range-picker
      locale="ko"
      name="datetime"
      label="Date"
      read-format="YYYY-MM-DD HH:mm:ss"
      write-format="YYYY-MM-DD HH:mm:ss">
    </things-date-time-range-picker>
```

## 2. 개발
### 2.1 Polymer-CLI 설치

먼저 [Polymer CLI](https://www.npmjs.com/package/polymer-cli)가 설치되어 있는지 확인한다. 다음, `polymer serve`를 실행하여 로컬에서 응용 프로그램을 제공한다.

### 2.2 Application 실행

```
$ polymer serve
```

### 2.3 Application 빌드

```
$ polymer build
```

아래 명령어로 `build/bundled`나 `build/unbundled`에서 서버를 띄울 수 있다.

```
$ polymer serve build/bundled
```

### 2.4 Tests 실행

```
$ polymer test
```

[web-component-tester](https://github.com/Polymer/web-component-tester)에서 설명한 대로, 테스트 설정은 이미 완료되어 있다.
아래 명령어로 테스트를 실행할 수 있다.
```
$ polymer test
```
