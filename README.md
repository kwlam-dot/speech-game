Speech Revision Game (Website).html
<!DOCTYPE html>
<html lang="en"><head><style id="qw-theme">:root {
  --color-bg: #ede4d0;
  --color-text: #2c2418;
  --color-navbar-bg: #e4dac4;
  --color-bg-chat-view: #f4ecda;
  --color-bg-secondary: #f7efdd;
  --color-bg-tertiary: #e4dac4;
  --color-bg-hover: #dbd0b8;
  --color-surface: #e4dac4;
  --color-surface-hover: #dbd0b8;
  --color-surface-active: #d0c4aa;
  --color-border: #cbbfa5;
  --color-border-light: #ddd3bc;
  --color-border-strong: #b5a78c;
  --color-primary: #7a5030;
  --color-primary-dark: #5e3d24;
  --color-primary-light: #8b5e3c;
  --color-primary-bg: rgba(122, 80, 48, .06);
  --color-primary-hover-border: #5e3d24;
  --color-nav-icon-active: #7a5030;
  --color-nav-hover-border: #7a5030;
  --color-primary-alpha-3: color-mix(in srgb, #7a5030 3%, transparent);
  --color-primary-alpha-5: color-mix(in srgb, #7a5030 5%, transparent);
  --color-primary-alpha-8: color-mix(in srgb, #7a5030 8%, transparent);
  --color-primary-alpha-12: color-mix(in srgb, #7a5030 12%, transparent);
  --color-primary-alpha-15: color-mix(in srgb, #7a5030 15%, transparent);
  --color-primary-alpha-20: color-mix(in srgb, #7a5030 20%, transparent);
  --color-primary-alpha-25: color-mix(in srgb, #7a5030 25%, transparent);
  --color-primary-alpha-30: color-mix(in srgb, #7a5030 30%, transparent);
  --color-primary-alpha-40: color-mix(in srgb, #7a5030 40%, transparent);
  --color-primary-alpha-50: color-mix(in srgb, #7a5030 50%, transparent);
  --color-primary-alpha-60: color-mix(in srgb, #7a5030 60%, transparent);
  --color-primary-subtle: color-mix(in srgb, #7a5030 8%, transparent);
  --color-primary-border: color-mix(in srgb, #7a5030 22%, transparent);
  --color-focus-ring: color-mix(in srgb, #7a5030 35%, transparent);
  --color-sidebar-hover: rgba(90, 70, 45, .06);
  --color-accent: #7a5030;
  --color-accent-foreground: #6b4528;
  --color-accent-dark: #5e3d24;
  --color-accent-light: rgba(122, 80, 48, .06);
  --color-accent-inverse: #f7f0e0;
  --color-link: #6b4528;
  --color-primary-gradient-end: rgba(122, 80, 48, .04);
  --color-primary-bg-solid: #f4ecda;
  --color-user-bubble: #e8dfc8;
  --color-text-secondary: #4a3f32;
  --color-text-tertiary: #8a7e6e;
  --color-text-muted: #918474;
  --color-text-on-primary: #f7f0e0;
  --color-success: #6b8a00;
  --color-success-dark: #4a6000;
  --color-success-light: #eaf0d0;
  --color-success-hover: #5a7500;
  --color-success-bg: #eaedce;
  --color-success-border: #d4daa8;
  --color-success-foreground: #6b8a00;
  --color-success-dark-foreground: #4a6000;
  --color-success-text: #4a6000;
  --color-error: #c43e2a;
  --color-error-dark: #962e1f;
  --color-error-light: #fce4df;
  --color-error-hover: #fce4df;
  --color-error-bg: #f6e8de;
  --color-error-border: #eecfc4;
  --color-error-active-border: #c43e2a;
  --color-error-foreground: #c43e2a;
  --color-error-dark-foreground: #962e1f;
  --color-error-inverse: #f7f0e0;
  --color-error-text: #962e1f;
  --color-warning: #a07800;
  --color-warning-dark: #6e5200;
  --color-warning-light: #f8edc5;
  --color-warning-hover: #8a6800;
  --color-warning-bg: #f9f0da;
  --color-warning-border: #eddcaa;
  --color-warning-foreground: #a07800;
  --color-warning-dark-foreground: #6e5200;
  --color-warning-inverse: #6e5200;
  --color-surface-warning: #f8edc5;
  --color-text-warning: #6e5200;
  --color-info: #4a7fa0;
  --color-info-dark: #35607a;
  --color-info-light: #dce9f0;
  --color-info-hover: #3d6d8a;
  --color-info-bg: #eaecdf;
  --color-info-border: #d4dcc8;
  --color-info-foreground: #4a7fa0;
  --color-info-dark-foreground: #35607a;
  --color-info-inverse: #f7f0e0;
  --color-overlay: rgba(44, 36, 24, .45);
  --color-shadow: rgba(44, 36, 24, .1);
  --color-hover: rgba(44, 36, 24, .04);
  --color-tooltip-bg: #2c2418;
  --color-tooltip-text: #f7f0e0;
  --color-voice-purple: #6c71c4;
  --color-voice-purple-dark: #4a4e99;
  --color-voice-purple-light: #6c71c4;
  --color-voice-red: #c43e2a;
  --color-voice-red-dark: #962e1f;
  --color-voice-amber: #a07800;
  --color-voice-purple-glow: rgba(108, 113, 196, .35);
  --color-voice-red-glow: rgba(196, 62, 42, .35);
  --font-sans: "Amazon Ember", "Helvetica Neue", "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  --font-mono: "SF Mono", "Monaco", "Menlo", "Consolas", monospace;
  --text-2xs: .5625rem;
  --text-xs: .625rem;
  --text-sm: .6875rem;
  --text-base: .75rem;
  --text-md: .8125rem;
  --text-lg: .875rem;
  --text-xl: 1rem;
  --text-2xl: 1.125rem;
  --text-3xl: 1.25rem;
  --text-4xl: 1.5rem;
  --text-5xl: 2rem;
  --radius-sm: 6px;
  --radius-md: 10px;
  --radius-card: 12px;
  --radius-lg: 16px;
  --radius-pill: 8px;
  --shadow-sm: 0 1px 3px rgba(44, 36, 24, .07);
  --shadow-md: 0 4px 14px rgba(44, 36, 24, .11);
  --color-success-bg-solid: #eaf0d0;
  --color-error-bg-solid: #fce4df;
  --color-error-border-solid: #fce4df;
  --color-warning-bg-solid: #f8edc5;
  --color-warning-text: #4a3200;
  --color-info-bg-solid: #dce9f0;
  --color-info-bg-solid-alt: #dce9f0;
  --color-info-text: #35607a;
  --color-info-text-alt: #35607a;
  --color-emerald: #6b8a00;
  --color-teal: #4a7fa0;
  --color-code-bg: #e4dac4;
  --color-code-header-bg: #dbd0b8;
  --color-code-text: #2c2418;
  --color-code-border: #cbbfa5;
  --color-code-muted: #918474;
  --color-inline-code-bg: #e4dac4;
  --color-inline-code-text: #4a3f32;
  --color-inline-code-border: #cbbfa5;
  --color-scrollbar-thumb: #b5a78c;
  --color-scrollbar-track: transparent;
  --color-graph-node-text: #2c2418;
  --color-graph-node-text-dim: #918474;
  --color-graph-edge-default: #b5a78c;
  --color-graph-edge-cross: #cb4b16;
  --color-graph-edge-text: #4a3f32;
  --color-graph-edge-stroke: #f7f0e0;
  --color-graph-highlight-bg: #c43e2a;
  --color-graph-highlight-border: #962e1f;
  --color-graph-search-bg: #a07800;
  --color-graph-search-border: #8a6800;
  --color-graph-focus-border: #c43e2a;
  --color-graph-external-border: #b5a78c;
  --color-graph-cat-file: #4a7fa0;
  --color-graph-cat-folder: #8a7e6e;
  --color-graph-cat-file-aggregate: #35607a;
  --color-graph-cat-class: #6c71c4;
  --color-graph-cat-function: #6b8a00;
  --color-graph-cat-method: #8b5e3c;
  --color-graph-cat-variable: #a07800;
  --color-graph-cat-import: #cb4b16;
  --color-graph-cat-module: #6c71c4;
  --color-graph-cat-concept: #c43e2a;
  --color-graph-cat-person: #b84a7a;
  --color-graph-cat-org: #8b5e3c;
  --color-graph-cat-organization: #8b5e3c;
  --color-graph-cat-product: #6c71c4;
  --color-graph-cat-metric: #b84a7a;
  --color-graph-cat-location: #4a3f32;
  --color-graph-cat-date: #b84a7a;
  --color-graph-cat-code: #4a7fa0;
  --color-graph-cat-doc: #8a7e6e;
  --color-graph-cat-url: #8b5e3c;
  --color-graph-cat-email: #6c71c4;
  --color-graph-cat-unknown: #b5a78c;
  --color-graph-rel-contains: #b5a78c;
  --color-graph-rel-extends: #6c71c4;
  --color-graph-rel-implements: #4a7fa0;
  --color-graph-rel-imports: #cb4b16;
  --color-graph-rel-uses: #6b8a00;
  --color-graph-rel-calls: #6b8a00;
  --color-graph-rel-references: #a07800;
  --color-graph-rel-related-to: #b5a78c;
  --color-graph-rel-works-on: #c43e2a;
  --color-graph-rel-owns: #8b5e3c;
  --color-graph-rel-depends-on: #cb4b16;
  --color-graph-rel-parent-of: #b5a78c;
  --qs-content: #f7efdd;
  --qs-main: #e4dac4;
  --qs-primary-foreground: #2c2418;
  --qs-secondary-foreground: #4a3f32;
  --qs-tertiary-foreground: #918474;
  --qs-placeholder-foreground: #918474;
  --qs-divider: #cbbfa5;
  --qs-default-border: #cbbfa5;
  --qs-neutral-soft: #b5a78c;
  --qs-neutral-gray-50: #e4dac4;
  --qs-tertiary-background: #e4dac4;
  --qs-action-hover: rgba(44, 36, 24, .04);
  --qs-primary-default: #7a5030;
  --qs-primary-dark: #5e3d24;
  --qs-primary-light: rgba(122, 80, 48, .06);
  --qs-success-default: #6b8a00;
  --qs-error-default: #c43e2a;
  --qs-font-sans: "Amazon Ember", "Helvetica Neue", "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  --react-pdf-text-layer: 1;
  --highlight-bg-color: rgba(180, 0, 170, 1);
  --highlight-selected-bg-color: rgba(0, 100, 0, 1);
  --react-pdf-annotation-layer: 1;
  --annotation-unfocused-field-background: url("data:image/svg+xml;charset=UTF-8,<svg width='1px' height='1px' xmlns='http://www.w3.org/2000/svg'><rect width='100%' height='100%' style='fill:rgba(0, 54, 255, 0.13);'/></svg>");
  --input-focus-border-color: Highlight;
  --input-focus-outline: 1px solid Canvas;
  --input-unfocused-border-color: transparent;
  --input-disabled-border-color: transparent;
  --input-hover-border-color: black;
  --link-outline: none;
  color-scheme: light;
}
body { background: var(--color-bg); color: var(--color-text); }
a { color: var(--color-link, var(--color-primary)); }</style>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Speech Structure Revision — S4 English</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>🎤</text></svg>">
<style>
:root {
  --color-bg: #f8f9fa;
  --color-bg-secondary: #f4f5f7;
  --color-text: #172b4d;
  --color-text-secondary: #44546f;
  --color-text-muted: #8993a4;
  --color-border-light: #ebecf0;
  --color-border: #dfe1e6;
  --color-surface: #ffffff;
  --color-primary: #0052CC;
  --color-success: #36b37e;
  --color-error: #de350b;
  --color-warning: #ff991f;
  --font-sans: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  --font-mono: 'SF Mono', Consolas, monospace;
}
* { box-sizing: border-box; }
body { background: var(--color-bg); font-family: var(--font-sans); color: var(--color-text); margin: 0; padding: 24px; min-height: 100vh; }
h1 { text-align: center; margin-bottom: 4px; font-size: 26px; }
.subtitle { text-align: center; color: var(--color-text-muted); margin-bottom: 20px; font-size: 13px; }
.game-container { max-width: 740px; margin: 0 auto; }

/* Difficulty */
.diff-bar { display: flex; justify-content: center; gap: 8px; margin-bottom: 16px; }
.diff-btn { padding: 6px 18px; border-radius: 20px; border: 2px solid var(--color-border-light); background: var(--color-bg-secondary); font-size: 12px; font-weight: 600; cursor: pointer; transition: all 0.15s; }
.diff-btn:hover { border-color: var(--color-primary); }
.diff-btn.active { background: var(--color-primary); color: #fff; border-color: var(--color-primary); }
.diff-btn.easy.active { background: #36b37e; border-color: #36b37e; }
.diff-btn.medium.active { background: #ff991f; border-color: #ff991f; }
.diff-btn.hard.active { background: #de350b; border-color: #de350b; }

/* Leaderboard toggle */
.lb-toggle { display: flex; justify-content: flex-end; margin-bottom: 8px; }
.lb-toggle-btn { background: none; border: none; color: var(--color-primary); font-size: 13px; font-weight: 600; cursor: pointer; display: flex; align-items: center; gap: 6px; padding: 6px 12px; border-radius: 6px; transition: all 0.15s; }
.lb-toggle-btn:hover { background: #e8f4fd; }

/* Leaderboard */
.leaderboard { background: var(--color-surface); border: 1px solid var(--color-border-light); border-radius: 12px; padding: 20px 24px; margin-bottom: 20px; box-shadow: 0 2px 12px rgba(0,0,0,0.04); display: none; }
.leaderboard.show { display: block; }
.lb-title { font-size: 16px; font-weight: 700; margin-bottom: 16px; display: flex; align-items: center; gap: 8px; }
.lb-table { width: 100%; border-collapse: collapse; font-size: 13px; }
.lb-table th { text-align: left; padding: 8px 12px; font-size: 11px; text-transform: uppercase; letter-spacing: 0.04em; color: var(--color-text-muted); border-bottom: 2px solid var(--color-border-light); }
.lb-table td { padding: 10px 12px; border-bottom: 1px solid var(--color-border-light); }
.lb-table tr:last-child td { border-bottom: none; }
.lb-table .rank { font-weight: 700; width: 40px; }
.lb-table .rank-1 { color: #ff991f; }
.lb-table .rank-2 { color: #8993a4; }
.lb-table .rank-3 { color: #cd7f32; }
.lb-table .lb-score { font-family: var(--font-mono); font-weight: 700; color: var(--color-primary); }
.lb-table .lb-diff { font-size: 10px; padding: 2px 8px; border-radius: 10px; font-weight: 600; }
.lb-diff-easy { background: #e3fcef; color: #006644; }
.lb-diff-medium { background: #fff3cd; color: #856404; }
.lb-diff-hard { background: #ffebe6; color: #bf2600; }
.lb-empty { text-align: center; color: var(--color-text-muted); font-style: italic; padding: 20px; }
.lb-clear { background: none; border: 1px solid var(--color-border); color: var(--color-text-secondary); padding: 6px 14px; border-radius: 6px; font-size: 11px; cursor: pointer; margin-top: 12px; transition: all 0.15s; }
.lb-clear:hover { border-color: #de350b; color: #de350b; }

/* Score bar */
.score-bar { display: flex; justify-content: space-between; align-items: center; background: var(--color-bg-secondary); border: 1px solid var(--color-border-light); border-radius: 8px; padding: 12px 20px; margin-bottom: 16px; flex-wrap: wrap; gap: 8px; }
.score-item { display: flex; align-items: center; gap: 6px; font-size: 13px; font-weight: 500; }
.score-val { font-family: var(--font-mono); font-size: 16px; font-weight: 700; }
.lives { display: flex; gap: 3px; }
.lives .heart { color: #de350b; font-size: 16px; transition: all 0.3s; }
.lives .heart.lost { color: var(--color-border-light); transform: scale(0.8); }

/* Timer */
.timer-bar { height: 6px; background: var(--color-border-light); border-radius: 4px; margin-bottom: 16px; overflow: hidden; }
.timer-fill { height: 100%; border-radius: 4px; transition: width 0.1s linear; background: #36b37e; }
.timer-fill.warning { background: #ff991f; }
.timer-fill.danger { background: #de350b; animation: pulse 0.5s infinite; }
@keyframes pulse { 0%,100%{opacity:1} 50%{opacity:0.6} }

/* Combo */
.combo-popup { position: fixed; top: 50%; left: 50%; transform: translate(-50%,-50%) scale(0); font-size: 48px; font-weight: 900; color: var(--color-primary); pointer-events: none; z-index: 999; opacity: 0; transition: all 0.4s ease; text-shadow: 0 2px 12px rgba(0,82,204,0.3); }
.combo-popup.show { transform: translate(-50%,-50%) scale(1); opacity: 1; }
.combo-popup.hide { transform: translate(-50%,-60%) scale(1.2); opacity: 0; }

/* Badges */
.badges-bar { display: flex; gap: 6px; margin-bottom: 16px; flex-wrap: wrap; }
.badge { width: 32px; height: 32px; border-radius: 50%; background: var(--color-border-light); display: flex; align-items: center; justify-content: center; font-size: 14px; opacity: 0.4; transition: all 0.3s; border: 2px solid transparent; }
.badge.earned { opacity: 1; background: #fff3cd; border-color: #ff991f; box-shadow: 0 2px 8px rgba(255,153,31,0.3); }
.badge-tooltip { position: relative; }
.badge-tooltip::after { content: attr(data-tip); position: absolute; bottom: -24px; left: 50%; transform: translateX(-50%); font-size: 9px; background: #172b4d; color: #fff; padding: 2px 6px; border-radius: 3px; white-space: nowrap; opacity: 0; pointer-events: none; transition: opacity 0.2s; }
.badge-tooltip:hover::after { opacity: 1; }

.mode-selector { display: grid; grid-template-columns: repeat(5, 1fr); gap: 8px; margin-bottom: 20px; }
.mode-btn { background: var(--color-bg-secondary); border: 2px solid var(--color-border-light); border-radius: 8px; padding: 12px 6px; text-align: center; cursor: pointer; transition: all 0.15s ease; font-size: 10px; font-weight: 500; position: relative; }
.mode-btn:hover { border-color: var(--color-primary); background: var(--color-surface); }
.mode-btn.active { border-color: var(--color-primary); background: var(--color-surface); box-shadow: 0 2px 8px rgba(0,82,204,0.12); }
.mode-btn i { display: block; font-size: 18px; margin-bottom: 5px; color: var(--color-primary); }
.mode-btn .mode-check { position: absolute; top: 4px; right: 4px; font-size: 10px; color: #36b37e; display: none; }
.mode-btn .mode-check.show { display: block; }

.progress-bar { height: 4px; background: var(--color-border-light); border-radius: 4px; margin-bottom: 20px; overflow: hidden; }
.progress-fill { height: 100%; background: var(--color-primary); border-radius: 4px; transition: width 0.3s ease; }
.question-card { background: var(--color-surface); border: 1px solid var(--color-border-light); border-radius: 12px; padding: 28px; margin-bottom: 20px; box-shadow: 0 2px 12px rgba(0,0,0,0.04); }
.q-label { font-size: 11px; text-transform: uppercase; letter-spacing: 0.05em; color: var(--color-text-muted); margin-bottom: 12px; font-weight: 600; }
.q-text { font-size: 15px; line-height: 1.7; margin-bottom: 20px; }
.options { display: flex; flex-direction: column; gap: 10px; }
.option-btn { background: var(--color-bg-secondary); border: 2px solid var(--color-border-light); border-radius: 8px; padding: 13px 16px; cursor: pointer; transition: all 0.15s ease; font-size: 13px; text-align: left; display: flex; align-items: center; gap: 12px; line-height: 1.5; }
.option-btn:hover:not(.disabled) { border-color: var(--color-primary); background: var(--color-surface); }
.option-btn .letter { width: 26px; height: 26px; border-radius: 50%; background: var(--color-border-light); display: flex; align-items: center; justify-content: center; font-weight: 700; font-size: 12px; color: var(--color-text-secondary); flex-shrink: 0; }
.option-btn.correct { border-color: #36b37e; background: #e3fcef; }
.option-btn.correct .letter { background: #36b37e; color: #fff; }
.option-btn.wrong { border-color: #de350b; background: #ffebe6; }
.option-btn.wrong .letter { background: #de350b; color: #fff; }
.option-btn.disabled { cursor: default; opacity: 0.7; }
.sentence-list { display: flex; flex-direction: column; gap: 8px; }
.sentence-item { background: var(--color-bg-secondary); border: 2px solid var(--color-border-light); border-radius: 8px; padding: 12px 16px; cursor: grab; transition: all 0.15s ease; font-size: 13px; display: flex; align-items: center; gap: 12px; user-select: none; line-height: 1.5; }
.sentence-item:hover { border-color: var(--color-primary); }
.sentence-item .num { width: 24px; height: 24px; border-radius: 50%; background: var(--color-primary); color: #fff; display: flex; align-items: center; justify-content: center; font-size: 11px; font-weight: 700; flex-shrink: 0; }
.sentence-item.dragging { opacity: 0.5; border-style: dashed; }
.feedback { margin-top: 16px; padding: 14px 18px; border-radius: 8px; font-size: 13px; line-height: 1.6; display: none; }
.feedback.show { display: block; }
.feedback.correct { background: #e3fcef; border: 1px solid #abf5d1; color: #006644; }
.feedback.wrong { background: #ffebe6; border: 1px solid #ffbdad; color: #bf2600; }
.next-btn { display: none; margin-top: 16px; background: var(--color-primary); color: #fff; border: none; border-radius: 8px; padding: 12px 28px; font-size: 14px; font-weight: 600; cursor: pointer; transition: all 0.15s ease; }
.next-btn:hover { opacity: 0.9; transform: translateY(-1px); }
.next-btn.show { display: inline-flex; align-items: center; gap: 8px; }
.check-btn { background: var(--color-primary); color: #fff; border: none; border-radius: 8px; padding: 12px 28px; font-size: 14px; font-weight: 600; cursor: pointer; margin-top: 16px; transition: all 0.15s ease; }
.check-btn:hover { opacity: 0.9; }

/* Gap fill */
.gap-sentence { font-size: 15px; line-height: 2.2; margin-bottom: 20px; background: var(--color-bg-secondary); padding: 20px 24px; border-radius: 10px; border: 1px solid var(--color-border-light); }
.gap-blank { display: inline-block; min-width: 130px; border-bottom: 2.5px dashed var(--color-primary); padding: 2px 8px; margin: 0 4px; color: var(--color-primary); font-weight: 600; cursor: pointer; transition: all 0.2s ease; text-align: center; font-size: 12px; }
.gap-blank.filled { background: #e8f4fd; border-radius: 4px; border-bottom: 2.5px solid var(--color-primary); }
.gap-blank.correct-gap { background: #e3fcef; border-color: #36b37e; color: #006644; border-radius: 4px; }
.gap-blank.wrong-gap { background: #ffebe6; border-color: #de350b; color: #bf2600; border-radius: 4px; text-decoration: line-through; }
.word-bank { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 16px; }
.word-chip { background: var(--color-surface); border: 2px solid var(--color-border); border-radius: 20px; padding: 8px 14px; font-size: 11px; cursor: pointer; transition: all 0.15s ease; font-weight: 500; user-select: none; }
.word-chip:hover:not(.used) { border-color: var(--color-primary); background: #e8f4fd; transform: translateY(-1px); }
.word-chip.used { opacity: 0.35; cursor: default; border-style: dashed; }
.word-chip.selected { border-color: var(--color-primary); background: #e8f4fd; box-shadow: 0 2px 6px rgba(0,82,204,0.15); }
.gap-instructions { font-size: 12px; color: var(--color-text-muted); margin-bottom: 12px; font-style: italic; }

/* Overlay */
.overlay { display: none; position: fixed; inset: 0; background: rgba(0,0,0,0.6); z-index: 1000; align-items: center; justify-content: center; }
.overlay.show { display: flex; }
.overlay-card { background: var(--color-surface); border-radius: 16px; padding: 40px; text-align: center; max-width: 420px; width: 90%; box-shadow: 0 20px 60px rgba(0,0,0,0.3); }
.overlay-card h2 { margin: 0 0 8px; font-size: 24px; }
.overlay-card p { color: var(--color-text-secondary); margin: 0 0 20px; font-size: 14px; line-height: 1.6; }
.overlay-card .stat-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; margin-bottom: 20px; }
.overlay-card .stat-box { background: var(--color-bg-secondary); border-radius: 8px; padding: 12px 8px; }
.overlay-card .stat-box .stat-num { font-size: 22px; font-weight: 700; color: var(--color-primary); }
.overlay-card .stat-box .stat-label { font-size: 10px; color: var(--color-text-muted); text-transform: uppercase; margin-top: 2px; }
.name-input { width: 100%; padding: 12px 16px; border: 2px solid var(--color-border); border-radius: 8px; font-size: 15px; margin-bottom: 12px; text-align: center; outline: none; transition: border-color 0.2s; font-family: var(--font-sans); }
.name-input:focus { border-color: var(--color-primary); }
.name-input::placeholder { color: var(--color-text-muted); }
.save-score-btn { background: #36b37e; color: #fff; border: none; border-radius: 8px; padding: 12px 28px; font-size: 14px; font-weight: 600; cursor: pointer; margin-right: 8px; transition: all 0.15s; }
.save-score-btn:hover { opacity: 0.9; }
.save-score-btn:disabled { opacity: 0.5; cursor: default; }
.restart-btn { background: var(--color-primary); color: #fff; border: none; border-radius: 8px; padding: 12px 28px; font-size: 14px; font-weight: 600; cursor: pointer; transition: all 0.15s; }
.restart-btn:hover { opacity: 0.9; }
.btn-row { display: flex; justify-content: center; gap: 8px; flex-wrap: wrap; }

/* Footer */
.footer { text-align: center; margin-top: 32px; padding-top: 20px; border-top: 1px solid var(--color-border-light); font-size: 11px; color: var(--color-text-muted); }

@media (max-width: 600px) {
  .mode-selector { grid-template-columns: repeat(3, 1fr); }
  body { padding: 16px; }
  .question-card { padding: 20px; }
  .score-bar { padding: 10px 14px; }
  .overlay-card { padding: 28px 20px; }
  .gap-sentence { padding: 14px 16px; font-size: 14px; }
}
</style>
</head>
<body>

<h1><i class="fa-solid fa-microphone-lines" style="color: var(--color-primary);"></i> Speech Structure Revision</h1>
<p class="subtitle">S4 Term 3 — Preservation and Promotion of Chinese Cultural Heritage</p>

<div class="game-container">
  <div class="diff-bar">
    <div class="diff-btn easy active" onclick="setDifficulty('easy')"><i class="fa-solid fa-seedling"></i> Easy</div>
    <div class="diff-btn medium" onclick="setDifficulty('medium')"><i class="fa-solid fa-fire"></i> Medium</div>
    <div class="diff-btn hard" onclick="setDifficulty('hard')"><i class="fa-solid fa-skull"></i> Hard</div>
  </div>

  <div class="lb-toggle">
    <button class="lb-toggle-btn" onclick="toggleLeaderboard()"><i class="fa-solid fa-ranking-star"></i> Leaderboard</button>
  </div>

  <div class="leaderboard" id="leaderboard"></div>

  <div class="badges-bar" id="badges-bar">
    <div class="badge badge-tooltip" id="badge-intro" data-tip="Introduction Master"><i class="fa-solid fa-hand-sparkles"></i></div>
    <div class="badge badge-tooltip" id="badge-tree" data-tip="TREE Expert"><i class="fa-solid fa-tree"></i></div>
    <div class="badge badge-tooltip" id="badge-gapfill" data-tip="Gap Fill Pro"><i class="fa-solid fa-pen-to-square"></i></div>
    <div class="badge badge-tooltip" id="badge-suggest" data-tip="Suggestion Star"><i class="fa-solid fa-lightbulb"></i></div>
    <div class="badge badge-tooltip" id="badge-ordering" data-tip="Structure Genius"><i class="fa-solid fa-arrow-down-short-wide"></i></div>
    <div class="badge badge-tooltip" id="badge-streak5" data-tip="5 Streak!"><i class="fa-solid fa-fire"></i></div>
    <div class="badge badge-tooltip" id="badge-perfect" data-tip="Perfect Round"><i class="fa-solid fa-crown"></i></div>
  </div>

  <div class="score-bar">
    <div class="score-item"><i class="fa-solid fa-star" style="color: #ff991f;"></i> <span class="score-val" id="score">0</span></div>
    <div class="score-item"><i class="fa-solid fa-fire" style="color: #de350b;"></i> <span class="score-val" id="streak">0</span></div>
    <div class="score-item"><span id="progress-text">0/0</span></div>
    <div class="score-item"><div class="lives" id="lives"><i class="fa-solid fa-heart heart"></i><i class="fa-solid fa-heart heart"></i><i class="fa-solid fa-heart heart"></i></div></div>
  </div>

  <div class="timer-bar"><div class="timer-fill" id="timer-fill" style="width:100%"></div></div>

  <div class="mode-selector">
    <div class="mode-btn active" onclick="switchMode('intro')"><i class="fa-solid fa-hand-sparkles"></i>Introduction<span class="mode-check" id="check-intro"><i class="fa-solid fa-check-circle"></i></span></div>
    <div class="mode-btn" onclick="switchMode('tree')"><i class="fa-solid fa-tree"></i>TREE Model<span class="mode-check" id="check-tree"><i class="fa-solid fa-check-circle"></i></span></div>
    <div class="mode-btn" onclick="switchMode('gapfill')"><i class="fa-solid fa-pen-to-square"></i>Gap Fill<span class="mode-check" id="check-gapfill"><i class="fa-solid fa-check-circle"></i></span></div>
    <div class="mode-btn" onclick="switchMode('suggest')"><i class="fa-solid fa-lightbulb"></i>Suggestions<span class="mode-check" id="check-suggest"><i class="fa-solid fa-check-circle"></i></span></div>
    <div class="mode-btn" onclick="switchMode('ordering')"><i class="fa-solid fa-arrow-down-short-wide"></i>Full Structure<span class="mode-check" id="check-ordering"><i class="fa-solid fa-check-circle"></i></span></div>
  </div>

  <div class="progress-bar"><div class="progress-fill" id="progress-fill"></div></div>
  <div class="question-card" id="question-area"></div>
</div>

<div class="combo-popup" id="combo-popup"></div>

<div class="overlay" id="overlay">
  <div class="overlay-card">
    <div id="overlay-icon" style="font-size:52px;margin-bottom:12px;">🏆</div>
    <h2 id="overlay-title">Game Over!</h2>
    <p id="overlay-msg">Great effort! Enter your name to save your score.</p>
    <div class="stat-grid">
      <div class="stat-box"><div class="stat-num" id="final-score">0</div><div class="stat-label">Score</div></div>
      <div class="stat-box"><div class="stat-num" id="final-streak">0</div><div class="stat-label">Best Streak</div></div>
      <div class="stat-box"><div class="stat-num" id="final-correct">0</div><div class="stat-label">Correct</div></div>
    </div>
    <input type="text" class="name-input" id="player-name" placeholder="Enter your name (e.g. 4A Peter)" maxlength="20">
    <div class="btn-row">
      <button class="save-score-btn" id="save-btn" onclick="saveScore()"><i class="fa-solid fa-trophy"></i> Save Score</button>
      <button class="restart-btn" onclick="restartGame()"><i class="fa-solid fa-redo"></i> Play Again</button>
    </div>
  </div>
</div>

<div class="footer">
  S4 English Language — Term 3 Writing: Speech Structure<br>
  Hong Kong Teachers' Association Lee Heng Kwei Secondary School
</div>

<script>
// ===== QUESTIONS =====
const questions = {
  intro: [
    { text: 'What is the FIRST thing you should do in your speech introduction?', options: ['Ask a rhetorical question', 'Greet the audience and introduce yourself', 'State the topic directly', 'Give a statistic'], answer: 1, explanation: 'Begin with: "Good morning, Principal, teachers, and fellow students. I am [Name], the [Position]."' },
    { text: 'After greeting and introducing yourself, what comes NEXT?', options: ['State the benefits', 'Give a call to action', 'Use a rhetorical question to introduce the topic', 'Give suggestions'], answer: 2, explanation: 'Use a <b>rhetorical question</b>: "Do you know that [topic] is more than just [common perception]?"' },
    { text: 'What phrase introduces the topic after the rhetorical question?', options: ['"I want to discuss..."', '"Today, it is my great honor to talk about [topic], a unique and valuable part of our cultural heritage."', '"Let me begin by saying..."', '"The purpose of my speech is..."'], answer: 1, explanation: '"<b>Today, it is my great honor to talk about [topic], a unique and valuable part of our cultural heritage.</b>"' },
    { text: 'Which is the correct order for the INTRODUCTION?', options: ['Rhetorical question → Greeting → Topic', 'Greeting → Self-introduction → Rhetorical question → Topic introduction', 'Topic → Greeting → Rhetorical question', 'Self-introduction → Topic → Rhetorical question'], answer: 1, explanation: '<b>Greeting → Self-introduction → Rhetorical question → Topic introduction</b>.' },
    { text: 'Who is the target audience for this speech?', options: ['Parents only', 'Friends only', 'Principal, teachers, and fellow students', 'The general public'], answer: 2, explanation: 'Morning assembly: "Principal, teachers, and fellow students."' },
    { text: 'Which is CORRECT for promoting Go? (Speaker: Gigi, Student Event Organizer)', options: ['Hi everyone! I\'m Gigi. Let me talk about Go.', 'Good morning, Principal, teachers, and fellow students. I am Gigi, the Student Event Organizer. Do you know that Go is more than just a board game? Today, it is my great honor to talk about learning Go, a unique and valuable part of our cultural heritage.', 'Good morning. Today I will talk about Go.', 'Dear all, Go is an ancient game.'], answer: 1, explanation: '<b>Greeting → Name + Position → Rhetorical Q → Honor phrase + topic</b>.' },
    { text: 'What TONE should the speech use?', options: ['Informal', 'Formal', 'Humorous', 'Angry'], answer: 1, explanation: 'Morning assembly = <b>formal</b> tone.' },
  ],
  tree: [
    { text: 'What does TREE stand for?', options: ['Topic, Reason, Example, End', 'Think, Read, Explain, Evaluate', 'Thesis, Research, Evidence, Elaboration', 'Topic, Result, Effect, Ending'], answer: 0, explanation: '<b>T</b>opic → <b>R</b>eason → <b>E</b>xample/Evidence → <b>E</b>nd' },
    { text: 'Level 2 opener for FIRST body paragraph?', options: ['"To begin with, it is good."', '"First of all, one major benefit is that learning [topic] helps us..."', '"The first reason is..."', '"Let me start..."'], answer: 1, explanation: '"<b>First of all, one major benefit is that</b> learning [topic] helps us..."' },
    { text: 'Level 2 opener for SECOND body paragraph?', options: ['"Next, another reason..."', '"Secondly, another key benefit is that learning [topic] helps us..."', '"Also, we can see..."', '"The second point..."'], answer: 1, explanation: '"<b>Secondly, another key benefit is that</b> learning [topic] helps us..."' },
    { text: 'Level 2 opener for THIRD body paragraph?', options: ['"Thirdly, a further important benefit is that learning [topic] helps us..."', '"Third, it is also true..."', '"Furthermore, we should..."', '"In addition..."'], answer: 0, explanation: '"<b>Thirdly, a further important benefit is that</b> learning [topic] helps us..."' },
    { text: 'In TREE, what comes AFTER Topic (T)?', options: ['Example', 'Conclusion', 'Reason — "This is because..."', 'Rhetorical question'], answer: 2, explanation: '<b>Reason</b>: "This is because..."' },
    { text: 'Which introduces a REAL-LIFE EXAMPLE?', options: ['"This is because..."', '"For example,..." / "For instance,..."', '"Therefore,..."', '"As a result,..."'], answer: 1, explanation: '"<b>For example,</b>" or "<b>For instance,</b>"' },
    { text: 'Which introduces STATISTICAL evidence?', options: ['"For example,..."', '"In my opinion,..."', '"As we all know,..." / "Studies show that..."', '"This is because..."'], answer: 2, explanation: '"<b>As we all know,...</b>" = factual. "<b>Studies show that...</b>" = statistical.' },
    { text: 'What is the LAST part of TREE?', options: ['"For example,..."', '"This is because..."', '"Therefore,..." / "As a result,..."', '"In addition,..."'], answer: 2, explanation: '"<b>Therefore,...</b>" or "<b>As a result,...</b>"' },
    { text: 'Correct order of TREE?', options: ['R → T → E → E', 'T → R → E → E', 'E → T → R → E', 'T → E → E → R'], answer: 1, explanation: 'T → R → E → E' },
  ],
  gapfill: [
    { instruction: 'Fill in the INTRODUCTION:', template: ['Good morning, ', '__1__', ', teachers, and fellow students. I am Alice, the ', '__2__', '. Do you know that Kung Fu is ', '__3__', '? Today, it is my ', '__4__', ' to talk about Chinese Kung Fu, a unique and valuable part of our cultural heritage.'], blanks: { '__1__': 'Principal', '__2__': 'chairperson of the Students\' Union', '__3__': 'more than just fighting', '__4__': 'great honor' }, wordBank: ['Principal', 'chairperson of the Students\' Union', 'more than just fighting', 'great honor', 'Headmaster', 'class monitor', 'very popular', 'big pleasure'] },
    { instruction: 'Fill in the TREE body paragraph:', template: ['First of all, ', '__1__', ' learning Chinese Kung Fu helps us preserve important cultural heritage for future generations. ', '__2__', ' we keep these old traditions alive by practicing them. ', '__3__', ', when young people practice Kung Fu in a park, they are showing a living history. ', '__4__', ', everyone who learns Kung Fu plays an important role in protecting our history.'], blanks: { '__1__': 'one major benefit is that', '__2__': 'This is because', '__3__': 'For example', '__4__': 'Therefore' }, wordBank: ['one major benefit is that', 'This is because', 'For example', 'Therefore', 'another key benefit is that', 'However', 'In addition', 'As a result'] },
    { instruction: 'Fill in the SECOND body paragraph:', template: ['Secondly, ', '__1__', ' learning Chinese Kung Fu helps us greatly improve our physical health. ', '__2__', ' the daily training helps us become stronger and more flexible. ', '__3__', ', practicing the horse stance can build muscle power. ', '__4__', ', practicing Kung Fu regularly is a wonderful way to keep fit.'], blanks: { '__1__': 'another key benefit is that', '__2__': 'This is because', '__3__': 'As we all know', '__4__': 'Therefore' }, wordBank: ['another key benefit is that', 'This is because', 'As we all know', 'Therefore', 'one major benefit is that', 'However', 'For example', 'In conclusion'] },
    { instruction: 'Fill in the THIRD paragraph (statistical evidence):', template: ['Thirdly, ', '__1__', ' learning Kung Fu helps us develop strong self-discipline. ', '__2__', ' the training requires students to practice every day. ', '__3__', ' teenagers who learn Kung Fu can focus 40% longer. ', '__4__', ', this strong focus will help them succeed.'], blanks: { '__1__': 'a further important benefit is that', '__2__': 'This is because', '__3__': 'Studies show that', '__4__': 'As a result' }, wordBank: ['a further important benefit is that', 'This is because', 'Studies show that', 'As a result', 'one major benefit is that', 'However', 'For example', 'Therefore'] },
    { instruction: 'Fill in the SUGGESTIONS:', template: ['To attract more young people, we can ', '__1__', ' after school. We can invite ', '__2__', ' to teach us basic movements. Also, we can watch Kung Fu movies to show how ', '__3__', ' it is. I believe these will ', '__4__', '.'], blanks: { '__1__': 'organize a Kung Fu workshop', '__2__': 'a professional expert', '__3__': 'cool and powerful', '__4__': 'spark our interest' }, wordBank: ['organize a Kung Fu workshop', 'a professional expert', 'cool and powerful', 'spark our interest', 'do homework', 'a famous actor', 'difficult and boring', 'waste time'] },
    { instruction: 'Fill in the CONCLUSION:', template: ['In conclusion, learning Chinese Kung Fu is ', '__1__', ' to students. It plays a vital role in keeping us healthy and our heritage alive. So, ', '__2__', '? Let\'s step out of the classrooms, ', '__3__', ' together. ', '__4__', '.'], blanks: { '__1__': 'truly valuable', '__2__': 'why not start this exciting journey today', '__3__': 'join us and learn Chinese Kung Fu', '__4__': 'Thank you' }, wordBank: ['truly valuable', 'why not start this exciting journey today', 'join us and learn Chinese Kung Fu', 'Thank you', 'quite fun', 'what do you think', 'forget about studying', 'Goodbye'] },
    { instruction: 'Fill in a CALLIGRAPHY introduction:', template: ['Good morning, Principal, teachers, and fellow students. I am Ivan Chan, the ', '__1__', '. Do you know that calligraphy is far more than ', '__2__', '? Today, it is my great honor to talk about learning ', '__3__', ', a unique and valuable part of our ', '__4__', '.'], blanks: { '__1__': 'School Culture Ambassador', '__2__': 'having good handwriting', '__3__': 'calligraphy', '__4__': 'cultural heritage' }, wordBank: ['School Culture Ambassador', 'having good handwriting', 'calligraphy', 'cultural heritage', 'class monitor', 'being artistic', 'painting', 'school tradition'] },
  ],
  suggest: [
    { text: 'Purpose of the suggestions section?', options: ['Give another benefit', 'Suggest ways to attract more young people', 'Summarize benefits', 'Ask a question'], answer: 1, explanation: 'Suggest <b>ways to attract more young people</b>.' },
    { text: 'What phrase STARTS the suggestions?', options: ['"In conclusion,..."', '"To attract more young people, we can..."', '"Therefore,..."', '"First of all,..."'], answer: 1, explanation: '"<b>To attract more young people,</b> we can..."' },
    { text: 'Which phrase makes things more engaging?', options: ['"We have to..."', '"To make it more engaging,..."', '"Students must..."', '"It is compulsory..."'], answer: 1, explanation: '"<b>To make it more engaging,</b>"' },
    { text: 'What adds another suggestion formally?', options: ['"Also, like..."', '"Furthermore, we could..."', '"And then,..."', '"Maybe..."'], answer: 1, explanation: '"<b>Furthermore, we could...</b>"' },
    { text: 'How should the CONCLUSION begin?', options: ['"That\'s all."', '"In conclusion, learning [topic] is truly valuable to students."', '"Finally, I hope you learned."', '"Thank you."'], answer: 1, explanation: '"<b>In conclusion, learning [topic] is truly valuable to students.</b>"' },
    { text: 'The conclusion MUST end with?', options: ['A joke', 'Long summary', 'A call to action + Thank you', 'A new benefit'], answer: 2, explanation: '<b>Call to action</b>: "So, why not start...? Let\'s [action]. Thank you."' },
    { text: 'Correct CONCLUSION pattern?', options: ['"In conclusion...truly valuable...vital role...why not start...Let\'s [action]. Thank you."', '"To sum up, I talked about benefits. Goodbye."', '"In conclusion, thank you."', '"Finally, I hope you try."'], answer: 0, explanation: 'Full: <b>In conclusion → truly valuable → vital role → call to action → Thank you</b>' },
  ],
  ordering: [
    { instruction: 'Arrange the FULL SPEECH structure:', sentences: ['Suggestions: Ways to attract young people', 'Introduction: Greeting → Self-intro → Rhetorical Q → Topic', 'Body 1: First benefit (TREE)', 'Conclusion: Summary + Call to action + Thank you', 'Body 2: Second benefit (TREE)', 'Body 3: Third benefit (TREE)'], correctOrder: [1, 2, 4, 5, 0, 3] },
    { instruction: 'Arrange the INTRODUCTION:', sentences: ['Do you know that Chinese Chess is more than just a board game?', 'Today, it is my great honor to talk about learning Chinese Chess, a unique and valuable part of our cultural heritage.', 'Good morning, Principal, teachers, and fellow students.', 'I am Peter, the chairperson of the Students\' Union.'], correctOrder: [2, 3, 0, 1] },
    { instruction: 'Arrange this TREE paragraph:', sentences: ['Therefore, everyone who learns calligraphy protects our Chinese history.', 'First of all, one major benefit is that learning calligraphy helps us preserve cultural heritage.', 'For example, when young people write Fai Chun during CNY, they show living history.', 'This is because we keep traditions alive by writing with brush and ink.'], correctOrder: [1, 3, 2, 0] },
    { instruction: 'Arrange the CONCLUSION:', sentences: ['Thank you.', 'In conclusion, learning Chinese Kung Fu is truly valuable to students.', 'So, why not start this exciting journey today? Let\'s join us and learn together.', 'It plays a vital role in keeping us healthy and our heritage alive.'], correctOrder: [1, 3, 2, 0] },
    { instruction: 'Arrange the SUGGESTIONS:', sentences: ['I believe these activities will spark our interest.', 'To attract more young people, we can organize a workshop after school.', 'Also, we can watch exciting movies during lunchtime.', 'We can invite a professional expert to teach us.'], correctOrder: [1, 3, 2, 0] },
  ]
};

// ===== GAME STATE =====
let currentMode = 'intro', currentQ = 0, score = 0, streak = 0, bestStreak = 0;
let lives = 3, answered = false, selectedChip = null, gapState = {};
let difficulty = 'easy', timerInterval = null, timeLeft = 100;
let totalCorrect = 0, roundCorrect = 0, completedModes = new Set();
const timerDurations = { easy: 0, medium: 20000, hard: 12000 };
const LB_KEY = 'speech_revision_leaderboard_v2';

// ===== LEADERBOARD =====
function getLeaderboard() { try { return JSON.parse(localStorage.getItem(LB_KEY)) || []; } catch(e) { return []; } }
function saveLeaderboard(lb) { localStorage.setItem(LB_KEY, JSON.stringify(lb)); }
function toggleLeaderboard() { const el = document.getElementById('leaderboard'); el.classList.toggle('show'); if (el.classList.contains('show')) renderLeaderboard(); }
function renderLeaderboard() {
  const lb = getLeaderboard(), el = document.getElementById('leaderboard');
  if (lb.length === 0) { el.innerHTML = `<div class="lb-title"><i class="fa-solid fa-ranking-star" style="color:#ff991f;"></i> Leaderboard</div><div class="lb-empty">No scores yet. Be the first to play!</div>`; return; }
  const medals = ['🥇','🥈','🥉'];
  let rows = lb.slice(0, 10).map((entry, i) => {
    const rankClass = i < 3 ? `rank-${i+1}` : '';
    const medal = i < 3 ? medals[i] : (i+1);
    const diffClass = `lb-diff-${entry.difficulty || 'easy'}`;
    const date = entry.date ? new Date(entry.date).toLocaleDateString() : '';
    return `<tr><td class="rank ${rankClass}">${medal}</td><td><b>${entry.name}</b></td><td class="lb-score">${entry.score}</td><td><span class="lb-diff ${diffClass}">${(entry.difficulty||'easy').toUpperCase()}</span></td><td style="font-size:11px;color:var(--color-text-muted);">${date}</td></tr>`;
  }).join('');
  el.innerHTML = `<div class="lb-title"><i class="fa-solid fa-ranking-star" style="color:#ff991f;"></i> Leaderboard — Top 10</div><table class="lb-table"><thead><tr><th>#</th><th>Name</th><th>Score</th><th>Diff</th><th>Date</th></tr></thead><tbody>${rows}</tbody></table><button class="lb-clear" onclick="clearLeaderboard()"><i class="fa-solid fa-trash"></i> Clear All</button>`;
}
function clearLeaderboard() { if(confirm('Clear all leaderboard scores?')) { localStorage.removeItem(LB_KEY); renderLeaderboard(); } }
function saveScore() {
  const nameInput = document.getElementById('player-name'), name = nameInput.value.trim();
  if (!name) { nameInput.style.borderColor = '#de350b'; nameInput.placeholder = 'Please enter your name!'; return; }
  const lb = getLeaderboard();
  lb.push({ name, score, difficulty, bestStreak, correct: totalCorrect, date: new Date().toISOString() });
  lb.sort((a, b) => b.score - a.score);
  saveLeaderboard(lb.slice(0, 50));
  document.getElementById('save-btn').disabled = true;
  document.getElementById('save-btn').innerHTML = '<i class="fa-solid fa-check"></i> Saved!';
}

// ===== DIFFICULTY =====
function setDifficulty(diff) { difficulty = diff; document.querySelectorAll('.diff-btn').forEach(b => b.classList.remove('active')); document.querySelector(`.diff-btn.${diff}`).classList.add('active'); restartGame(); }

// ===== TIMER =====
function startTimer() {
  clearInterval(timerInterval);
  const fill = document.getElementById('timer-fill');
  if (timerDurations[difficulty] === 0) { fill.style.width = '100%'; fill.className = 'timer-fill'; return; }
  timeLeft = 100; fill.style.width = '100%'; fill.className = 'timer-fill';
  const interval = 100, decrement = 100 / (timerDurations[difficulty] / interval);
  timerInterval = setInterval(() => {
    if (answered) { clearInterval(timerInterval); return; }
    timeLeft -= decrement;
    if (timeLeft <= 0) { timeLeft = 0; clearInterval(timerInterval); timeUp(); }
    fill.style.width = timeLeft + '%';
    if (timeLeft < 25) fill.className = 'timer-fill danger';
    else if (timeLeft < 50) fill.className = 'timer-fill warning';
    else fill.className = 'timer-fill';
  }, interval);
}
function timeUp() {
  if (answered) return; answered = true; loseLife();
  const fb = document.getElementById('feedback');
  if (fb) { fb.className = 'feedback show wrong'; fb.innerHTML = `<i class="fa-solid fa-clock"></i> <b>Time's up!</b>`; }
  document.getElementById('next-btn').classList.add('show');
  if (currentMode !== 'gapfill' && currentMode !== 'ordering') {
    const q = questions[currentMode][currentQ], opts = document.querySelectorAll('.option-btn');
    opts.forEach(o => o.classList.add('disabled'));
    if (opts[q.answer]) opts[q.answer].classList.add('correct');
    if (fb) fb.innerHTML += ` ${q.explanation}`;
  }
}

// ===== LIVES =====
function loseLife() { streak = 0; document.getElementById('streak').textContent = streak; lives--; updateLives(); if (lives <= 0) gameOver(); }
function updateLives() { document.querySelectorAll('#lives .heart').forEach((h, i) => h.classList.toggle('lost', i >= lives)); }
function gameOver() {
  clearInterval(timerInterval);
  document.getElementById('final-score').textContent = score;
  document.getElementById('final-streak').textContent = bestStreak;
  document.getElementById('final-correct').textContent = totalCorrect;
  document.getElementById('overlay-icon').textContent = score >= 200 ? '🏆' : score >= 100 ? '⭐' : '💪';
  document.getElementById('overlay-title').textContent = score >= 200 ? 'Amazing!' : score >= 100 ? 'Well Done!' : 'Game Over!';
  document.getElementById('overlay-msg').textContent = score >= 200 ? 'Outstanding performance! Save your score!' : score >= 100 ? 'Good job! Keep practicing!' : 'Don\'t give up! Review and try again.';
  document.getElementById('save-btn').disabled = false;
  document.getElementById('save-btn').innerHTML = '<i class="fa-solid fa-trophy"></i> Save Score';
  document.getElementById('player-name').value = '';
  document.getElementById('player-name').style.borderColor = '';
  document.getElementById('overlay').classList.add('show');
}
function restartGame() {
  score = 0; streak = 0; bestStreak = 0; lives = 3; totalCorrect = 0; roundCorrect = 0;
  currentQ = 0; answered = false; completedModes = new Set();
  document.getElementById('score').textContent = 0;
  document.getElementById('streak').textContent = 0;
  document.getElementById('overlay').classList.remove('show');
  updateLives();
  document.querySelectorAll('.badge').forEach(b => b.classList.remove('earned'));
  document.querySelectorAll('.mode-check').forEach(c => c.classList.remove('show'));
  renderQuestion();
}

// ===== COMBOS & BADGES =====
function showCombo(text) { const el = document.getElementById('combo-popup'); el.textContent = text; el.className = 'combo-popup show'; setTimeout(() => el.className = 'combo-popup hide', 800); setTimeout(() => el.className = 'combo-popup', 1200); }
function awardBadge(id) { const b = document.getElementById(id); if (b && !b.classList.contains('earned')) b.classList.add('earned'); }

// ===== MODE =====
function switchMode(mode) {
  currentMode = mode; currentQ = 0; answered = false; roundCorrect = 0; selectedChip = null; gapState = {};
  const modes = ['intro', 'tree', 'gapfill', 'suggest', 'ordering'];
  document.querySelectorAll('.mode-btn').forEach((btn, i) => btn.classList.toggle('active', modes[i] === mode));
  renderQuestion();
}

// ===== RENDER =====
function renderQuestion() {
  clearInterval(timerInterval);
  const qs = questions[currentMode], total = qs.length;
  document.getElementById('progress-text').textContent = `${currentQ + 1}/${total}`;
  document.getElementById('progress-fill').style.width = `${(currentQ / total) * 100}%`;
  if (currentMode === 'ordering') { renderOrdering(qs[currentQ]); startTimer(); return; }
  if (currentMode === 'gapfill') { renderGapFill(qs[currentQ]); startTimer(); return; }
  const q = qs[currentQ], letters = ['A','B','C','D'];
  const modeNames = { intro:'Introduction', tree:'TREE Model', suggest:'Suggestions & Conclusion' };
  const area = document.getElementById('question-area');
  let html = `<div class="q-label">${modeNames[currentMode]} — Q${currentQ+1}/${total}</div><div class="q-text">${q.text}</div><div class="options">`;
  q.options.forEach((opt, i) => { html += `<div class="option-btn" onclick="checkAnswer(${i})"><span class="letter">${letters[i]}</span><span>${opt}</span></div>`; });
  html += `</div><div class="feedback" id="feedback"></div><button class="next-btn" id="next-btn" onclick="nextQuestion()">Next <i class="fa-solid fa-arrow-right"></i></button>`;
  area.innerHTML = html; answered = false; startTimer();
}

function renderGapFill(q) {
  const area = document.getElementById('question-area');
  gapState = {}; selectedChip = null;
  const blankKeys = Object.keys(q.blanks);
  blankKeys.forEach(k => gapState[k] = null);
  let sentenceHtml = '';
  q.template.forEach(part => {
    if (part.startsWith('__') && part.endsWith('__')) sentenceHtml += `<span class="gap-blank" id="gap-${part}" onclick="onBlankClick('${part}')">${blankKeys.indexOf(part)+1}</span>`;
    else sentenceHtml += part;
  });
  let shuffledBank = [...q.wordBank];
  for (let i = shuffledBank.length-1; i > 0; i--) { const j = Math.floor(Math.random()*(i+1)); [shuffledBank[i],shuffledBank[j]] = [shuffledBank[j],shuffledBank[i]]; }
  let html = `<div class="q-label">Gap Fill — Q${currentQ+1}/${questions.gapfill.length}</div><div class="q-text">${q.instruction}</div>`;
  html += `<p class="gap-instructions"><i class="fa-solid fa-info-circle"></i> Click a phrase from the bank, then click the numbered blank to place it.</p><div class="word-bank">`;
  shuffledBank.forEach((word, i) => { html += `<span class="word-chip" id="chip-${i}" onclick="onChipClick(${i},'${word.replace(/'/g,"\\'")}')">${word}</span>`; });
  html += `</div><div class="gap-sentence">${sentenceHtml}</div>`;
  html += `<button class="check-btn" onclick="checkGapFill()">Check Answers <i class="fa-solid fa-check"></i></button><div class="feedback" id="feedback"></div><button class="next-btn" id="next-btn" onclick="nextQuestion()">Next <i class="fa-solid fa-arrow-right"></i></button>`;
  area.innerHTML = html; answered = false;
}

function onChipClick(idx, word) { if(answered) return; const chip=document.getElementById(`chip-${idx}`); if(chip.classList.contains('used')) return; document.querySelectorAll('.word-chip.selected').forEach(c=>c.classList.remove('selected')); chip.classList.add('selected'); selectedChip={idx,word}; }
function onBlankClick(blankId) { if(answered||!selectedChip) return; const el=document.getElementById(`gap-${blankId}`); if(gapState[blankId]!==null){const old=document.getElementById(`chip-${gapState[blankId].idx}`);if(old)old.classList.remove('used');} gapState[blankId]=selectedChip; el.textContent=selectedChip.word; el.classList.add('filled'); const chip=document.getElementById(`chip-${selectedChip.idx}`); chip.classList.remove('selected'); chip.classList.add('used'); selectedChip=null; }

function checkGapFill() {
  if(answered) return; answered=true; clearInterval(timerInterval);
  const q=questions.gapfill[currentQ], blankKeys=Object.keys(q.blanks); let allCorrect=true;
  blankKeys.forEach(key=>{const el=document.getElementById(`gap-${key}`);const ua=gapState[key]?gapState[key].word:'';if(ua===q.blanks[key])el.classList.add('correct-gap');else{el.classList.add('wrong-gap');allCorrect=false;const s=document.createElement('span');s.style.cssText='display:block;color:#006644;font-size:11px;font-weight:600;margin-top:2px;';s.textContent='→ '+q.blanks[key];el.appendChild(s);}});
  const fb=document.getElementById('feedback');
  if(allCorrect){score+=(streak+1)*15;streak++;totalCorrect++;roundCorrect++;if(streak>bestStreak)bestStreak=streak;if(streak===5){awardBadge('badge-streak5');showCombo('🔥 5x!');}else if(streak>=3)showCombo(`${streak}x`);fb.className='feedback show correct';fb.innerHTML=`<i class="fa-solid fa-check-circle"></i> <b>Perfect!</b> All correct!`;}
  else{loseLife();fb.className='feedback show wrong';fb.innerHTML=`<i class="fa-solid fa-times-circle"></i> <b>Not quite.</b> See corrections above.`;}
  document.getElementById('score').textContent=score;document.getElementById('streak').textContent=streak;document.getElementById('next-btn').classList.add('show');
}

function checkAnswer(idx) {
  if(answered) return; answered=true; clearInterval(timerInterval);
  const q=questions[currentMode][currentQ], opts=document.querySelectorAll('.option-btn');
  opts.forEach(o=>o.classList.add('disabled'));
  const fb=document.getElementById('feedback');
  if(idx===q.answer){opts[idx].classList.add('correct');score+=(streak+1)*10;streak++;totalCorrect++;roundCorrect++;if(streak>bestStreak)bestStreak=streak;if(streak===5){awardBadge('badge-streak5');showCombo('🔥 5x!');}else if(streak>=3)showCombo(`${streak}x`);fb.className='feedback show correct';fb.innerHTML=`<i class="fa-solid fa-check-circle"></i> <b>Correct!</b> ${q.explanation}`;}
  else{opts[idx].classList.add('wrong');opts[q.answer].classList.add('correct');loseLife();fb.className='feedback show wrong';fb.innerHTML=`<i class="fa-solid fa-times-circle"></i> <b>Not quite.</b> ${q.explanation}`;}
  document.getElementById('score').textContent=score;document.getElementById('streak').textContent=streak;document.getElementById('next-btn').classList.add('show');
}

function nextQuestion() { const qs=questions[currentMode]; currentQ++; if(currentQ>=qs.length){currentQ=0;completeRound();return;} renderQuestion(); }

function completeRound() {
  clearInterval(timerInterval); completedModes.add(currentMode);
  const checkEl=document.getElementById(`check-${currentMode}`); if(checkEl)checkEl.classList.add('show');
  awardBadge(`badge-${currentMode}`);
  if(roundCorrect===questions[currentMode].length){awardBadge('badge-perfect');showCombo('👑 PERFECT!');}
  const area=document.getElementById('question-area');
  area.innerHTML=`<div style="text-align:center;padding:30px 0;"><i class="fa-solid fa-trophy" style="font-size:48px;color:#ff991f;margin-bottom:16px;display:block;"></i><h2 style="margin:0 0 8px;">Round Complete!</h2><p style="color:var(--color-text-secondary);">Score: <b>${score}</b> | Correct: <b>${roundCorrect}/${questions[currentMode].length}</b></p><p style="font-size:12px;color:var(--color-text-muted);margin-top:12px;">${completedModes.size}/5 categories completed</p><button class="check-btn" onclick="roundCorrect=0;currentQ=0;renderQuestion();" style="margin-top:16px;">Play Again <i class="fa-solid fa-redo"></i></button></div>`;
  document.getElementById('progress-fill').style.width='100%'; roundCorrect=0;
}

// ===== ORDERING =====
function renderOrdering(q) {
  const area=document.getElementById('question-area');
  let shuffled=[...q.sentences.keys()];
  for(let i=shuffled.length-1;i>0;i--){const j=Math.floor(Math.random()*(i+1));[shuffled[i],shuffled[j]]=[shuffled[j],shuffled[i]];}
  if(JSON.stringify(shuffled)===JSON.stringify(q.correctOrder))[shuffled[0],shuffled[1]]=[shuffled[1],shuffled[0]];
  window._orderState={shuffled,q};
  let html=`<div class="q-label">Full Structure — Q${currentQ+1}/${questions.ordering.length}</div><div class="q-text">${q.instruction}</div><div class="sentence-list" id="sentence-list">`;
  shuffled.forEach((origIdx,pos)=>{html+=`<div class="sentence-item" draggable="true" data-orig="${origIdx}"><span class="num">${pos+1}</span><span>${q.sentences[origIdx]}</span></div>`;});
  html+=`</div><button class="check-btn" onclick="checkOrdering()">Check Order <i class="fa-solid fa-check"></i></button><div class="feedback" id="feedback"></div><button class="next-btn" id="next-btn" onclick="nextQuestion()">Next <i class="fa-solid fa-arrow-right"></i></button>`;
  area.innerHTML=html; answered=false; setupDragDrop();
}
function setupDragDrop(){const list=document.getElementById('sentence-list');let dragEl=null;list.querySelectorAll('.sentence-item').forEach(item=>{item.addEventListener('dragstart',e=>{dragEl=item;item.classList.add('dragging');e.dataTransfer.effectAllowed='move';});item.addEventListener('dragend',()=>{item.classList.remove('dragging');dragEl=null;updateNumbers();});item.addEventListener('dragover',e=>{e.preventDefault();if(dragEl&&item!==dragEl){const r=item.getBoundingClientRect();if(e.clientY<r.top+r.height/2)list.insertBefore(dragEl,item);else list.insertBefore(dragEl,item.nextSibling);}});item.addEventListener('touchstart',()=>{dragEl=item;item.classList.add('dragging');});item.addEventListener('touchmove',e=>{e.preventDefault();const t=e.touches[0];const els=document.elementsFromPoint(t.clientX,t.clientY);const target=els.find(el=>el.classList.contains('sentence-item')&&el!==dragEl);if(target){const r=target.getBoundingClientRect();if(t.clientY<r.top+r.height/2)list.insertBefore(dragEl,target);else list.insertBefore(dragEl,target.nextSibling);}},{passive:false});item.addEventListener('touchend',()=>{item.classList.remove('dragging');dragEl=null;updateNumbers();});});}
function updateNumbers(){document.querySelectorAll('.sentence-item .num').forEach((n,i)=>n.textContent=i+1);}
function checkOrdering(){
  if(answered)return;answered=true;clearInterval(timerInterval);
  const{q}=window._orderState;const items=document.querySelectorAll('.sentence-item');
  const userOrder=Array.from(items).map(el=>parseInt(el.dataset.orig));
  const correct=JSON.stringify(userOrder)===JSON.stringify(q.correctOrder);
  const fb=document.getElementById('feedback');
  if(correct){score+=(streak+1)*20;streak++;totalCorrect++;roundCorrect++;if(streak>bestStreak)bestStreak=streak;if(streak===5){awardBadge('badge-streak5');showCombo('🔥 5x!');}else if(streak>=3)showCombo(`${streak}x`);fb.className='feedback show correct';fb.innerHTML=`<i class="fa-solid fa-check-circle"></i> <b>Perfect!</b> Correct order!`;}
  else{loseLife();const cs=q.correctOrder.map((idx,pos)=>`${pos+1}. ${q.sentences[idx]}`).join('<br>');fb.className='feedback show wrong';fb.innerHTML=`<i class="fa-solid fa-times-circle"></i> <b>Not quite.</b> Correct order:<br><br>${cs}`;}
  document.getElementById('score').textContent=score;document.getElementById('streak').textContent=streak;document.getElementById('next-btn').classList.add('show');
}

// ===== INIT =====
renderQuestion();
</script>

</body></html>
