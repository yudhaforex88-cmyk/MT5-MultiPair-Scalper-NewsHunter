# MT5 MultiPair Scalper + NewsHunter — Foundation v1.2
**Safety:** trading disabled by default; News Hunter monitor-only. Scaffold only—not a finished EA, compile, or backtest claim.

## Build
Copy `MQL5/` into your MT5 terminal data folder. Open `MQL5/Experts/MPNH/MPNH_Main.mq5` in MetaEditor and compile. `InpEnableTrading=false` is intentional. No strategy entry is implemented.

## Safety
- No order API implemented in this scaffold.
- Risk manager fails closed.
- News has no ExecutionGateway dependency.
- Do not enable live trading until execution, risk, ownership, protection and validation are audited.
