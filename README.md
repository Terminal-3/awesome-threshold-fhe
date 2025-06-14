🔐 Awesome Threshold FHE (ThFHE)
A curated list of foundational and advanced research papers on Threshold Fully Homomorphic Encryption, inspired by Andreea Alexandru’s MPTS 2023 talk.

🧱 Core Threshold FHE Schemes
Papers that directly propose threshold FHE schemes.

[BD10] Bendlin & Damgård. Threshold decryption and zero-knowledge proofs for lattice-based cryptosystems.
ePrint 2009/539

[AJL+12] Asharov, Jain, Lin, Liu, Sahai, Seyalioglu, and Yao. Multiparty Computation with Low Communication, Computation and Interaction via Threshold FHE.
ePrint 2011/535

[LATV12] López-Alt, Tromer, Vaikuntanathan. On-the-Fly Multiparty Computation on the Cloud via Multikey FHE.
ePrint 2011/535 (Note: same as above; both papers present similar ideas, but the main multikey FHE paper is ePrint 2011/277)

[BGG+18] Boneh, Gentry, Halevi, Ishai, Sahai, Waters. Threshold Cryptosystems from Threshold Fully Homomorphic Encryption.
ePrint 2018/206

[SPT+21] Sav, Polychroniadou, Tang, Wang, Wichs. POSEIDON: Privacy-Preserving Federated Neural Network Learning.
ePrint 2021/1025

[MBH23] Mouchet, Boudgoust, Huguenin. Efficient Access Structures for Threshold RLWE-based FHE.
ePrint 2023/448

[CCK23] Cheon, Choi, Kim. Improved Universal Thresholdizer.
ePrint 2023/1223

🆕 New (2024–2025) Core ThFHE Schemes
Latest research advancing the efficiency and scalability of Threshold FHE.

Passelègue & Stehlé (2024). Low Communication Threshold Fully Homomorphic Encryption.
ePrint 2024/1984

Chang & Li (2025). Arbitrary‑Threshold FHE with Lower Complexity.
ePrint 2025/084

Okada & Takagi (2025). Low Communication ThFHE from Standard (Module‑)LWE.
ePrint 2025/409

⚙️ Building Blocks: From FHE to ThFHE
Supporting components such as keygen, scheme-switching, bootstrapping.

[CLO+13] Choudhury, Lepoint, Orlandi, Paillier, Vergnaud. Optimizing FHE for MPC.
ePrint 2013/229

[GGP+23] Geva, Gentry, Polychroniadou, Raykova, Sahai, Wichs, Zaverucha. Multi-Party Homomorphic Encryption for Secure Collaborative Cancer Research.
ePrint 2023/467

[MW16] Mukherjee & Wichs. Two Round Multiparty Computation via Multi-Key FHE.
ePrint 2015/344

[DS16] Ducas & Stehlé. Sanitization of FHE ciphertexts.
ePrint 2015/624

🔒 Passive Security in ThFHE
Security under honest-but-curious adversaries.

[LM21] Li & Micciancio. On the Security of Approximate Homomorphic Encryption.
ePrint 2021/153

[LMSS22] Li, Micciancio, Sorrell, Sorrell. Differentially Private Secure Aggregation with CKKS.
ePrint 2022/1231

[AV21] Akavia & Vald. On the Privacy of CPA-Secure Homomorphic Encryption.
ePrint 2021/1376

[KS23] Kluczniak & Santato. Circuit-Private Multi-Key and Threshold FHE.
ePrint 2023/346

[BS23] Boudgoust & Scholl. Simple Threshold FHE from LWE.
ePrint 2023/003

🛡️ Active Security in ThFHE
Security against malicious adversaries, including zero-knowledge and simulation-based models.

[ABGS22] Aranha, Boudgoust, Gjøsteen, Scholl. Verifiable Mix-Nets for Threshold Cryptography.
ePrint 2022/1251

[CMS+23] Chatel, Mouchet, Sav, Scholl. PELTA: Maliciously Secure Multi-Party Homomorphic Encryption.
ePrint 2023/200

[DDE+23] Dahl, Damgård, Escudero, Fagerberg, Frederiksen, Gjøsteen, Huguenin, Mouchet, Scholl. Noah’s Ark: Efficient Threshold FHE via Noise Flooding.
ePrint 2023/168

[VKH23] Viand, Krenn, Hanzlik. Verifiable FHE.
ePrint 2023/070

[KPR18] Keller, Pastro, Rotaru. SPDZ2k: Efficient MPC mod 2^k for Dishonest Majority.
ePrint 2018/482

🔁 Thresholdizing Lattice-Based PKE
Adapting PKE schemes for distributed decryption and key generation.

[BGGK17] Boneh, Gentry, Gorbunov, Halevi, Ishai, Sahai, Waters. Thresholdizing Lattice-Based Encryption Schemes.
ePrint 2017/1013

[CS19] Cozzo & Smart. Threshold Post-Quantum Signatures.
ePrint 2019/1116

[KLO+19] Kraitsberg, Lepoint, Orlandi, Polychroniadou, Raykova, Smart, Wichs. Distributed Key Generation and Threshold Decryption for Lattice-Based Cryptosystems.
ePrint 2019/692

[DLN+21] Devevey, Lepoint, Nguyen, Orlandi, Paillier, Vergnaud. Non-Interactive CCA2-Secure Threshold Cryptosystems.
ePrint 2020/1274

[ASY22] Agrawal, Shah, Yuen. Round-Optimal Threshold Lattice Signatures.
ePrint 2022/634

[GKS23] Gur, Katz, Shmueli. Threshold Lattice Signatures from Threshold FHE.
ePrint 2023/1090

[CCMS21] Cong, Chen, Ma, Shi. Gladius: Hybrid PKE with Distributed Decryption.
ePrint 2021/1416

🧪 Circuit & Functional Privacy
Research on input/function hiding, malleability, and privacy relaxations.

[BdPMW16] Bourse, de Panafieu, Minelli, Pointcheval, Wichs. Circuit Privacy Almost for Free.
ePrint 2016/392

[OPCPC14] Ostrovsky, Persiano, Catalano, Puglisi, Catalano. Malicious Circuit-Private FHE.
ePrint 2014/786

[BSW11] Boneh, Sahai, Waters. Targeted Malleability in Cryptography.
ePrint 2010/365

📖 Foundational HE Works
Must-read general papers for understanding underlying FHE schemes.

[Gen09] Craig Gentry. Fully Homomorphic Encryption Using Ideal Lattices (PhD Thesis).
PDF

[Bra12] Brakerski. Fully Homomorphic Encryption from Classical GapSVP.
ePrint 2012/078

[FV12] Fan & Vercauteren. Somewhat Practical Fully Homomorphic Encryption.
ePrint 2012/144

[GHS13] Gentry, Halevi, Sahai. Homomorphic Encryption from Learning with Errors: Conceptually-Simpler, Asymptotically-Faster, Attribute-Based.
ePrint 2013/340

[BGV14] Brakerski, Gentry, Vaikuntanathan. (Leveled) Fully Homomorphic Encryption without Bootstrapping.
ePrint 2011/277

[DM15] Ducas & Micciancio. FHEW: Bootstrapping Homomorphic Encryption in Less Than a Second.
ePrint 2014/816

[CKKS17] Cheon, Kim, Kim, Song. Homomorphic Encryption for Arithmetic of Approximate Numbers.
ePrint 2016/421

📬 Contributing
If you know of any recent or classic paper on ThFHE (construction, optimization, attack, implementation), feel free to open a PR! Contributions are very welcome 🚀

📘 License
This project is licensed under the MIT License

---

## 📘 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).