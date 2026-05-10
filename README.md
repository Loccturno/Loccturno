# loccturno

Solo learner working toward a freelance career in **ZK & smart contract auditing**.

By day, I operate forklifts in a steel wholesale warehouse in Crete.  
By night, I read circuits, hunt bugs, and write audit reports.

## Origin

In 2003, when I was 13, I read Simon Singh's *The Code Book*. I drew a 
Vigenère tableau and taped it to my closet door, and went around telling 
anyone who would listen — teachers, friends, parents — that cryptography 
was essential for human freedom, privacy, and the survival of the human 
spirit.

The grown-ups told me to focus on schoolwork.

Twenty-three years later, by complete coincidence, a friend gave me the 
same book as a gift. I had forgotten the title; opening it brought back 
the closet door, the cipher tableau, the convictions. By that point I 
had already been a Bitcoiner for four years.

The career change wasn't a decision. It was a recognition.

## Currently learning

- **Solidity** — writing contracts from scratch, reading auditing reports, breaking my own code
- **Circom + ZK circuits** — Poseidon, Merkle membership proofs, nullifiers, underconstrained-signal patterns
- **Smart contract auditing** — severity classification, professional report writing, hands-on exploit reproduction
- **DeFi attack vectors** — reentrancy (single-function, cross-function, read-only), oracle manipulation, approval phishing, governance attacks

## Featured projects

### [lending-protocol-audit](https://github.com/Loccturno/lending-protocol-audit)
Full end-to-end audit project. Vulnerable lending protocol with uncollateralized 
borrowing exploit, hands-on PoC with transaction hashes from Remix VM, fixed 
version, and a professional audit report (Severity / Description / Impact / Fix). 
My first complete portfolio piece.

### [reentrancy-classic-vault](https://github.com/Loccturno/reentrancy-classic-vault)
Hands-on reentrancy lab recreating the DAO-style bug. Vulnerable `EtherVault`, 
working `Attacker` contract that drains it, fixed version with CEI ordering + 
ReentrancyGuard, plus a 12-step state-by-state attack walkthrough.

### [approval-phishing-analysis](https://github.com/Loccturno/approval-phishing-analysis)
Breakdown of an approval phishing scam token pattern observed in the wild. 
What the contract does, how the drain works, and why revoking approvals 
matters more than people think.

### [tax-manipulation-scam-analysis](https://github.com/Loccturno/tax-manipulation-scam-analysis)
The "tax sandwich" front-running pattern in ERC20 tokens, plus a tour of 
unrestricted owner privileges that turn legitimate-looking projects into 
rug pulls.

More in the repository list below ↓

## Tech stack

`Solidity` · `Circom` · `JavaScript` · `Remix` · `Git` · `MetaMask`  
**ZK concepts**: SNARKs, Groth16 verifiers, Poseidon, Merkle trees, nullifiers  
**On-chain analysis**: Etherscan deep dives, transaction tracing, scam pattern recognition

## Reading

**Read**
- *The Code Book* — Simon Singh (the one that started it all, twice)
- *Fermat's Last Theorem* — Simon Singh
- *Ghost in the Wires* — Kevin Mitnick

**Currently reading**
- *Quantum Theory Cannot Hurt You* — Marcus Chown
- *Sandworm* — Andy Greenberg
- *Future Crimes* — Marc Goodman
- *Mastering Ethereum* — Andreas Antonopoulos

**In queue**
- *Dark Wire* — Joseph Cox
- *Ctrl+Alt+Chaos* — Joe Tidy
- *Handsome Devil* — Jeff Maysh
- *Aggressive Network Self-Defense* — Neil Wyler

## Contact

- **Email**: loccturno@protonmail.com
- **Open to**: ZK circuit audits, smart contract audits, paid learning collaborations, mentorship from senior auditors

---

*Crete, Greece. Pseudonymous by choice. Started writing code in early 2026 — building toward auditor work the long way: deeply, openly, one bug at a time.*
