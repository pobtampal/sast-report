# SAST Security Scan Report

## Summary Table

| Tool | Status | Findings |
|------|--------|----------|
| Gitleaks (Secrets) | ⚪ success | N/A |
| Semgrep (Code) | ✅ success | 0 |
| Trivy (Filesystem) | ✅ success | 0 |
| gosec (Go Security) | ⚠️ success | 9 |

---

## Detailed Findings

### 🔐 Gitleaks (Secret Scanning)
  *(No findings file found - scan may not have completed)*

### 🔍 Semgrep (Static Code Analysis)
  ✅ No findings detected

### 🐳 Trivy (Container & Filesystem Scan)
  ✅ No findings detected

### 🛡️ gosec (Go Security Linter)
  Found 9 issue(s):
  *(Unable to parse results)*

---

## Metadata & Links

**Execution Details**
- Commit: [`912171d`](https://github.com/pobtampal/GCP-Sec/commit/912171d4ffbac5a69c1b6375815486b39c51d3c7)
- Branch: `main`
- Actor: @pobtampal
- Timestamp: 2026-03-10 15:16:00 UTC
- Workflow Run: [View on GitHub](https://github.com/pobtampal/GCP-Sec/actions/runs/22909453622)

**Resources**
- [GitHub Security Code Scanning](https://github.com/pobtampal/GCP-Sec/security/code-scanning)
- [Action Artifacts](https://github.com/pobtampal/GCP-Sec/actions/runs/22909453622)
