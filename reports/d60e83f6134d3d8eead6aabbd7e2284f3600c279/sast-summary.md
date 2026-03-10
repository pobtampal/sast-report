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
- Commit: [`d60e83f`](https://github.com/pobtampal/GCP-Sec/commit/d60e83f6134d3d8eead6aabbd7e2284f3600c279)
- Branch: `main`
- Actor: @pobtampal
- Timestamp: 2026-03-10 05:32:19 UTC
- Workflow Run: [View on GitHub](https://github.com/pobtampal/GCP-Sec/actions/runs/22888624917)

**Resources**
- [GitHub Security Code Scanning](https://github.com/pobtampal/GCP-Sec/security/code-scanning)
- [Action Artifacts](https://github.com/pobtampal/GCP-Sec/actions/runs/22888624917)
