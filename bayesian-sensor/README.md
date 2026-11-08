# Bayes Lens — 베이지안 센서

흰색·블루 톤의 단일 HTML 베이지안 판단 시각화 도구입니다.

## 실행

[**index.html**](./index.html)을 다운로드한 뒤 브라우저에서 열면 됩니다. 빌드, 서버, 패키지 설치가 필요하지 않습니다.

- 사전확률(Prior)을 조절하고 증거를 선택하여 사후확률(Posterior)이 바뀌는 모습을 관찰할 수 있습니다.
- 사람·협업 / 게임·사업 / 정보 검증 / 사용자 정의 시나리오가 포함되어 있습니다.
- 증거별 우도와 증거 간 연관성 조정을 지원합니다.
- 판단 기록을 JSON으로 내보낼 수 있습니다.

> **주의:** 기본 확률과 예시는 교육용 가정입니다. 확률 수치를 실제 인물이나 사업에 관한 객관적인 평가로 받아들이지 마세요. 특히 상관된 증거는 독립 증거처럼 중복 계산하지 않도록 주의해야 합니다.

원본: `bayesian-sensor/index.html`

GitHub의 파일 보기 화면에서 **Raw** → **Save As**로 저장하거나 아래 명령으로 내려받을 수 있습니다.

```bash
curl -L "https://raw.githubusercontent.com/MikeShin0822/codex-use/main/bayesian-sensor/index.html" -o bayesian_sensor.html
```

## GitHub Pages에서 웹사이트로 보기

이 폴더는 빌드 과정이 필요 없는 정적 HTML입니다. 저장소 관리자가 **한 번만** 아래 설정을 하면 GitHub Pages에서 바로 실행할 수 있습니다.

1. [저장소의 Pages 설정](https://github.com/MikeShin0822/codex-use/settings/pages)을 엽니다.
2. **Build and deployment → Source**를 **Deploy from a branch**로 선택합니다.
3. **Branch**는 `main`, **Folder**는 `/(root)`로 선택한 뒤 **Save**를 누릅니다.
4. 빌드가 완료되면 [Bayes Lens](https://mikeshin0822.github.io/codex-use/bayesian-sensor/) 주소에서 실행할 수 있습니다.

> **상태 안내:** 이 README는 Pages 게시를 위한 안내서입니다. 위 링크는 GitHub Pages 활성화·배포 완료 후의 예상 URL이며, 링크가 열린다는 사실을 확인하기 전까지는 배포 완료로 간주하지 않습니다.

GitHub Pages에서 `/(root)`를 게시 소스로 잡으면 이 저장소 내 다른 폴더도 함께 정적으로 노출될 수 있습니다. 이미 공개된 저장소지만 별도 비공개 자료가 없는지 확인하세요.
