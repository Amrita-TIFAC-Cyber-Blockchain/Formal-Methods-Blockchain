# Formal Methods and Verification of Blockchain Consensus and Smart Contracts ![](https://img.shields.io/badge/-Live-brightgreen)
![](https://img.shields.io/badge/Batch-Ph.D-green) <br/>
![](https://img.shields.io/badge/Focus-Blockchain-yellow) ![](https://img.shields.io/badge/Focus-Smart_Contracts-yellow) ![](https://img.shields.io/badge/Focus-Languages-yellow) ![](https://img.shields.io/badge/Focus-DASP-yellow) ![](https://img.shields.io/badge/Focus-SWC-yellow) <br/>
![](https://img.shields.io/badge/Blockchain-Bitcoin-blue) ![](https://img.shields.io/badge/Blockchain-Ethereum-blue) ![](https://img.shields.io/badge/Blockchain-Hyperledger-blue) ![](https://img.shields.io/badge/Blockchain-EOS-blue) ![](https://img.shields.io/badge/Blockchain-Cardano-blue) ![](https://img.shields.io/badge/Blockchain-Solana-blue) ![](https://img.shields.io/badge/Blockchain-Tezos-blue) <br/>
![](https://img.shields.io/badge/FM-Model_Checking-purple) ![](https://img.shields.io/badge/FM-Theorem_Proving-purple) ![](https://img.shields.io/badge/FM-Symbolic_Concolic_Execution-purple) ![](https://img.shields.io/badge/FM-Program_Verification-purple) ![](https://img.shields.io/badge/FM-Run_Time_Verification-purple)

## PhD Thesis and Conferences
 - [Stefano Lande - Formal Methods for Secure Bitcoin Smart Contracts - Universita degli Studi di Cagliari](Assets/Thesis/PhD_Formal_Methods_for_Secure_Bitcoin.pdf)
 - **Workshop on Formal Methods for Blockchains**
   - [2020 - Formal Specification and Model Checking of the Tendermint Blockchain Synchronization Protocol](https://ramagururadhakrishnan.github.io/Blockchain-Papers/Formal_Methods/Formal_Specification_and_Model_Checking_of_the_Tendermint_Blockchain_Synchronization_Protocol.pdf)
   - [2019](https://ramagururadhakrishnan.github.io/Blockchain-Papers/Formal_Methods/Proceedings_Formal_Methods_for_Blockchains.pdf)
  

## Organisations
 - [SECBIT Labs](https://secbit.io/about.html)
    - [Token Libraries with Proofs](https://github.com/sec-bit/tokenlibs-with-proofs)
    - [Formal Verification for Decentralized Exchange](https://github.com/sec-bit/loopring-protocol2-verification)
    - [Security Audit for the First zkRollup DEX Protocol](https://github.com/Loopring/protocols/tree/d528ab83c9934a4d54e4a3ceefa20ba7908ebe25/packages/loopring_v3/security_audit)
    
## Literature Survey
[Click Here](https://ramagururadhakrishnan.github.io/Blockchain-Papers/Formal_Methods/) to view.

## Model Formalisms, Specification and Verification

### Model Formalisms
#### Contract-Level Models
 - **Process Algebra**
   - [λ-Calculus](https://jacksongl.github.io/files/demo/lambda/index.htm)
   - [𝜋-calculus]()
   - [𝜌-calculus]()
 - **State-Transition**
   - [Behavior-Interaction Priority (BIP)]()
   - [PetriNets]()
 - **Set-Based Methods**
   - [Event-B]()
   - [TLA+]()
 
#### Program-Level Models
 - **AST-Level**
 - **Control Flow Graph** 
   - Ethainter
   - Securify
   - Vandal
   - Oyente
   - Mythril
   - Manticore
   - Annotary
   - SmartScopy
 - **Program Logic** 

### Specification Logic
 - Temporal Logic 
   - Linear Temporal Logic
   - Computation Tree Logic
 - Dynamic Logic
 - Deontic and Defeasible Logics
 - Defeasible logic
 - Hoare-Style Properties
 - Program Path-Level Patterns
 
### Verification Technique 

| Verification | Tools | 
|:------------:|:-----:|
| **Model Checking** | [NuSMV, nuXmv](https://nusmv.fbk.eu/)  <br/> [SPIN](https://spinroot.com/spin/whatispin.html)  <br/> [CPN](https://cpntools.org/) <br/> [BIP-SMC](http://www-verimag.imag.fr/Statistical-Model-Checking.html) <br/> [PRISM](https://www.prismmodelchecker.org/)  <br/> [UPPAAL](https://uppaal.org/) <br/> MCK <br/> [Maude](http://maude.cs.illinois.edu/tools/lmc/)  <br/> [FDR](https://cocotec.io/fdr/)  <br/> Ambient Calculus  <br/> LDLf |
| **Theorem Proving** | [Coq](https://coq.inria.fr/) <br/> [Isabelle/HOL](https://isabelle.in.tum.de/) <br/> [Agda](https://plfa.inf.ed.ac.uk/) | 
| **Program Verification** | [Datalog & Soufflé](https://souffle-lang.github.io/) <br/> [Boogie Verifier & Corral](https://github.com/boogie-org/corral)  <br/> [LLVM & SMACK](https://github.com/smackers/smack) <br/> [SeaHorn](https://seahorn.github.io/) <br/> [F*](https://www.fstar-lang.org/)  <br/> [KeY](https://www.key-project.org/)  <br/> [Why3](https://why3.lri.fr/)  <br/> [K framework](https://kframework.org/) <br/> Custom static analyses <br/> | 
| **Symbolic & Concolic Execution** | [Oyente](https://oyente.tech/) <br/> [Mythril](https://github.com/ConsenSys/mythril)  <br/> teEther <br/> [Maian](https://github.com/ivicanikolicsg/MAIAN)  <br/> [Manticore](https://github.com/trailofbits/manticore) |
| **Runtime Verification & Testing** | [ContractLarva](https://github.com/gordonpace/contractLarva) <br/> EVM* <br/> [ReGuard](https://ieeexplore.ieee.org/document/8449446) <br/> SODA <br/> [Solythesis](https://github.com/aoli-al/Solythesis) <br/> [ECFChecker](https://github.com/shellygr/ECFChecker) <br/> |
  
## Languages 

| Bitcoin | Ethereum | Hyperledger |
|:-------:|:--------:|:-----------:|
|  BitML  | Solidity <br/> Vyper  <br/> Yul <br/> FE <br/> [Bamboo](https://github.com/cornellblockchain/bamboo) | Go <br/> [Obsidian](https://obsidian-lang.com/) |

| Cardano | Solana | Libra/Calibra | Tezos | RChain | Aeternity | Stratis | Aergo |
|:-------:|:------:|:-------------:|:-----:|:------:|:---------:|:-------:|:-----:|
| Marlowe <br/> Plutus | Rust <br/> C | Move | Michelson | Rholang | Sophia | C# | Lua <br/> SCL |
  
## Formal Verified Blockchain Ecosystem
 - [KEVEM]() - K Semantics of the Ethereum Virtual Machine 

## References
 - [Research Publications and Thesis](https://github.com/ramagururadhakrishnan/Blockchain-Papers/tree/main/Formal_Methods)
 - [Smart Contracts Weakness Classification Registry (SWC)](https://swcregistry.io/)
 - [Smart Contracts Testcases for Solidity](https://github.com/SmartContractSecurity/SWC-registry/tree/master/test_cases/solidity)
