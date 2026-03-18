# Publishing Checklist

## Repository Targets

- `portfolio-ai-engineering`
- `law-hub-legal-system`
- `own-acquirer-panel`
- `automation-tools`
- `ai-systems`
- `fintech-projects`
- `gabrielrmsaganski-cpu.github.io`

## Before Push

1. Review for any remaining local credentials or machine-specific data.
2. Replace placeholder LinkedIn URL if needed.
3. Optionally add GitHub Actions CI for lint/build/test.
4. Create the corresponding GitHub repositories under `gabriel-saganski`.
5. Set the Pages repo default branch and enable GitHub Pages from root.

## Suggested Push Flow

```powershell
cd C:\Users\Administrator\gabriel-saganski\<repo-name>
git remote add origin git@github.com:gabrielrmsaganski-cpu/<repo-name>.git
git push -u origin main
```
