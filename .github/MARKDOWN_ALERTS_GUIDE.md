# GitHub Markdown Alerts 가이드

GitHub의 Markdown에서는 독자의 주의를 끌기 위한 **5가지 알림(Alert) 요소**를 지원합니다.  
`>` 블록 인용 문법에 `[!TYPE]` 키워드를 조합하여 사용합니다.

---

## 기본 문법

```markdown
> [!TYPE]
> 내용을 여기에 작성합니다.
```

---

## 알림 유형별 사용법

### 1. NOTE

> [!NOTE]
> 독자가 알아두면 유용한 **추가 정보**를 제공할 때 사용합니다.

```markdown
> [!NOTE]
> 독자가 알아두면 유용한 추가 정보를 제공할 때 사용합니다.
```

---

### 2. TIP

> [!TIP]
> 더 나은 방법이나 **유용한 팁**을 안내할 때 사용합니다.

```markdown
> [!TIP]
> 더 나은 방법이나 유용한 팁을 안내할 때 사용합니다.
```

---

### 3. IMPORTANT

> [!IMPORTANT]
> 목표를 달성하는 데 **필수적인 정보**를 강조할 때 사용합니다.

```markdown
> [!IMPORTANT]
> 목표를 달성하는 데 필수적인 정보를 강조할 때 사용합니다.
```

---

### 4. WARNING

> [!WARNING]
> 잠재적인 **위험 또는 문제**에 대해 주의를 요구할 때 사용합니다.

```markdown
> [!WARNING]
> 잠재적인 위험 또는 문제에 대해 주의를 요구할 때 사용합니다.
```

---

### 5. CAUTION

> [!CAUTION]
> 특정 행동으로 인해 발생할 수 있는 **부정적인 결과**를 경고할 때 사용합니다.

```markdown
> [!CAUTION]
> 특정 행동으로 인해 발생할 수 있는 부정적인 결과를 경고할 때 사용합니다.
```

---

## 유형 비교 요약

| 유형          | 색상(GitHub) | 사용 목적                                      |
|---------------|-------------|------------------------------------------------|
| `[!NOTE]`     | 파란색       | 추가 정보, 참고 사항 전달                        |
| `[!TIP]`      | 초록색       | 유용한 팁, 권장 방법 안내                        |
| `[!IMPORTANT]`| 보라색       | 놓치면 안 되는 중요 정보 강조                    |
| `[!WARNING]`  | 주황색       | 주의가 필요한 잠재적 위험 경고                   |
| `[!CAUTION]`  | 빨간색       | 부정적 결과를 초래할 수 있는 행동 경고           |

---

## 여러 줄 작성

알림 블록 내에 여러 줄을 작성할 수 있습니다.

```markdown
> [!NOTE]
> 첫 번째 줄입니다.
> 두 번째 줄입니다.
> 세 번째 줄입니다.
```

---

## 지원 환경

GitHub Markdown alerts는 다음 환경에서 렌더링됩니다.

- GitHub.com (Issues, Pull Requests, Discussions, README 등)
- GitHub Docs

> [!WARNING]
> 일반 Markdown 렌더러(예: VS Code 기본 미리보기, 일부 외부 도구)에서는 지원되지 않을 수 있습니다.

---

## 참고 링크

- [GitHub Docs - Alerts](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#alerts)
