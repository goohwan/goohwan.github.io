---
version: "1.0"
name: "Goohwan.net Landing Page Design System"
colors:
  bg: "#0B0F19"
  card-bg: "rgba(255, 255, 255, 0.03)"
  card-border: "rgba(255, 255, 255, 0.08)"
  accent: "#38bdf8"
  accent-hover: "#7dd3fc"
  text-main: "#f8fafc"
  text-muted: "#94a3b8"
  gradient-start: "#3b82f6"
  gradient-end: "#8b5cf6"
typography:
  fontFamily: "'Inter', system-ui, -apple-system, sans-serif"
  h1:
    fontSize: "3rem"
    fontWeight: "800"
  body:
    fontSize: "1rem"
    lineHeight: "1.6"
rounded:
  md: "16px"
  tag: "6px"
spacing:
  container: "1200px"
  gap: "1.5rem"
  card-padding: "1.75rem"
components:
  card:
    backgroundColor: "{colors.card-bg}"
    borderColor: "{colors.card-border}"
    rounded: "{rounded.md}"
    padding: "{spacing.card-padding}"
    backdropFilter: "blur(12px)"
  tag:
    backgroundColor: "rgba(56, 189, 248, 0.1)"
    textColor: "{colors.accent}"
    rounded: "{rounded.tag}"
---

# Goohwan.net Landing Page Premium Design System

## Overview
이 디자인 시스템은 `goohwan.net` 랜딩 페이지의 프리미엄 다크 모드와 글래스모피즘(Glassmorphism) 미학을 정의합니다. Antigravity의 프리미엄 디자인 원칙에 맞춰 설계되었습니다.

## Tokens
- **Colors**: 깊이 있는 어두운 배경(`#0B0F19`)과 반투명한 화이트(`rgba(255, 255, 255, 0.03)`)를 조합하여 깊이감을 부여합니다. 카드에 마우스를 올리면 포인트 컬러(`#38bdf8`)가 은은하게 빛납니다.
- **Typography**: 구글 폰트 `Inter`를 사용하여 현대적이고 세련된 가독성을 제공합니다.
- **Micro-animations**: 카드에 호버할 때 부드러운 떠오름(Lift) 전환, 은은한 글로우 효과, 빗면 빛반사 애니메이션(Shimmer sweep)을 적용하여 동적이고 생동감 있는 사용자 경험을 선사합니다.
- **Background**: 동적으로 천천히 움직이는 방사형 그라데이션 애니메이션(Pulse background)을 통해 입체감을 더합니다.
