### Hi, I'm Eusebiu

Full-stack developer building React and Next.js applications, with hands-on experience in applied zero-knowledge proofs (ZKP) and Rust benchmark tooling.

I contributed **two merged ECDSA verification benchmarks** to Ethereum's [client-side proving benchmark suite](https://github.com/ethereum/csp-benchmarks): [secp256k1 (#302)](https://github.com/ethereum/csp-benchmarks/pull/302) and [P-256 (#308)](https://github.com/ethereum/csp-benchmarks/pull/308). The work involved circuit optimization, measurements, Rust tooling, and code-review revisions.

Based in Bucharest, Romania. Open to frontend and full-stack opportunities, including part-time roles.

---

#### Featured work

| Project | What I built / contributed | Stack |
|---|---|---|
| **[secp256k1 ECDSA Benchmark](https://github.com/ethereum/csp-benchmarks/pull/302)** *(merged)* | Verification circuit optimization: reduced non-linear constraints from **1,508,904 to 503,280** using fake-GLV and a width-12 fixed-base comb, with Rust benchmark tooling. | Circom · Rust · Groth16 |
| **[P-256 ECDSA Benchmark](https://github.com/ethereum/csp-benchmarks/pull/308)** *(merged)* | Circom verification benchmark with **299,183 constraints**, versus 1,972,905 in the reference implementation; includes validation and exceptional-case handling after review. [Implementation and review notes](https://eusebiu.vercel.app/writing/p256-ecdsa-circom/). | Circom · Rust · Groth16 |
| **[Job Tracker](https://github.com/Spyro7883/job-tracker)** | Authenticated dashboard, CRUD, filtering, and Playwright end-to-end tests. | Next.js · Prisma · PostgreSQL · Clerk · Playwright |
| **[MEV Forensics Agent](https://github.com/tskoyo/agentic-mev-forensics)** *(team)* | I built the frontend: a real-time investigation dashboard with an SSE-streamed tool timeline, evidence panels, and shareable reports. | Next.js · TypeScript · Tailwind CSS · SSE |
| **[DID Wallet (ZKP)](https://github.com/Spyro7883/DID_Wallet_ZKP)** | Bachelor's thesis: a React Native identity wallet proving age, citizenship, and income range with zero-knowledge proofs verified on-chain, without revealing the raw data. | React Native · Circom · Groth16 · Solidity |
| **[tex2png](https://github.com/Spyro7883/tex2png)** | LaTeX-to-image tooling with blank-render detection and retry handling; 48 regression tests in CI across three operating systems. | Node.js · JavaScript · GitHub Actions |
| **[DeFi Risk Analyzer](https://github.com/tskoyo/defi-risk-analyzer)** *(team)* | I built the swap UI and smart-contract integration for a Uniswap v4 liquidity-risk prototype. | Next.js · wagmi · viem · Solidity |

---

#### Stack

**Frontend:** TypeScript · JavaScript · React · Next.js · React Native · Tailwind CSS · shadcn/ui  
**Backend & data:** Node.js · PostgreSQL · Prisma · Python  
**Testing & tooling:** Playwright · Pytest · GitHub Actions · Docker · Vercel  
**Applied ZKP & Web3:** Circom · Groth16 · snarkjs · Rust (benchmark tooling) · Solidity · wagmi · viem

---

#### Reach me

[Portfolio & engineering notes](https://eusebiu.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/eusebiuspi/) · [Email](mailto:eusebiu.spinu@proton.me)

<sub>ETHBucharest volunteer · ETHGlobal participant · Top 5 @ HackITAll (BCR)</sub>
