# Digital-Clock- Public
2019 | Web development

# HTML, CSS, JS - 디지털 시계 만들기 (시간, 알람, 타이머 기능)

## 프로젝트 개요

이 프로젝트는 HTML, CSS, 그리고 자바스크립트를 사용하여 디지털 시계를 제작하는 것을 목표로 합니다. 이 시계는 시간 표시뿐만 아니라, 알람과 타이머 기능도 함께 구현되어 있습니다.

## 사용된 도구 및 플랫폼

- **Visual Studio Code**: 개발 환경으로 사용
- **Github**: 소스 코드 관리를 위해 사용
- **Netlify**: 프로젝트 배포를 위해 사용

## 완성된 사이트

프로젝트는 Netlify를 통해 배포되었으며, 아래 링크에서 확인할 수 있습니다:
- [완성된 사이트 접속하기](https://neon-elf-202055.netlify.app/)

## 주요 기능

1. **시간 표시**:
   - 실시간으로 시간을 표시하는 디지털 시계.

2. **알람 기능**:
   - 사용자가 특정 시간을 설정하면, 설정된 시간에 알람 소리가 재생됨.

3. **타이머 기능**:
   - 사용자가 원하는 시간을 설정하여 타이머를 시작할 수 있음. 타이머 종료 시 알람 소리가 울림.

4. **UI 기능**:
   - 시계의 색상 변경, 시작 화면, 알람 화면, 타이머 화면 등이 포함되어 있음.

## 결과 화면

### (1) 시작 화면
- 디지털 시계를 통해 실시간 시간 표시.

### (2) 시계 색상 변경 기능
- 사용자 맞춤형 색상 변경 기능 제공.

### (3) 알람 설정 및 알람 소리
- 알람이 울릴 시간을 설정 후, 설정된 시간에 알람 소리가 울림.

### (4) 타이머 설정 및 종료
- 타이머 설정 후, 설정 시간이 끝나면 타이머 종료 알림과 함께 소리가 울림.

## 핵심 코드

```html
<div id="alarm" class="category-container">
    <h4>알람 설정</h4>
    <input type="time" id="alarmTime" class="form-control">
    <button class="btn btn-primary mt-2" onclick="setAlarm()">알람 설정</button>
    <div id="alarmMessage" class="mt-3"></div>
</div>

<div id="timer" class="category-container">
    <h4>타이머 설정</h4>
    <div class="d-flex">
        <input type="number" id="timerHours" class="form-control" placeholder="시" min="0">
        <input type="number" id="timerMinutes" class="form-control" placeholder="분" min="0">
        <input type="number" id="timerSeconds" class="form-control" placeholder="초" min="0">
    </div>
</div>

<audio id="alarmSound" src="./alarm.mp3.mp3"></audio> <!-- 알람 소리 파일 -->
```

## 태그

- HTML
- CSS
- 자바스크립트
- Netlify
- Github
- 디지털 시계
- 알람 기능
- 타이머 기능
