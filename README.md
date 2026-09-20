### Hi, I'm Houssam 👋

Software engineer at **[Fount](https://fount.energy)** in Bergen, Norway, working on the software
behind EV charging: charger communication over **OCPP**, roaming and billing, serverless
**TypeScript** back ends on **Google Cloud / Firebase**, and **Angular** operator portals.

Outside work I like building things from first principles: protocols, optimisation, numerical
code, trading research, and the occasional game.

---

#### 🔧 Featured projects

**[ocpp-kit](https://github.com/houssammehdi/ocpp-kit)** · TypeScript · Node.js · WebSockets\
Type-safe OCPP 1.6-J toolkit: spec-exact RPC framing and error mapping, a Central System
server, a charge-point client with backoff and an offline transaction queue, and a simulator
with smart-charging profiles that can load-test a CSMS with hundreds of virtual chargers.

**[ev-smart-charging](https://github.com/houssammehdi/ev-smart-charging)** · Python · SciPy/HiGHS\
Schedules EV charging at sites with more chargers than grid capacity. It compares real-time
heuristics (EDF, least laxity, price-aware) with a perfect-foresight MILP and an online MPC
controller, measured against a certified LP lower bound, and it models the IEC 61851 6 A
minimum, PV and demand charges.

**[event-backtester](https://github.com/houssammehdi/event-backtester)** · Python · pandas\
Event-driven backtesting engine built for correctness. Look-ahead is ruled out by construction,
fills model gaps, slippage and volume caps, and the accounting is checked every bar. It includes
walk-forward optimisation with the deflated Sharpe ratio, plus a vectorized fast path that
matches the event engine to floating-point precision.

**[tensorgrad](https://github.com/houssammehdi/tensorgrad)** · Python · NumPy\
A deep-learning framework from scratch: reverse-mode autodiff over n-d tensors, 43
gradient-checked ops, and PyTorch-style `nn` and `optim` modules. Examples go up to a
character-level GPT that trains on a CPU in under four minutes.

**[NeuralStyleTransfer-PyTorch](https://github.com/houssammehdi/NeuralStyleTransfer-PyTorch)** · Python · PyTorch\
VGG-19 neural style transfer (Gatys et al.) with multi-style blending and colour preservation.
It started as a 2019 university project and has been rewritten as a tested package with a CLI.

---

#### 🧰 Tech

| | |
|---|---|
| **Languages** | TypeScript · Python · JavaScript · SQL · Java |
| **Back end & cloud** | Node.js · Firebase / Cloud Functions · Firestore · Google Cloud (BigQuery, Cloud Tasks) · WebSockets · REST |
| **Front end** | Angular · RxJS · React / Next.js · Tailwind CSS |
| **Energy & EV** | OCPP 1.6-J · smart charging · roaming · charge-point management |
| **Data & ML** | NumPy · pandas · SciPy · PyTorch |
| **Engineering** | Git · GitHub Actions · Docker · Vitest / Jest · pytest / Hypothesis · Playwright |

📍 Bergen, Norway · 🏢 [fount.energy](https://fount.energy)
