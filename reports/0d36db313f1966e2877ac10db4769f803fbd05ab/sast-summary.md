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
- Commit: [`0d36db3`](https://github.com/pobtampal/GCP-Sec/commit/0d36db313f1966e2877ac10db4769f803fbd05ab)
- Branch: `main`
- Actor: @SuparnaKScope
- Timestamp: 2026-03-09 04:46:11 UTC
- Workflow Run: [View on GitHub](https://github.com/pobtampal/GCP-Sec/actions/runs/22838767166)

**Resources**
- [GitHub Security Code Scanning](https://github.com/pobtampal/GCP-Sec/security/code-scanning)
- [Action Artifacts](https://github.com/pobtampal/GCP-Sec/actions/runs/22838767166)
