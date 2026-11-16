<div align="center">

# Mehrdad Dastouri

**Quantitative Machine Learning Researcher & Systems Engineer**

*Core Focus: Market Microstructure • Stochastic Control • Distributionally Robust Reinforcement Learning*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat&logo=gmail&logoColor=white)](mailto:mehrdaddastouri@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Repositories-181717?style=flat&logo=github)](https://github.com/MehrdadDastouri?tab=repositories)

---

> *"Engineering deterministic, zero-allocation matching infrastructure and modeling endogenous reflexivity in financial microstructure."*

</div>

---

### 🔬 Research & Engineering Vectors

- **Market Microstructure & Order Flow Dynamics:** FIFO queue priority tracking, cancellation hazard modeling, multi-level Order Flow Imbalance (OFI), and empirical price impact calibration.
- **Order Flow Toxicity & Non-Synchronous Econometrics:** Volume-Synchronized Probability of Toxicity (VPIN) using Bulk Volume Classification, and linear $\mathcal{O}(N+M)$ Hayashi-Yoshida cross-asset lead-lag discovery.
- **Statistical Regime Shifts & State-Space Filtering:** Bayesian Online Changepoint Detection (BOCPD) under Student-t conjugate priors, log-space Hidden Markov Models (HMM), and dynamic Kalman Filter hedge ratio tracking.
- **Low-Latency Systems Engineering:** Sub-microsecond execution loops, memory pools (`__slots__`), cache-conscious contiguous arrays, and Big-Endian zero-allocation binary protocol codecs (NASDAQ ITCH 5.0 / OUCH 5.0).

---

### 🚀 Production & Open-Source Infrastructure

| Engine / Gateway | Focus & Architecture | Performance Benchmark |
| :--- | :--- | :--- |
| **[`lob-engine`](https://github.com/MehrdadDastouri/lob-engine)** | Level-3 LOB matching core with intrusive memory pools & deterministic $\mathcal{O}(1)$ cancellations. | **~2.4M ops/sec** • P50: **360 ns** |
| **[`ouch-gateway`](https://github.com/MehrdadDastouri/ouch-gateway)** | NASDAQ OUCH 5.0 binary order entry codec & atomic order replacement session simulator. | **~2.3M pkts/sec** • P50: **380 ns** |
| **[`itch-parser`](https://github.com/MehrdadDastouri/itch-parser)** | Streaming NASDAQ ITCH 5.0 direct binary market data protocol decoder. | **~2.1M msgs/sec** • P50: **410 ns** |
| **[`vpin-engine`](https://github.com/MehrdadDastouri/vpin-engine)** | Volume-clock sampling engine evaluating toxicity (VPIN) via Bulk Volume Classification (BVC). | **~2.8M trades/sec** • P50: **280 ns** |
| **[`ofi-engine`](https://github.com/MehrdadDastouri/ofi-engine)** | Cont-Kukanov-Stoikov multi-level Order Flow Imbalance & contemporaneous price impact estimator. | **~1.6M snaps/sec** • P50: **520 ns** |
| **[`optimal-exec`](https://github.com/MehrdadDastouri/optimal-exec)** | Closed-form Almgren-Chriss optimal liquidation solver under temporary & permanent impact. | **~720k paths/sec** • P50: **1.25 µs** |
| **[`leadlag-matrix`](https://github.com/MehrdadDastouri/leadlag-matrix)** | Linear-time $\mathcal{O}(N+M)$ Hayashi-Yoshida non-synchronous covariation & lead-lag matrix engine. | **~3.2M ticks/sec** • Linear Sweep |
| **[`regime-shift`](https://github.com/MehrdadDastouri/regime-shift)** | $\mathcal{O}(K)$ Bayesian Online Changepoint Detection (BOCPD) with Normal-Inverse-Gamma filtering. | **~24.5k updates/sec** • P50: **38 µs** |
| **[`pairs-coint`](https://github.com/MehrdadDastouri/pairs-coint)** | State-space Kalman dynamic hedge ratio tracking, Engle-Granger test, and bivariate VECM. | **~2.1M updates/sec** • P50: **420 ns** |
| **[`markov-regime`](https://github.com/MehrdadDastouri/markov-regime)** | Zero-allocation Gaussian HMM online regime filter (LogSumExp) & Viterbi sequence decoder. | **~1.2M updates/sec** • P50: **740 ns** |

---

### 🛠 Core Technical Stack

- **Languages:** Python (AsyncIO, Cython/C-Extensions), C++ (C++20, Memory Layouts), Julia, Bash
- **Quantitative & Numerical:** NumPy, SciPy, PyTorch, Numba, CVXPY
- **Telemetry & High-Throughput:** Polars, DuckDB, FlatBuffers, ZeroMQ, Socket Programming
- **Tooling & Environments:** Linux (WSL2/Ubuntu), Docker, Git, CI/CD Actions, Pytest

---

<div align="center">

### 📊 Telemetry & Activity

<img src="https://github-readme-stats.vercel.app/api?username=MehrdadDastouri&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117" alt="GitHub Stats" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MehrdadDastouri&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117" alt="Top Languages" width="42%" />

<br />

*Engineered with mathematical rigor • Focused on computational determinism*

</div>
