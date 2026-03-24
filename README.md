# KeyFlow

A macOS keyboard utility app. Launch apps, scroll with keyboard, and auto-replace text — all with global hotkeys.

macOS 키보드 유틸리티 앱. 글로벌 단축키로 앱 실행, 키보드 스크롤, 텍스트 자동 대치를 지원합니다.

## Download

[Latest Release](https://github.com/jeje-labs/Keyflow-Release/releases/latest)

## Features

### App Launcher
Launch, switch, or hide apps instantly with hotkeys. Press again to toggle.
- Auto-categorized by app type (Developer Tools, Productivity, etc.)
- Shortcut templates (⌘F1~F12) for quick setup

단축키로 앱을 즉시 실행/전환/숨기기. 카테고리별 자동 분류.

### Keyboard Scroll
Vim-style keyboard scrolling. Works in any app without a mouse.

| Shortcut | Action |
|---|---|
| `⌃J` | Scroll down |
| `⌃K` | Scroll up |
| `⌃D` | Half page down |
| `⌃U` | Half page up |
| `⌃H` | Scroll left |
| `⌃L` | Scroll right |

### Text Expansion
Type a short trigger and it auto-expands into a full phrase. Optimized for customer service workflows.

한글 자모 조합을 입력하면 정형화된 문구로 자동 대치됩니다. CS 업무에 최적화.

**Usage:**
1. Type a trigger (e.g. `ㅎㅂ`)
2. Preview panel appears
3. Press `Tab` or `Enter` to confirm
4. Multiple matches? Press `⌘1`~`⌘9` to select

**Built-in examples:**

| Trigger | Replacement |
|---|---|
| `ㅎㅂ` | 안녕하세요, 고객님. 문의해 주셔서 감사합니다. 무엇을 도와드릴까요? |
| `ㅈㅅ` | 불편을 드려 대단히 죄송합니다, 고객님. 빠르게 확인하여 안내드리겠습니다. |
| `ㅂㅅ` | 주문하신 상품은 현재 배송 준비 중이며, 출고 완료 시 송장번호를 안내드리겠습니다. |
| `ㅎㅂㄹ` | 환불 요청이 접수되었습니다. 영업일 기준 3~5일 이내에 처리 완료됩니다. |
| `ㄱㅅ` | 소중한 시간 내어 문의해 주셔서 감사합니다. 좋은 하루 되세요! |

### Snippet Palette
Press `⌘F11` to open a Spotlight-style search panel. Browse and select from all registered phrases.

## Installation

1. Download `KeyFlow.dmg` from [Releases](https://github.com/jeje-labs/Keyflow-Release/releases/latest)
2. Open DMG → Drag `KeyFlow.app` to Applications
3. Launch the app
4. **Grant Accessibility permission** (System Settings → Privacy & Security → Accessibility → Enable KeyFlow)

> Accessibility permission is required for global hotkeys to work.

## Key Shortcuts

| Shortcut | Action |
|---|---|
| `⌘⇧K` | Open/close KeyFlow Settings |
| `⌘F11` | Open/close Snippet Palette |

All shortcuts are customizable in Settings.

## Backup

Settings → General → **Export/Import** to backup and restore all bindings + text expansions as JSON.

## Requirements

- macOS 14.0+
- Accessibility permission required

## License

Copyright © 2026 jeje-labs. All rights reserved.
