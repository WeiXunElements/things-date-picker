# things-date-picker
## It is a component that displays the time by receiving the date according to the format set in the program.

  Example:

```html
    <things-date-picker
      label="Date Picker"
      locale="ko"
      read-format="YYYY-MM-DD">
    </things-date-picker>
```

# things-date-from-to
## It is a component that displays the period by receiving From Date and To Date.

Example:
```html
    <things-date-from-to
      locale="ko"
      read-format="YYYY-MM-DD">
    </things-date-from-to>
```

# things-date-time-picker
## It is a component that displays the time by receiving Date Time according to the format set in the program.

Example:
```html
    <things-date-time-picker
      label="Date Time"
      locale="ko"
      read-format="YYYY-MM-DD hh:mm:ss">
    </things-date-time-picker>
```

# things-time-picker
## It is a component that displays the time by receiving Time according to the format set in the program.

Example:
```html
    <things-time-picker
      label="Time Picker"
      read-format="hh:mm:ss">
    </things-time-picker>
```

# things-date-time-range-picker
## It is a component that displays the period by receiving From Datetime and To Datetime.

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

## 2. Development
### 2.1 Install Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### 2.2 Run Application

```
$ polymer serve
```

### 2.3 Build Application

```
$ polymer build
```

You can launch the server from `build/bundled` or `build/unbundled` with the following command:

```
$ polymer serve build/bundled
```

### 2.4 Run Tests

```
$ polymer test
```

The test has been set up as described in [web-component-tester](https://github.com/Polymer/web-component-tester).
You can run the test with the following command.
```
$ polymer test
```
