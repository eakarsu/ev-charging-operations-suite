# EV Charging Operations Suite

Wave:
- Portfolio next-20 completion batch

Source candidates represented:
- `AIEVChargingOperationsAssistant`
- `AIEVChargingOperationsOperations`
- `AIEVChargingOperationsAnalytics`
- `AIEVChargingOperationsWorkflow`

This suite is a runnable merged app with one login, one dashboard, one feature-first sidebar, PostgreSQL-backed records/documents/notifications/audit, role behavior, and smoke coverage.

## Local Run

```bash
cd /Users/erolakarsu/projects/merged/ev-charging-operations-suite
./start.sh
```

Local URL:
- `http://127.0.0.1:18090`

Seeded users:
- `admin@ev-charging-operations.local / admin123`
- `manager@ev-charging-operations.local / manager123`
- `analyst@ev-charging-operations.local / analyst123`

## Validation

```bash
cd /Users/erolakarsu/projects/merged/ev-charging-operations-suite/frontend
npm run typecheck
SMOKE_BASE_URL=http://127.0.0.1:18090 npm run smoke
```
