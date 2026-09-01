<h1 align="center">Hey, I'm Arush! 👋</h1>
<h3 align="center">Zero-Knowledge Engineer & Smart Contract Developer</h3>

<p align="center">
  <a href="https://linkedin.com/in/04arush/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/04arush"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://x.com/04arush"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"/></a>
  <a href="https://04arush.github.io"><img src="https://img.shields.io/badge/Portfolio-4E5EE4?style=for-the-badge&logo=Web&logoColor=white"/></a>
  <a href="mailto:04arush@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a><br>
  <a href="https://github.com/04arush/04arush/blob/main/sc_dev_resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-6E40C9?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/></a>
</p>

---

## About Me

I'm a blockchain developer specializing in Solidity Smart Contract development and Zero-Knowledge Cryptography. My focus is on DeFi Protocols, on-chain automation, and rigorous testing. I have built and deployed production contracts integrating Chainlink VRF and Automation, and I am authoring ZK circuits in Noir—spanning Merkle Sum Tree proof-of-solvency and undercollateralised credit verification. 

My on-chain proof verification leverages Barretenberg UltraHonk, and my testing methodology is grounded in security principles like invariant and fuzz testing.

- 🔬 **Actively building:** Noir circuits · Barretenberg UltraHonk verifiers · Merkle Sum Trees · Poseidon Hashing
- ⚒️ **Strong foundation:** Solidity · Foundry · DeFi mechanics · TypeScript · Ethernaut security basics
- 🛡️ **Security mindset:** reentrancy, access control, invariant testing, fuzz testing
- 🌍 Based in New Delhi, India · Open to relocation & Remote friendly
- 💼 Targeting **ZK Engineer** and **Smart Contract Developer** roles

---

## ZK & Cryptography Stack

<div align="center">

![Noir](https://img.shields.io/badge/Noir-6E40C9?style=for-the-badge&logo=ethereum&logoColor=white)
![Barretenberg](https://img.shields.io/badge/Barretenberg-4B0082?style=for-the-badge&logo=ethereum&logoColor=white)
![SNARKs/STARKs](https://img.shields.io/badge/SNARKs%2FSTARKs-4B0082?style=for-the-badge&logo=ethereum&logoColor=white)
![UltraHonk](https://img.shields.io/badge/UltraHonk-8B00FF?style=for-the-badge&logo=ethereum&logoColor=white)
![ZK Rollups](https://img.shields.io/badge/ZK_Rollups-5C2D91?style=for-the-badge&logo=ethereum&logoColor=white)

</div>

## Smart Contract Stack

<div align="center">

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-000000?style=for-the-badge&logo=ethereum&logoColor=white)
![Chainlink](https://img.shields.io/badge/Chainlink-375BD2?style=for-the-badge&logo=Chainlink&logoColor=white)
![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?style=for-the-badge&logo=OpenZeppelin&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white)

</div>

## Languages & Tools

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## Featured Projects

**[Zero-Knowledge Proof of Solvency](https://github.com/04arush/ZK-Proof-of-Solvency)** — `Noir · TypeScript · Barretenberg · Solidity · Foundry`
> A ZK proof-of-solvency protocol letting an asset custodian prove liabilities coverage and honest per-user inclusion without disclosing individual account data. Built on a Merkle Sum Tree where every node commits to a Poseidon hash and a running balance sum. The Noir circuit matches the root sum to declared liabilities and constrains every balance to [0, 2^64) via native range checks to close negative-balance attacks. The UltraHonk proof is consumed on-chain by `proveAndRecord()`, with custom contract logic holding 100% test coverage. 

**[ZK-Powered Undercollateralized Lending Protocol](https://github.com/04arush/ZK-Powered-Uncollateralized-Lending-Protocol)** — `Noir · Barretenberg · Solidity · Foundry · Next.js`
> A DeFi lending protocol enabling a 50% collateral ratio (vs the standard 150%) by verifying off-chain creditworthiness via ZK proofs. The Noir circuit takes credit score and income as private inputs, and `nargo prove` produces a proof validated by an on-chain Barretenberg UltraVerifier. Implements strict Solidity conventions, ReentrancyGuard, and SafeERC20. Test suite includes 23 passing tests covering unit, fuzz (256 runs), and invariant testing (128,000 actions per invariant) utilizing ghost-variable tracking. Deployed to Sepolia across 5 iterations.

**[Decentralized Provably Fair Raffle](https://github.com/04arush/Raffle-Contest)** — `Solidity · Chainlink VRF v2.5 · Chainlink Automation · Foundry`
> A fully autonomous on-chain raffle utilizing Chainlink VRF v2.5 for verifiable randomness and Chainlink Automation for autonomous upkeep. Features a HelperConfig pattern for chain-aware deployment on Anvil (with a VRFCoordinatorV2_5Mock) and Sepolia. Rigorously tested with 12 unit tests, fuzz testing, and a `skipFork` modifier for VRF-mock tests.

---

## Hackathons & Education

### 🏆 Hackathons
*   **ETHOnline 2026** - ETHGlobal Async Hackathon (Upcoming)
*   **Frostbyte Hackathon Finale** — Devpost Online Participation Award. Advanced to the finale by building the ZK-Powered Undercollateralized Lending Protocol.
*   **Frostbyte Hackathon Qualifier** — Devpost Online Participation & Completion Recognition. Submitted an Employee Payroll Manager powered by Chainlink Automation.

### 🎓 Education
*   **Indira Gandhi National Open University (IGNOU)** — Bachelor's in Computer Application (Aug 2023 - Ongoing)

---

## Certifications

| | Certification | Issuer | Date |
|--|--------------|--------|------|
| ✅ | [Noir Programming & ZK Circuits](https://profiles.cyfrin.io/u/arush/achievements/noir-programming-and-zk-circuits) | Cyfrin Updraft | Apr 2026 |
| ✅ | [Fundamentals of Zero-Knowledge Proofs](https://profiles.cyfrin.io/u/arush/achievements/fundamentals-of-zero-knowledge-proofs) | Cyfrin Updraft | Mar 2026 |
| ✅ | [Advanced Foundry](https://profiles.cyfrin.io/u/arush/achievements/advanced-foundry) | Cyfrin Updraft | Mar 2026 |
| ✅ | [Foundry Fundamentals](https://profiles.cyfrin.io/u/arush/achievements/foundry) | Cyfrin Updraft | Mar 2026 |
| ✅ | [Solidity Smart Contract Development](https://profiles.cyfrin.io/u/arush/achievements/solidity) | Cyfrin Updraft | Jan 2026 |
| ✅ | [Rust Programming Basics](https://profiles.cyfrin.io/u/arush/achievements/rust-programming-basics) | Cyfrin Updraft | Feb 2026 |
| ✅ | [Advanced Web3 Wallet Security](https://profiles.cyfrin.io/u/arush/achievements/advanced-web3-wallet-security) | Cyfrin Updraft | Feb 2026 |
| ✅ | [Web3 Wallet Security Basics](https://profiles.cyfrin.io/u/arush/achievements/web3-wallet-security-basics) | Cyfrin Updraft | Feb 2026 |
| ✅ | [Blockchain Basics](https://profiles.cyfrin.io/u/arush/achievements/blockchain-basics) | Cyfrin Updraft | Dec 2025 |

---

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=04arush&theme=dark&hide_border=true&background=0D1117&ring=6E40C9&fire=6E40C9&currStreakLabel=FFFFFF)

</div>
