### Hi, I'm Houssam 👋

Software engineer at **[Fount](https://fount.energy)** in Bergen, Norway, working on the software
behind EV charging: charger communication over **OCPP**, roaming and billing, serverless
**TypeScript** back ends on **Google Cloud / Firebase**, and **Angular** operator portals.

Outside work I like building things from first principles: protocols, optimisation, numerical
code, trading research, and the occasional game.

---

#### 🔧 Featured projects

**[ocpp-kit](https://github.com/houssammehdi/ocpp-kit)** · TypeScript · Node.js · WebSockets\
A complete OCPP 1.6-J toolkit (all 28 messages, all six feature profiles): a typed RPC core,
a Central System with TLS security profiles 2 and 3, a resilient charge-point client, a charger
simulator for load tests, and a conformance checker that audits any CSMS against the spec.
Property-based fuzzing, Prometheus metrics and 480 tests.

**[ev-smart-charging](https://github.com/houssammehdi/ev-smart-charging)** · Python · SciPy/HiGHS\
Smart charging under grid limits, modelled the way sites are wired: per-phase fuses on TN and
Norwegian IT grids, the IEC 61851 6 A minimum, PV, demand charges and V2G. Real-time heuristics,
a MILP optimum, forecast-aware MPC and a Python OCPP controller, measured against a certified LP
bound, with a theory write-up of when each policy is optimal.

**[event-backtester](https://github.com/houssammehdi/event-backtester)** · Python · pandas\
A backtesting engine built for honest results: look-ahead ruled out by construction, realistic
fills (brackets, OCO, trailing stops, gaps), and statistics against overfitting (probability of
backtest overfitting, Hansen's SPA, stationary bootstrap, purged CV), plus portfolio
construction and an HTML tear sheet.

**[tensorgrad](https://github.com/houssammehdi/tensorgrad)** · Python · NumPy\
A deep-learning framework from scratch with derivatives of any order: `grad`, `jvp`, `hessian`
and `hvp`, and every op gradient-checked and verified against PyTorch in 131 parity tests. It
trains a character-level GPT, LSTMs and a diffusion model on a CPU.

**[NeuralStyleTransfer-PyTorch](https://github.com/houssammehdi/NeuralStyleTransfer-PyTorch)** · Python · PyTorch\
A faithful implementation of Gatys et al.'s style transfer with the original Caffe VGG-19
weights: spatial masks, colour control and coarse-to-fine synthesis, with a gallery of real
results from public-domain inputs. It started as a 2019 university project.

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
