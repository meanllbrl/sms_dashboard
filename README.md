# KPI Dashboard

Secure, Notion-compatible KPI dashboard with encrypted parameters.

## Features

- ✅ Notion dark/light mode compatible
- ✅ Fully responsive design
- ✅ Secure API access
- ✅ Auto-refresh capability
- ✅ 6 metric categories

## Metrics

1. **Students** - Active student count
2. **Revenue** - MRR, ARR, WRR
3. **Student Value** - LTV, ARPU
4. **Acquisition** - CAC, LTV/CAC Ratio
5. **Activity** - Class frequency, duration, churn
6. **Performance** - Hourly revenue, monthly average

## Security

- No hardcoded endpoints
- No hardcoded credentials
- All sensitive data passed via encrypted URL parameters
- Query parameter authentication
- Zero sensitive data in repository

## Architecture

Dashboard receives all configuration through URL query parameters:
- Authentication key
- Encrypted endpoint URL

No sensitive information is stored in the codebase.
