# Success Criteria - Cloud PM Demo App

## Baseline
- Demo app accessible at http://localhost:3000
- Page loads under 500ms locally

## After Migration (Cloud Deployment)
- Demo app accessible at http://<cloud-url>
- 95th percentile (p95) latency improves by 10% compared to baseline
- Deployment frequency: at least 2 deploys per day during testing

## GameDay (Simulated Incident)
- Mean time to detect (MTTD): < 5 minutes
- Mitigation (restart container or rollback) executed within 10 minutes
