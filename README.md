# 🔐 Awesome Threshold FHE (ThFHE)

> A curated list of foundational and advanced research papers on **Threshold Fully Homomorphic Encryption**, inspired by [Andreea Alexandru’s MPTS 2023 talk](https://csrc.nist.gov/csrc/media/Presentations/2023/mpts2023-day3-talk-fhe-blocks/images-media/mpts2023-3c1-slides--andreea--threshold-FHE-blocks.pdf).

Threshold FHE allows multiple parties to collaboratively perform fully homomorphic encryption operations — including joint key generation, distributed evaluation, and threshold decryption — while maintaining cryptographic security even under passive or active adversarial models.

---

## 🧱 Core Threshold FHE Schemes

> Papers that directly propose threshold FHE schemes.

- [BD10] Bendlin & Damgård. *Threshold decryption and ZK proofs for lattice-based crypto*. [TCC 2010](https://eprint.iacr.org/2009/391.pdf)
- [AJL+12] Asharov et al. *Multiparty Computation with Low Communication,
Computation and Interaction via Threshold FHE
*. [EUROCRYPT 2012](https://eprint.iacr.org/2011/613.pdf)
- [LATV12] López-Alt et al. *On-the-Fly Multiparty Computation on the Cloud via Multikey Fully Homomorphic Encryption*. [STOC 2012](https://eprint.iacr.org/2013/094)
- [BGG+18] Boneh et al. *Threshold cryptosystems from threshold fully homomorphic encryption*. [CRYPTO 2018](https://eprint.iacr.org/2017/956.pdf)
- [CCS19] Chen et al. *Multi-Key Homomophic Encryption from TFHE*. [ASIACRYPT 2019](https://eprint.iacr.org/2019/116.pdf)
- [SPT+21] Sav et al. *POSEIDON: Federated learning with MPHE*. [NDSS 2021](https://arxiv.org/abs/2104.10295)
- [MBH23] Mouchet et al. *An Efficient Threshold Access-Structure for RLWE-Based Multiparty Homomorphic Encryption*. [Journal of Cryptology](https://eprint.iacr.org/2022/780)
- [CCK23] Cheon et al. *Improved Universal Thresholdizer from Iterative Shamir Secret Sharing*. [ePrint 2023/1223](https://eprint.iacr.org/2023/1223)

---

## 🛡️ Security Notions for Threshold Public Key Encryption

- [FPS01] Fouque et al., Poupard, G. and Stern, J., 2001. *Sharing decryption in the context of voting or lotteries*. [Financial Cryptography 2000](https://www.di.ens.fr/~stern/data/St85.pdf)

---

## ⚙️ Building Blocks: From Lattice Based PKE  to Threshold PKE 

> Not trivial to thresholdize existing lattice-based PKE schemes to their threshold variants

- [BGGK17] Boneh et al. *A Lattice-Based Universal Thresholdizer for Cryptographic Systems*. [Cryptology ePrint Archive.](https://eprint.iacr.org/2017/251.pdf)
- [BGG+18] Boneh et al. *Threshold cryptosystems from threshold fully homomorphic encryption*. [CRYPTO 2018](https://eprint.iacr.org/2017/956.pdf)
- [CS19] Daniele Cozzo and Nigel P. smart. *Sharing the LUOV: Threshold Post-Quantum Signatures*. [IMA International Conference on Cryptography and Coding](https://eprint.iacr.org/2019/1060)
- [KLO+19] Kraitsberg et al. *Adding distributed decryption and key generation to a ring-LWE based CCA encryption scheme*. [ACISP 2019](https://eprint.iacr.org/2018/1034.pdf)
- [DLN+21] Devevey et al. *Non-interactive CCA2-secure threshold cryptosystems: achieving adaptive security in the standard model without
pairings.*. [IACR International Conference on Public-Key Cryptography](https://eprint.iacr.org/2021/630)
- [CCMS21] Cong et al. Gladius: *LWR based efficient hybrid public key encryption with distributed decryption*. [International Conference on the Theory
and Application of Cryptology and Information Security](https://www.iacr.org/archive/asiacrypt2021/130900030/130900030.pdf)
- [CHI+21] Cong et al. *Diogenes: Lightweight scalable RSA modulus generation
with a dishonest majority*. [2021 IEEE Symposium on Security and Privacy](https://eprint.iacr.org/2020/374)
- [BTT+22] Boschini et al. *MuSig-L: Lattice-Based Multi-Signature With Single-Round Online Phase*. [Annual International Cryptology Conference](https://eprint.iacr.org/2022/1036)
- [ASY22] Agrawal et al.  *Round-optimal lattice-based threshold signatures. revisited*. [Cryptology ePrint Archive](https://eprint.iacr.org/2022/6346)
- [GKS23] Gur et al.  *Two-Round Threshold Lattice Signatures from Threshold Homomorphic Encryption*. [Cryptology ePrint Archive](https://eprint.iacr.org/2023/1318)

---

## ⚙️ Smudging/Noise Flooding

- [MW16] Mukherjee & Wichs. *2-Round MPC via Multikey FHE*. [EUROCRYPT 2016](https://eprint.iacr.org/2015/345.pdf)
- [DS16] Ducas & Stehlé. *Sanitization of FHE ciphertexts*. [EUROCRYPT 2016](https://eprint.iacr.org/2016/164.pdf)

---

## 📖 Foundational HE Works

> Must-read general papers for understanding underlying FHE schemes.

- [Gen09] Craig Gentry. *FHE PhD Thesis*. [PDF](https://crypto.stanford.edu/craig/craig-thesis.pdf)
- [Bra12] Brakerski. *Fully Homomorphic Encryption without Modulus Switching
from Classical GapSVP
*. [CRYPTO 2012](https://eprint.iacr.org/2012/078.pdf)
- [FV12] Fan & Vercauteren. *Somewhat practical FHE*. [ePrint 2012/144](https://eprint.iacr.org/2012/144)
- [GHS13] Gentry et al. *Homomorphic Encryption from Learning with Errors:
Conceptually-Simpler, Asymptotically-Faster, Attribute-Based*. [CRYPTO 2013](https://eprint.iacr.org/2013/340.pdf)
- [BGV14] Brakerski et al. *Fully Homomorphic Encryption without Bootstrapping*. [TOCT](https://eprint.iacr.org/2011/277.pdf)
- [DM15] FHEW: Bootstrapping Homomorphic Encryption in less than a second*. [EUROCRYPT 2015](https://eprint.iacr.org/2016/870)
- [CKKS17] Cheon et al. *Homomorphic Encryption
for Arithmetic of Approximate Numbers*. [ASIACRYPT 2017](https://eprint.iacr.org/2016/421.pdf)

---

## 🔒 Passive Security notions for FHE

> Security under honest-but-curious adversaries.

>IND-CPAD Security

- [LM21] Li & Micciancio. *On the security of homomorphic encryption on approximate numbers*. [EUROCRYPT 2021](https://eprint.iacr.org/2020/1533.pdf)
- [LMSS22] Li et al. *Securing approximate homomorphic encryption using differential privacy*. [Annual International Cryptology Conference 2022](https://eprint.iacr.org/2022/816)

>Circuit privacy: oracle access to “encrypt-evaluate-decrypt” 

- [Gen09] Craig Gentry. *FHE PhD Thesis*. [PDF](https://crypto.stanford.edu/craig/craig-thesis.pdf)
- [OPCPC14] Ostrovsky et al. *Maliciously Circuit-Private FHE*. [Annual Cryptology Conference](https://eprint.iacr.org/2013/307.pdf)
- [BdPMW16]  Bourse et al. *FHE Circuit Privacy Almost For Free*. [Annual Cryptology Conference](https://eprint.iacr.org/2016/381.pdf)
- [KS23]  Kluczniak et al. *On Circuit Private, Multikey and Threshold Approximate Homomorphic Encryption*. [Cryptology ePrint Archive](https://eprint.iacr.org/2023/301)

>funcCPA: oracle access for “decrypt-evaluate-encrypt”

- [AV21]  Adi Akavia and Margarita Vald. *On the privacy of protocols based on CPA-secure homomorphic encryption*. [Cryptology ePrint Archive](https://eprint.iacr.org/2021/803)
- [AGHV22]  Adi Akavia et al. *Achievable CCA2 relaxation for homomorphic encryption*. [Cryptology ePrint Archive](https://eprint.iacr.org/2022/282)

---

## 🔒 Active Security notions for FHE

> Security against malicious adversaries, including zero-knowledge and simulation-based models.

> IND-CCA1

- [CRRV17]  Canetti et al. *Chosen-ciphertext secure fully homomorphic encryption*. [IACR IWPKC](https://www.iacr.org/archive/pkc2017/101750203/101750203.pdf)

> Targeted Malleability: allow decryptions of some function families

- [BSW11]  Boneh et al. *Targeted malleability: homomorphic encryption for restricted computations*. [Proceedings of the  3rd Innovations in Theoretical Computer
Science Conference](https://eprint.iacr.org/2011/311)

>IND-CVA:  oracle access for plaintext validity

- [LMNV10]
- [CGG16]
- [CCCM22]
- [CCCM23]

>Malicious security: 

- [VKH23]

>IND-TCPA + threshold verifiability + decryption simulatability

- [BGG+18]
- [ABGS22]

>Real/ideal functionality with active security

- [DDE+23]
- [Sma23]

## 🔒 Standardizing active ThFHE

>Threshold additively/somewhat HE, FHE with active security

- [DKL+13] 
- [KPR18]
- [RST+22]
- [ABGS22]
- [CMS+23]
- [DDE+23]

---

## 📬 Contributing

If you know of any recent or classic paper on ThFHE (construction, optimization, attack, implementation), feel free to open a PR! Contributions are very welcome 🚀

---

## 📘 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).