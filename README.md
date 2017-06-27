# things-date-picker
## 프로그램에 설정한 포멧에 따라 날짜를 입력받아 시간을 표현하는 컴포넌트

  Example:

```html
    <things-date-picker
      label="Date Picker"
      locale="ko"
      read-format="YYYY-MM-DD">
    </things-date-picker>
```

# things-date-from-to
## From Date와 To Date를 입력받아 기간을 표현하는 컴퍼넌트

Example:
```html
    <things-date-from-to
      locale="ko"
      read-format="YYYY-MM-DD">
    </things-date-from-to>
```

# things-date-time-picker
## 프로그램에 설정한 포멧에 따라 Date Time을 입력받아 시간을 표현하는 컴포넌트

Example:
```html
    <things-date-time-picker
      label="Date Time"
      locale="ko"
      read-format="YYYY-MM-DD hh:mm:ss">
    </things-date-time-picker>
```

# things-time-picker
## 프로그램에 설정한 포멧에 따라 Time을 입력받아 시간을 표현하는 컴포넌트

Example:
```html
    <things-time-picker
      label="Time Picker"
      read-format="hh:mm:ss">
    </things-time-picker>
```

# things-date-time-range-picker
## From Datetime과 To Datetime을 입력받아 기간을 표현하는 컴퍼넌트

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

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### 2.2 Application 수행

```
$ polymer serve
```

### 2.3 Application 빌드

```
$ polymer build
```

아래 명령어로 ` build/bundled`나 ` build/unbundled`에서 서버를 띄울수 있다.

```
$ polymer serve build/bundled
```

### 2.3 Running Tests

```
$ polymer test
```

테스트는 [web-component-tester](https://github.com/Polymer/web-component-tester)에서 설명한데로 설정완료됨.
아래 명령어로 테스트를 수행할 수 있다.
```
$ polymer test
```
`<things-date-from-to>` From Date와 To Date를 입력받아 기간을 표현하는 컴퍼넌트
