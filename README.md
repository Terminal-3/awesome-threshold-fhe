# 🔐 Awesome Threshold FHE (ThFHE)

> A curated list of foundational and advanced research papers on **Threshold Fully Homomorphic Encryption**, inspired by [Andreea Alexandru’s MPTS 2023 talk](https://csrc.nist.gov/Events/2023/mpts-2023).

Threshold FHE allows multiple parties to collaboratively perform fully homomorphic encryption operations — including joint key generation, distributed evaluation, and threshold decryption — while maintaining cryptographic security even under passive or active adversarial models.

---

## 🧱 Core Threshold FHE Schemes

> Papers that directly propose threshold FHE schemes.

- [BD10] Bendlin & Damgård. *Threshold decryption and ZK proofs for lattice-based crypto*. [TCC 2010](https://doi.org/10.1007/978-3-642-11799-2_13)
- [AJL+12] Asharov et al. *Low-overhead MPC via ThFHE*. [EUROCRYPT 2012](https://doi.org/10.1007/978-3-642-29011-4_29)
- [LATV12] López-Alt et al. *Multikey FHE for MPC in the cloud*. [STOC 2012](https://doi.org/10.1145/2213977.2214086)
- [BGG+18] Boneh et al. *Threshold crypto from ThFHE*. [CRYPTO 2018](https://doi.org/10.1007/978-3-319-96884-1_20)
- [SPT+21] Sav et al. *POSEIDON: Federated learning with MPHE*. [NDSS 2021](https://arxiv.org/abs/2104.10295)
- [MBH23] Mouchet et al. *Efficient access structure for RLWE ThFHE*. [Journal of Cryptology](https://doi.org/10.1007/s00145-023-09448-0)
- [CCK23] Cheon et al. *Improved universal thresholdizer*. [ePrint 2023/1223](https://eprint.iacr.org/2023/1223)

---

## 🆕 New (2024–2025) Core ThFHE Schemes

> Latest research advancing the efficiency and scalability of Threshold FHE.

- **Passelègue & Stehlé (2024)**. *Low Communication Threshold Fully Homomorphic Encryption*.  
  [ePrint 2024/1984](https://eprint.iacr.org/2024/1984)

- **Chang & Li (2025)**. *Arbitrary‑Threshold FHE with Lower Complexity*.  
  USENIX Security 2025; [ePrint 2025/084](https://eprint.iacr.org/2025/084)

- **Okada & Takagi (2025)**. *Low Communication ThFHE from Standard (Module‑)LWE*.  
  [ePrint 2025/409](https://eprint.iacr.org/2025/409)

---

## ⚙️ Building Blocks: From FHE to ThFHE

> Supporting components such as keygen, scheme-switching, bootstrapping.

- [CLO+13] Choudhury et al. *Interpolating between MPC and FHE*. [ASIACRYPT 2013](https://doi.org/10.1007/978-3-642-42033-7_12)
- [GGP+23] Geva et al. *MPHE for collaborative cancer research*. [PNAS](https://www.pnas.org/doi/full/10.1073/pnas.2304415120)
- [MW16] Mukherjee & Wichs. *2-Round MPC via Multikey FHE*. [EUROCRYPT 2016](https://doi.org/10.1007/978-3-662-49896-5_26)
- [DS16] Ducas & Stehlé. *Sanitization of FHE ciphertexts*. [EUROCRYPT 2016](https://doi.org/10.1007/978-3-662-49896-5_11)

---

## 🔒 Passive Security in ThFHE

> Security under honest-but-curious adversaries.

- [LM21] Li & Micciancio. *Security of approximate HE*. [EUROCRYPT 2021](https://doi.org/10.1007/978-3-030-77886-6_23)
- [LMSS22] Li et al. *DP-secure CKKS*. [CRYPTO 2022](https://doi.org/10.1007/978-3-031-15982-4_20)
- [AV21] Akavia & Vald. *Privacy of CPA-secure HE*. [ePrint 2021/1376](https://eprint.iacr.org/2021/1376)
- [KS23] Kluczniak & Santato. *Circuit-private Multikey/ThFHE*. [ePrint 2023/346](https://eprint.iacr.org/2023/346)
- [BS23] Boudgoust & Scholl. *Simple ThFHE from LWE*. [ePrint 2023/003](https://eprint.iacr.org/2023/003)

---

## 🛡️ Active Security in ThFHE

> Security against malicious adversaries, including zero-knowledge and simulation-based models.

- [ABGS22] Aranha et al. *Verifiable mix-nets for Th crypto*. [ePrint 2022/1251](https://eprint.iacr.org/2022/1251)
- [CMS+23] Chatel et al. *PELTA: Maliciously secure MPHE*. [ePrint 2023/200](https://eprint.iacr.org/2023/200)
- [DDE+23] Dahl et al. *Noah’s Ark: Efficient ThFHE via noise flooding*. [ePrint 2023/168](https://eprint.iacr.org/2023/168)
- [VKH23] Viand et al. *Verifiable FHE*. [arXiv 2301.07041](https://arxiv.org/abs/2301.07041)
- [KPR18] Keller et al. *SPDZ overdrive*. [EUROCRYPT 2018](https://doi.org/10.1007/978-3-319-78375-8_6)

---

## 🔁 Thresholdizing Lattice-Based PKE

> Adapting PKE schemes for distributed decryption and key generation.

- [BGGK17] Boneh et al. *Universal thresholdizer*. [ePrint 2017/1013](https://eprint.iacr.org/2017/1013)
- [CS19] Cozzo & Smart. *Threshold post-quantum sigs*. [IMA 2019](https://doi.org/10.1007/978-3-030-30323-5_8)
- [KLO+19] Kraitsberg et al. *Distributed keygen + decryption*. [ACISP 2019](https://doi.org/10.1007/978-3-030-21568-2_9)
- [DLN+21] Devevey et al. *Non-interactive CCA2-secure Th crypto*. [PKC 2021](https://doi.org/10.1007/978-3-030-75245-3_23)
- [ASY22] Agrawal et al. *Round-optimal Th lattice signatures*. [ePrint 2022/634](https://eprint.iacr.org/2022/634)
- [GKS23] Gur et al. *Threshold lattice sigs from ThFHE*. [ePrint 2023/1090](https://eprint.iacr.org/2023/1090)
- [CCMS21] Cong et al. *Gladius: Hybrid PKE with distributed decryption*. [ASIACRYPT 2021](https://doi.org/10.1007/978-3-030-92068-5_5)

---

## 🧪 Circuit & Functional Privacy

> Research on input/function hiding, malleability, and privacy relaxations.

- [BdPMW16] Bourse et al. *Circuit privacy almost for free*. [CRYPTO 2016](https://doi.org/10.1007/978-3-662-53018-4_3)
- [OPCPC14] Ostrovsky et al. *Malicious circuit-private FHE*. [CRYPTO 2014](https://doi.org/10.1007/978-3-662-44371-2_30)
- [BSW11] Boneh et al. *Targeted malleability in HE*. [ITCS 2011](https://doi.org/10.1145/1993636.1993666)

---

## 📖 Foundational HE Works

> Must-read general papers for understanding underlying FHE schemes.

- [Gen09] Craig Gentry. *FHE PhD Thesis*. [PDF](https://crypto.stanford.edu/craig/craig-thesis.pdf)
- [Bra12] Brakerski. *FHE from classical GapSVP*. [CRYPTO 2012](https://doi.org/10.1007/978-3-642-32009-5_49)
- [FV12] Fan & Vercauteren. *Somewhat practical FHE*. [ePrint 2012/144](https://eprint.iacr.org/2012/144)
- [GHS13] Gentry et al. *FHE from LWE with ABE*. [CRYPTO 2013](https://doi.org/10.1007/978-3-642-40041-4_5)
- [BGV14] Brakerski et al. *Leveled FHE without bootstrapping*. [TOCT](https://dl.acm.org/doi/10.1145/2591791)
- [DM15] Ducas & Micciancio. *FHEW: Fast bootstrapping*. [EUROCRYPT 2015](https://doi.org/10.1007/978-3-662-46800-5_24)
- [CKKS17] Cheon et al. *CKKS: Approximate HE*. [ASIACRYPT 2017](https://doi.org/10.1007/978-3-319-70694-8_18)

---

## 📬 Contributing

If you know of any recent or classic paper on ThFHE (construction, optimization, attack, implementation), feel free to open a PR! Contributions are very welcome 🚀

---

## 📘 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).