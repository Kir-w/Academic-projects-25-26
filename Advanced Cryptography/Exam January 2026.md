## Quiz

#### 1. Which of the following is true?
   
A One-wayness does not imply collision-resistance, and vice versa.

B Every collision-resistant hash function is a one-way function, but the opposite is false.

C Every one-way function is a collision-resistant hash function, but the opposite is false.

D A function is one-way if and only if it is collision-resistant.

<details>
<summary>Answer</summary>

`A`

</details>

#### 2. Let Π = (Gen, Enc, Dec) be a public-key encryption scheme. Which of the following is true?

A If Enc is deterministic, then Π is not CPA-secure.

B If Enc is deterministic, then Π is CPA-secure.

C If Dec is deterministic, then Π is not CPA-secure.

D If Dec is deterministic, then Π is CPA-secure.

<details>
<summary>Answer</summary>

`A`

</details>

#### 3. Suppose that a secret-sharing scheme achieves perfect security. Which of the following is true?

A The sum of the sizes of all the shares must be equal to the size of the secret.

B The sum of the sizes of all the shares must be less than the size of the secret.

C The size of each share must be less than the size of the secret.

D The size of each share must be greater than or equal to the size of the secret.

<details>
<summary>Answer</summary>

`D`

</details>

#### 4. In the definition of zero-knowledge proof of knowledge, the concept of “extractor” is needed to guarantee that:

A a honest prover always succeeds;

B a honest verifier always succeeds;

C for the prover, cheating is at least as difficult as computing a witness;

D the verifier learns nothing about the secret witness.

<details>
<summary>Answer</summary>

`C`

</details>

#### 5. The Fiat–Shamir transform makes possible to:

A convert a secure identification scheme to a secure signature scheme, if the hash function is modeled as a random oracle;

B convert a secure signature scheme to a secure identification scheme, if the hash function is modeled as a random oracle;

C convert a secure identification scheme to a secure signature scheme, if the hash function is collisionresistant;

D convert a secure signature scheme to a secure identification scheme, if the hash function is collisionresistant;

<details>
<summary>Answer</summary>

`A`

</details>

#### 6. A multi-party computation protocol in the public-output setting is secure against a honest-but-curious adversary if there exists a simulator that,

A using only the secret inputs of the corrupt parties and the output of the protocol, simulates the views of the corrupt parties;

B using only the secret inputs of the honest parties and the output of the protocol, simulates the views of the corrupt parties;

C using only the secret inputs of the honest parties and the output of the protocol, simulates the views of the honest parties;

D using only the secret inputs of the corrupt parties and the output of the protocol, simulates the views of the corrupt parties;

<details>
<summary>Answer</summary>

`A`

</details>


## Question 1

1. Explain the Fiat-Shamir Transform.

2. Explain what we know about the security of the Fiat-Shamir Transform.
   
3. Given the following identification scheme, explain how to apply the Fiat–Shamir transform.

<img width="257" height="124" alt="image" src="https://github.com/user-attachments/assets/bb5acd12-0781-4f5d-a86a-6ffec325c4bf" />

(Provide the signing and verification algorithms of the digital signature.)

<details>
<summary>Answer</summary>

1. From identification to signature scheme. Instead of ch random in C, H(com,ch)=ch, with H hash function modeled as a random oracle.

2. Since ch is taken as random, proba to have the correct value is negligible...

3. Sign_sk(m):

...

Verifiy_pk(sigma, m):

...


</details>

## Question 2

Let G be a finite multiplicative group of prime order p with generator g, and let x ∈ G be
publicly known. The following Σ-protocol allows a prover to convince a verifier that the prover knows
w ∈ Zp such that x = g^w.

<img width="263" height="158" alt="image" src="https://github.com/user-attachments/assets/ea8f3e28-704d-49c2-857a-640412d59397" />

Show that this Σ-protocol does indeed satisfy the properties of completeness, (special) soundness, and
zero-knowledge.


<details>
<summary>Answer</summary>

[to be completed] 


</details>
