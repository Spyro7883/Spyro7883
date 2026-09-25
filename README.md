### Hi, I'm Eusebiu 👋

Software engineer building full-stack products and applied zero-knowledge systems.

I contributed a merged Circom/Groth16 ECDSA benchmark to
[`ethereum/csp-benchmarks`](https://github.com/ethereum/csp-benchmarks/pull/302),
reducing non-linear constraints 3x, from 1,508,904 to 503,280. I'm now working
on the [P-256 follow-up](https://github.com/ethereum/csp-benchmarks/issues/305).

---

#### Featured work

| Project | What it is | Stack |
|---|---|---|
| **[ECDSA Circuit Benchmark](https://github.com/ethereum/csp-benchmarks/pull/302)** *(merged)* | secp256k1 ECDSA verification benchmark contributed to Ethereum's client-side proving benchmark suite. Cut the verification circuit from 1,508,904 to 503,280 non-linear constraints using fake-GLV and a width-12 fixed-base comb, with a Rust harness that measures baseline against optimized. | Circom · Rust · Groth16 |
| **[P-256 ECDSA Benchmark](https://github.com/ethereum/csp-benchmarks/issues/305)** *(in progress)* | Follow-up Circom/Groth16 benchmark for secp256r1, covering a curve that already appears in four other proving systems in the suite but has no Circom entry. | Circom · Rust · P-256 |
| **[DID Wallet (ZKP)](https://github.com/Spyro7883/DID_Wallet_ZKP)** | Self-sovereign identity wallet that proves age, citizenship, and income range with zero-knowledge proofs verified on-chain, without ever revealing the raw data. | Circom · Groth16 · React Native · Solidity |
| **[Job Tracker](https://github.com/Spyro7883/job-tracker)** | Production-style job-application tracker: auth-protected dashboard, CRUD, advanced table UX, E2E tested. | Next.js · Prisma · PostgreSQL · Clerk · Playwright |
| **[MEV Forensics Agent](https://github.com/tskoyo/agentic-mev-forensics)** *(team)* | An AI agent that investigates why a DEX/MEV trade underperformed and delivers a cited report. I built the entire frontend - a real-time investigation dashboard with an SSE-streamed tool-call timeline, PnL/verdict cards, evidence panels, and shareable permalinks. | Next.js · TypeScript · TailwindCSS · SSE |
| [tex2png](https://github.com/Spyro7883/tex2png) | LaTeX-to-PNG pipeline with blank-render detection and display-mode retry. Found a silent failure mode with probe scripts, then pinned it with 48 regression tests on CI across three operating systems. | Node · JavaScript · GitHub Actions |
| **[DeFi Risk Analyzer](https://github.com/tskoyo/defi-risk-analyzer)** *(team)* | Uniswap v4 hook that raises swap fees as pool depth drops, protecting LPs from toxic flow. I built the swap UI and contract integration. | Solidity · Uniswap v4 · wagmi/viem · Next.js |


---

#### Stack

**Frontend** TypeScript · React · Next.js · TailwindCSS · shadcn/ui  
**Backend & tooling** Python · Node.js · PostgreSQL · Prisma · Docker · Pytest · Playwright · Vercel  
**ZK & systems** Circom · Groth16 · snarkjs · Rust (benchmark harness)  
**Web3** wagmi · viem · Solidity · Hardhat · Foundry

---

#### Reach me

[LinkedIn](https://www.linkedin.com/in/eusebiuspi) · eusebiu.spinu@proton.me

<sub>ETHBucharest volunteer · ETHGlobal Lisbon (in person) · ETHGlobal HackMoney & Open Agents (online) · Top 5 @ HackITAll (BCR)</sub>
