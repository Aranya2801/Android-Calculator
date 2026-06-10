# Contributing to Android Calculator

Thank you for your interest in contributing! 🎉

## Development Setup

1. Fork & clone the repo
2. `npm install`
3. `npm run dev` — starts dev server at `http://localhost:5173/Android-Calculator/`

## Branch Naming

| Type | Pattern | Example |
|------|---------|---------|
| Feature | `feature/description` | `feature/graphing-mode` |
| Bug fix | `fix/description` | `fix/trig-deg-conversion` |
| Docs | `docs/description` | `docs/update-readme` |
| Refactor | `refactor/description` | `refactor/calc-engine` |

## Commit Messages

Follow [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: add graphing mode
fix: correct RAD to DEG conversion in tan()
docs: update keyboard shortcuts table
refactor: extract base conversion logic
test: add factorial edge case tests
```

## Code Style

- TypeScript strict mode — no `any` types
- Functional React components only
- CSS custom properties for all theming
- Keep component files focused (< 200 lines)

## Pull Request Checklist

- [ ] `npm run build` passes with no errors
- [ ] `npm run lint` reports no new warnings
- [ ] Feature is tested manually in all 4 themes
- [ ] README updated if new features are added
- [ ] New utility functions have JSDoc comments

## Reporting Bugs

Please open an issue with:
- Steps to reproduce
- Expected vs actual behavior
- Browser & OS version
- Screenshot if applicable

## Questions?

Open a Discussion or ping [@Aranya2801](https://github.com/Aranya2801) on GitHub.
