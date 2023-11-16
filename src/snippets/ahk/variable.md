Using a variable and if-statement

```ahk
mode := 'default'

!n:: {
  global mode
  if (mode = 'default') {
    mode := 'numpad'
  } else {
    mode := 'default'
  }
}
```