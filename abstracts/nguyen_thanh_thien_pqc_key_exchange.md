# Key Exchange Mechanisms Using Post-Quantum Algorithms in Opportunistic Environments  
**Author:** Thanh Thien Nguyen  
**Year:** 2025  
**Supervisor:** Samaneh Rashidibajgan

---

## Abstract

The emergence of quantum computing has been a increasingly considerable risk to ITSecurity
generally and classical cryptographic schemes, particularly. This topic become
more and more relevant when Microsoft announced Majorana 1, which is designed to
scale up to one millions qubits. Adversaries equipped with sufficient large quantum system
like that will be able to leverage algorithms, such as Shor’s or Grover algorithm,
effortlessly attack current key exchange mechanisms like RSA, Diffie-Hellman, and Elliptic
Curve Diffie-Hellman. This vulnerability is particularly critical in delay-tolerant and
opportunistic network, where devices and nodes must exchange sensitive data over intermittent
and infrastructure-less connections.

To guarantee long-term security in these challenged environments, post-quantum cryptography
(PQC) presents a promising way to go. This work analyzes the design and
evaluates quantum-resistant key exchange protocol tailored for resource-constraint opportunistic
environments. Leveraging lattice-based constructions, we implement a Learning
With Errors (LWE) - based Key Exchange Mechanism (KEM) to establish secure
session keys between nodes during brief contact windows. Aiming to enhance further
integrity, we propose a lightweight authentication scheme that combines Dithilium signature
scheme and a binary-noise variant of Ring-LWE, so called Ring-BinLWE, reducing
the computational overhead but still preserving security guarantees.

We integrate these cryptographic mechanisms into typical Delay-Tolerant routing protocols
such as Epidemic, PRoPHET, and Spray-and-Wait, and evaluate their performance
within simulated opportunistic scenarios using The ONE simulator. Our analysis demonstrates
the feasibility of deploying post-quantum security primitives in highly dynamic,
resource-constrained environments, providing a foundation for future-proof secure communication
in mobile, ad hoc, and infrastructure-less networks.
---

## Keywords
Post-Quantum Cryptography, LWE, Ring-LWE, Dilithium, Opportunistic Networks, Delay-Tolerant Networking, Key Exchange Mechanisms, Quantum Security
