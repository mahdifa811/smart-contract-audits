# Smart Contract Audit Reports

**Welcome to my portfolio of security audits for open-source blockchain projects!**  
 This repository contains detailed audit reports for open-source projects, conducted voluntarily to contribute to the blockchain community and enhance my auditing skills.

## About Me
- **Experience**: Competed in audit contests on Sherlock and Code4rena
- **Focus Areas**: Reentrancy, access control, logical flaws, integer overflows
- **Tools**: Slither, Mythril, manual code review
- **Contact**: [karizmeh811@proton.me](mailto:karizmeh811@proton.me) | [GitHub](https://github.com/mahdifa811) | [X/Twitter](https://x.com/MahdiKariz)

## Featured Audits

### 🏆 CrowdFunding.sol (September 2025)
**Project**: [CrowdFunding](https://github.com/hassan4702/crowdfunding) by Hassan Shakil  
**Type**: Non-production, personal learning project  
**Findings**: 9 issues (3 High, 2 Medium, 3 Low, 1 Informational)  
**Report**: [Full Report](audits/crowd-funding/audit-report.md) | [PDF](audits/crowd-funding/audit-report.pdf)  
**Key Findings**:
- **Reentrancy in refund process** (High): Double-spending vulnerability
- **Campaign ID overlap** (High): Data overwriting due to ID reuse
- **Emergency refund logic flaw** (Medium): Off-by-one error preventing complete refunds

---

## Audit Methodology

Each audit follows a rigorous process:

### 🔍 **Phase 1: Reconnaissance**
- Project scope analysis
- Architecture and dependency review
- Threat modeling

### 🛡️ **Phase 2: Static Analysis**
- Manual code review (line-by-line)
- Static analysis tools (Slither, Mythril)
- Pattern detection (reentrancy, access control)

### 🧪 **Phase 3: Dynamic Testing**
- Attack scenario simulation
- Boundary condition testing
- Gas optimization analysis

### 📊 **Phase 4: Reporting**
- Severity classification (High/Medium/Low/Informational)
- Proof-of-concept scenarios
- Mitigation recommendations

## Severity Classification

| Severity | Impact | Examples |
|----------|--------|----------|
| **High** | Financial loss, data corruption | Reentrancy, access control failures |
| **Medium** | Logic violations, DoS potential | Incorrect calculations, emergency mode issues |
| **Low** | UX issues, gas inefficiencies | Event emission errors, rounding issues |
| **Informational** | Best practices, optimizations | Code style, documentation improvements |

## Recent Activity

| Date | Project | Findings | Status |
|------|---------|----------|--------|
| Sep 2025 | CrowdFunding.sol | 9 (3H/2M/3L/1I) | Completed |


## Responsible Disclosure

All audits adhere to responsible disclosure principles:
- **Private reporting** for critical vulnerabilities
- **Owner permission** for public sharing
- **30-day disclosure** timeline for non-responsive projects
- **Redaction** of sensitive details in public reports

## Get in Touch

Looking for a security audit? Have questions about my methodology? Let's connect:

- **Email**: [karizmeh811@proton.me](mailto:karizmeh811@proton.me)
- **GitHub**: [mahdifa811](https://github.com/mahdifa811)
- **X/Twitter**: [@mahdiFa](https://x.com/MahdiKariz)
- **Portfolio**: [Audit Reports](https://github.com/mahdifa811/audit-reports)

---

## License

This repository is licensed under [MIT License](LICENSE). Individual audit reports may have different licensing based on project permissions.

---

*Built with ❤️ for the Web3 security community*
