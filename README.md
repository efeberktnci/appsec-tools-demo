# AppSec Tools Demo (CI/CD Security)

Bu repo, AppSec portfolyomu "delivery kasi" ile guclendirmek icin CI/CD guvenlik demolari icerir:
SAST + SCA + secrets scan + SBOM.

Hedef: pipeline calissin, ciktilar README'de gorunsun, her tool icin kisa "ne yakalar / nasil yorumlarim" notu olsun.

## Plan (High-Level)
- SAST: CodeQL veya Semgrep
- SCA: Dependabot + osv-scanner (veya benzeri)
- Secrets: gitleaks
- SBOM: syft

Detay: `docs/PLAN.md`

## Portfolio Baglanti
Ana portfolio repo: `https://github.com/efeberktnci/appsec-portfolio`
