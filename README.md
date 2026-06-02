# DIKWP TransitTrustGraph OS

DIKWP TransitTrustGraph OS is a GitHub-ready reference system for a Guangdong/Guangzhou bus group DIKWP pilot. It focuses on offline enterprise knowledge governance, white-box RAG answer cards, evidence ledgers, passenger-service drafts, safety escalation tickets, new-energy operation review tickets, and training microcases.

It does not connect to production dispatch, vehicles, chargers, ticketing, cameras, or safety-critical equipment.

## Quick start

```bash
pip install -e .
transittrustgraph analyze examples/sample_transit_knowledge_case.json --out outputs/demo
transittrustgraph static-audit src --out outputs/demo/static_boundary_audit_report.json
```

## Strategic use

Open-source the reference core. Keep official DIKWP pilot review, industry adapter packs, TrustPassport registry, signed assessment reports, and deployment services as value layers.
