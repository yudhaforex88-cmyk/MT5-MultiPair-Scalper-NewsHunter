# Build & Audit
- [ ] Copy MQL5 into terminal data directory; open MPNH_Main.mq5.
- [ ] Compile in MetaEditor; resolve all warnings/errors. Do not claim compile locked without actual output.
- [ ] Confirm InpEnableTrading=false.
- [ ] Static search: order APIs must only ever be in ExecutionGateway.
- [ ] Verify news module has no execution dependency.
- [ ] Test risk math, signal expiry, exposure allocation, state transitions, stop monotonicity, idempotency, reconciliation.
- [ ] Backtest with realistic tick/spread/commission; run OOS, demo soak and fault injection.
