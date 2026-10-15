# Department of Computer Science and Engineering, Jagannath University
## M.Sc. in CSE Professional Program Mid-Term Examination-2026 (17B)
**Course Code:** CSE-5310  
**Course Title:** Internet Security and Policy  
**Time:** 1:00 hour  
**Total Points:** 20  

*[Answer the following questions]*

---

### Question 1
**(a)** Write down the functions of the following protocols: **[03 points]**
1. ARP  
2. ICMP  
3. TCP  

**(b)** What is key-logging attacks? Differ SYN-flooding and TCP hijacking with examples. **[03 points]**

**(c)** Define intrusion/anomaly detection. How can intruder be harmful to our daily digital life? **[02 points]**

**(d)** How the round-key is related to the operations of any single round of DES? Explain with proper example. **[02 points]**

---

### Question 2
**(a)** Convert the right 32 bits of 1st round input into proper expanded form so that the value can be properly operated with respected round key generated from key generation process of DES.  
*Right 32 bits of 1st round input = in hexadecimal form `A6AB27??`*, Where `'??'` will be replaced with last 2 digits of your ID in Jagannath University CSE Department. **[2.5 points]**

**(b)** How initial permutation (IP) and final permutation (FP) computed with permutation key? Explain with examples of IP table/FP table and some provision value as the value for encryption. **[2.5 points]**

**(c)** Compute data state using your last name as given in your certificate then do the sub-byte operation of a single round of AES algorithm using given sub-byte table below. **[03 points]**

**(d)** How temporary word was calculated in AES word expansion for key? How word expansion computed to generate keys in AES? **[02 points]**

---

### Sub-byte Table for Fig. 2(c)

|   | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | a | b | c | d | e | f |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **0** | 63 | 7c | 77 | 7b | f2 | 6b | 6f | c5 | 30 | 01 | 67 | 2b | fe | d7 | ab | 76 |
| **1** | ca | 82 | c9 | 7d | fa | 59 | 47 | f0 | ad | d4 | a2 | af | 9c | a4 | 72 | c0 |
| **2** | b7 | fd | 93 | 26 | 36 | 3f | f7 | cc | 34 | a5 | e5 | f1 | 71 | d8 | 31 | 15 |
| **3** | 04 | c7 | 23 | c3 | 18 | 96 | 05 | 9a | 07 | 12 | 80 | e2 | eb | 27 | b2 | 75 |
| **4** | 09 | 83 | 2c | 1a | 1b | 6e | 5a | a0 | 52 | 3b | d6 | b3 | 29 | e3 | 2f | 84 |
| **5** | 53 | d1 | 00 | ed | 20 | fc | b1 | 5b | 6a | cb | be | 39 | 4a | 4c | 58 | cf |
| **6** | d0 | ef | aa | fb | 43 | 4d | 33 | 85 | 45 | f9 | 02 | 7f | 50 | 3c | 9f | a8 |
| **7** | 51 | a3 | 40 | 8f | 92 | 9d | 38 | f5 | bc | b6 | da | 21 | 10 | ff | f3 | d2 |
| **8** | cd | 0c | 13 | ec | 5f | 97 | 44 | 17 | c4 | a7 | 7e | 3d | 64 | 5d | 19 | 73 |
| **9** | 60 | 81 | 4f | dc | 22 | 2a | 90 | 88 | 46 | ee | b8 | 14 | de | 5e | 0b | db |
| **a** | e0 | 32 | 3a | 0a | 49 | 06 | 24 | 5c | c2 | d3 | ac | 62 | 91 | 95 | e4 | 79 |
| **b** | e7 | c8 | 37 | 6d | 8d | d5 | 4e | a9 | 6c | 56 | f4 | ea | 65 | 7a | ae | 08 |
| **c** | ba | 78 | 25 | 2e | 1c | a6 | b4 | c6 | e8 | dd | 74 | 1f | 4b | bd | 8b | 8a |
| **d** | 70 | 3e | b5 | 66 | 48 | 03 | f6 | 0e | 61 | 35 | 57 | b9 | 86 | c1 | 1d | 9e |
| **e** | e1 | f8 | 98 | 11 | 69 | d9 | 8e | 94 | 9b | 1e | 87 | e9 | ce | 55 | 28 | df |
| **f** | 8c | a1 | 89 | 0d | bf | e6 | 42 | 68 | 41 | 99 | 2d | 0f | b0 | 54 | bb | 16 |
---

## Part 1: Mid-Term Examination-2026 (17B)
**Course Code:** CSE-5310, **Course Title:** Internet Security and Policy 
**Time:** 1:00 hour, **Total Points:** 20

### 1.(a) Write down the functions of the following protocols. (03 points)
* **ARP (Address Resolution Protocol):** Resolves an IPv4 address to a physical MAC address on a local area network so that data frames can be delivered correctly to the target network interface card.
* **ICMP (Internet Control Message Protocol):** Reports errors and provides network diagnostic information, such as destination unreachable or echo request and reply messages, to help manage network traffic and troubleshoot connectivity.
* **TCP (Transmission Control Protocol):** Provides reliable, connection-oriented, ordered, and error-checked delivery of a stream of bytes between applications running on hosts communicating via an IP network.

### 1.(b) What is key-logging attacks? Differ SYN-flooding and TCP hijacking with examples. (03 points)
* **Key-logging attack:** A monitoring form of malware or hardware device that records every keystroke a user types on a keyboard, often capturing credentials, sensitive messages, and personal data without authorization.
* **SYN-flooding vs. TCP hijacking:**
  * **SYN-flooding:** A denial of service attack where an attacker sends a high volume of TCP SYN requests to a server, exhausting its resources by leaving half-open connections pending because the final ACK is never sent. Example: Flooding a web server with fake connection requests until legitimate users cannot connect.
  * **TCP hijacking:** An attack where an unauthorized user takes over an active communication session between two trusted hosts by guessing or intercepting the current sequence and acknowledgement numbers. Example: Intercepting an ongoing telnet or web session after authentication and injecting unauthorized commands.

### 1.(c) Define intrusion/anomaly detection. How can intruder be harmful to our daily digital life? (02 points)
* **Intrusion/Anomaly Detection:** A security mechanism that monitors network traffic or system activities for abnormal patterns, policy violations, or malicious signatures that deviate from established normal baseline behavior.
* **Harm to digital life:** Intruders can steal sensitive personal data, compromise financial accounts, corrupt critical files, deploy ransomware, or use infected devices as nodes in a botnet for wider cyber attacks, leading to financial loss, identity theft, and privacy invasion.

### 1.(d) How the round-key is related to the operations of any single round of DES? Explain with proper example. (02 points)
* In each round of the Data Encryption Standard (DES), the 48-bit round key is combined with the 48-bit expanded right-half data block using a bitwise XOR operation. This output is passed through eight substitution boxes to introduce confusion before further permutation. Example: If the expanded data block is XORed with Round Key $K_1$, the resulting 32-bit output dictates the substitution outcomes that alter the message bits for that specific round.

### 2.(a) Convert the right 32 bits of 1st round input into proper expanded from so that the value can be properly operated with respected round key generated from key generation process of DES. (2.5 points)
* **Given:** Right 32 bits of 1st round input = `A6AB27??` (where `??` is replaced with the last 2 digits of ID, e.g., `01`) $\to$ `A6AB2701`.
* **Binary conversion:** `10100110101010110010011100000001`.
* **Expansion:** The DES expansion table (E-table) duplicates 16 specific bits from this 32-bit input to expand it to 48 bits, ensuring each 4-bit nibble boundary is appropriately mapped according to standard DES specifications.

### 2.(b) How initial permutation (IP) and final permutation (FP) computed with permutation key? Explain with examples of IP table/FP table and some provision value as the value for encryption. (2.5 points)
* **IP and FP:** The Initial Permutation rearranges the bits of the 64-bit plaintext block according to a fixed permutation table before the first encryption round. The Final Permutation performs the exact inverse operation on the 64-bit block after the final round to produce the ciphertext.
* **Example:** The IP table specifies that bit 58 moves to position 1, bit 50 moves to position 2, and so forth. If a 64-bit block has bit 58 set to 1, that bit becomes the first bit of the permuted block.

### 2.(c) Compute data state using your last name as given in your certificate then do the sub-byte operation of a single round of AES algorithm using given sub-byte table below. (03 points)
* **Last name:** Lemon (5 letters). To form an AES state matrix, 16 bytes are organized in a 4x4 matrix.
* **Mapping ($A=0, B=1, \dots, Z=25$):** L=11 (`0B`), E=4 (`04`), M=12 (`0C`), O=14 (`0E`), N=13 (`0D`).
* **State Matrix (Columns filled sequentially with repeating letters):**
  * Column 0: `0B`, `04`, `0C`, `0E`
  * Column 1: `0D`, `0B`, `04`, `0C`
  * Column 2: `0E`, `0D`, `0B`, `04`
  * Column 3: `0C`, `0E`, `0D`, `0B`
* **Sub-Byte Operation:** Each byte is replaced by substituting the row (high nibble) and column (low nibble) from the Sub-Byte table. For instance, substituting byte `0B` yields the table value at row `0`, column `b` (`2b`), and byte `04` yields row `0`, column `4` (`f2`).

### 2.(d) How temporary word was calculated in AES word expansion for key? How word expansion computed to generate keys in AES? (02 points)
* **Temporary word (`temp`):** In AES key expansion, a temporary 4-byte word is initialized with the previous column word of the key schedule. It undergoes a one-byte left rotation, byte substitution via the S-box, and an XOR operation with a round constant before being XORed with the word four positions earlier.
* **Word expansion computation:** The key expansion routine takes a 16-byte cipher key and expands it into an array of 44 words. The first 4 words are the original key, and each subsequent word is generated by XORing the previous word and the word four positions back, applying transformation steps every fourth word.

---



***

# Department of Computer Science and Engineering, Jagannath University
## M.Sc. in CSE Professional Program Mid-Term Examination-2025 (16B)
**Course Code:** CSE-5310  
**Course Title:** Internet Security and Policy  
**Time:** 1:00 hour  
**Total Points:** 20  

---

### Question 1
**(a)** Define Cryptography. Explain the security goals with example. **[03 points]**

**(b)** How does Caesar cipher works? Convert `MSCPINCSEJNU` in to cipher text using key=3. **[02 points]**

**(c)** Illustrate and explain the basic diagram for data encryption standard (DES). **[03 points]**

**(d)** Compute the outcome of `2F4CBB5D` in hexadecimal after passing through expansion d-box. **[02 points]**

---

### Question 2
**(a)** Calculate the output of hexadecimal value `22AAB27DB55D` passing through s-boxes. **[02 points]**

**(b)** Differ data state and data block used in advanced encryption standard AES. Convert your first name to data state used in AES encryption, e.g. MD Kamal Uddin, here MD Kamal is the first name. Consider the alphabet mapping A->0, B->1 .. Z->25. **[03 points]**

**(c)** How many operations in a single round of AES and how these are ordered? Discuss shift-rows with example. **[02 points]**

**(d)** Illustrate and discuss AES key expansion strategy. **[03 points]**

---

### S-Box Tables for DES

#### S1
| Row \ Column | [0] | [1] | [2] | [3] | [4] | [5] | [6] | [7] | [8] | [9] | [10] | [11] | [12] | [13] | [14] | [15] |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **[0]** | 14 | 4 | 13 | 1 | 2 | 15 | 11 | 8 | 3 | 10 | 6 | 12 | 5 | 9 | 0 | 7 |
| **[1]** | 0 | 15 | 7 | 4 | 14 | 2 | 13 | 1 | 10 | 6 | 12 | 11 | 9 | 5 | 3 | 8 |
| **[2]** | 4 | 1 | 14 | 8 | 13 | 6 | 2 | 11 | 15 | 12 | 9 | 7 | 3 | 10 | 5 | 0 |
| **[3]** | 15 | 12 | 8 | 2 | 4 | 9 | 1 | 7 | 5 | 11 | 3 | 14 | 10 | 0 | 6 | 13 |

#### S2
| Row \ Column | [0] | [1] | [2] | [3] | [4] | [5] | [6] | [7] | [8] | [9] | [10] | [11] | [12] | [13] | [14] | [15] |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **[0]** | 15 | 1 | 8 | 14 | 6 | 11 | 3 | 4 | 9 | 7 | 2 | 13 | 12 | 0 | 5 | 10 |
| **[1]** | 3 | 13 | 4 | 7 | 15 | 2 | 8 | 14 | 12 | 0 | 1 | 10 | 6 | 9 | 11 | 5 |
| **[2]** | 0 | 14 | 7 | 11 | 10 | 4 | 13 | 1 | 5 | 8 | 12 | 6 | 9 | 3 | 2 | 15 |
| **[3]** | 13 | 8 | 10 | 1 | 3 | 15 | 4 | 2 | 11 | 6 | 7 | 12 | 0 | 5 | 14 | 9 |

#### S3
| Row \ Column | [0] | [1] | [2] | [3] | [4] | [5] | [6] | [7] | [8] | [9] | [10] | [11] | [12] | [13] | [14] | [15] |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **[0]** | 10 | 0 | 9 | 14 | 6 | 3 | 15 | 5 | 1 | 13 | 12 | 7 | 11 | 4 | 2 | 8 |
| **[1]** | 13 | 7 | 0 | 9 | 3 | 4 | 6 | 10 | 2 | 8 | 5 | 14 | 12 | 11 | 15 | 1 |
| **[2]** | 13 | 6 | 4 | 9 | 8 | 15 | 3 | 0 | 11 | 1 | 2 | 12 | 5 | 10 | 14 | 7 |
| **[3]** | 1 | 10 | 13 | 0 | 6 | 9 | 8 | 7 | 4 | 15 | 14 | 3 | 11 | 5 | 2 | 12 |

#### S4
| Row \ Column | [0] | [1] | [2] | [3] | [4] | [5] | [6] | [7] | [8] | [9] | [10] | [11] | [12] | [13] | [14] | [15] |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **[0]** | 7 | 13 | 14 | 3 | 0 | 6 | 9 | 10 | 1 | 2 | 8 | 5 | 11 | 12 | 4 | 15 |
| **[1]** | 13 | 8 | 11 | 5 | 6 | 15 | 0 | 3 | 4 | 7 | 2 | 12 | 1 | 10 | 14 | 9 |
| **[2]** | 10 | 6 | 9 | 0 | 12 | 11 | 7 | 13 | 15 | 1 | 3 | 14 | 5 | 2 | 8 | 4 |
| **[3]** | 3 | 15 | 0 | 6 | 10 | 1 | 13 | 8 | 9 | 4 | 5 | 11 | 12 | 7 | 2 | 14 |

#### S5
| Row \ Column | [0] | [1] | [2] | [3] | [4] | [5] | [6] | [7] | [8] | [9] | [10] | [11] | [12] | [13] | [14] | [15] |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **[0]** | 2 | 12 | 4 | 1 | 7 | 10 | 11 | 6 | 8 | 5 | 3 | 15 | 13 | 0 | 14 | 9 |
| **[1]** | 14 | 11 | 2 | 12 | 4 | 7 | 13 | 1 | 5 | 0 | 15 | 10 | 3 | 9 | 8 | 6 |
| **[2]** | 4 | 2 | 1 | 11 | 10 | 13 | 7 | 8 | 15 | 9 | 12 | 5 | 6 | 3 | 0 | 14 |
| **[3]** | 11 | 8 | 12 | 7 | 1 | 14 | 2 | 13 | 6 | 15 | 0 | 9 | 10 | 4 | 5 | 3 |

#### S6
| Row \ Column | [0] | [1] | [2] | [3] | [4] | [5] | [6] | [7] | [8] | [9] | [10] | [11] | [12] | [13] | [14] | [15] |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **[0]** | 12 | 1 | 10 | 15 | 9 | 2 | 6 | 8 | 0 | 13 | 3 | 4 | 14 | 7 | 5 | 11 |
| **[1]** | 10 | 15 | 4 | 2 | 7 | 12 | 9 | 5 | 6 | 1 | 13 | 14 | 0 | 11 | 3 | 8 |
| **[2]** | 9 | 14 | 15 | 5 | 2 | 8 | 12 | 3 | 7 | 0 | 4 | 10 | 1 | 13 | 11 | 6 |
| **[3]** | 4 | 3 | 2 | 12 | 9 | 5 | 15 | 10 | 11 | 14 | 1 | 7 | 6 | 0 | 8 | 13 |

#### S7
| Row \ Column | [0] | [1] | [2] | [3] | [4] | [5] | [6] | [7] | [8] | [9] | [10] | [11] | [12] | [13] | [14] | [15] |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **[0]** | 4 | 11 | 2 | 14 | 15 | 0 | 8 | 13 | 3 | 12 | 9 | 7 | 5 | 10 | 6 | 1 |
| **[1]** | 13 | 0 | 11 | 7 | 4 | 9 | 1 | 10 | 14 | 3 | 5 | 12 | 2 | 15 | 8 | 6 |
| **[2]** | 1 | 4 | 11 | 13 | 12 | 3 | 7 | 14 | 10 | 15 | 6 | 8 | 0 | 5 | 9 | 2 |
| **[3]** | 6 | 11 | 13 | 8 | 1 | 4 | 10 | 7 | 9 | 5 | 0 | 15 | 14 | 2 | 3 | 12 |

#### S8
| Row \ Column | [0] | [1] | [2] | [3] | [4] | [5] | [6] | [7] | [8] | [9] | [10] | [11] | [12] | [13] | [14] | [15] |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **[0]** | 13 | 2 | 8 | 4 | 6 | 15 | 11 | 1 | 10 | 9 | 3 | 14 | 5 | 0 | 12 | 7 |
| **[1]** | 1 | 15 | 13 | 8 | 10 | 3 | 7 | 4 | 12 | 5 | 6 | 11 | 0 | 14 | 9 | 2 |
| **[2]** | 7 | 11 | 4 | 1 | 9 | 12 | 14 | 2 | 0 | 6 | 10 | 13 | 15 | 3 | 5 | 8 |
| **[3]** | 2 | 1 | 14 | 7 | 4 | 10 | 8 | 13 | 15 | 12 | 9 | 0 | 3 | 5 | 6 | 11 |

---
## Part 2: Mid-Term Examination-2025 (16B)
**Course Code:** CSE-5310, **Course Title:** Internet Security and Policy  
**Time:** 1:00 hour, **Total Points:** 20

### 1.a) Define Cryptography. Explain the security goals with example. (03 points)
* **Cryptography:** The practice and study of hiding information, transforming plaintext into ciphertext to ensure secure communication over untrusted networks.
* **Security Goals:**
  1. **Confidentiality:** Ensuring information is accessible only to authorized individuals. Example: Encrypting credit card details during online checkout.
  2. **Integrity:** Ensuring data has not been altered or tampered with in transit. Example: Using cryptographic hash functions like SHA-256 to verify file downloads.
  3. **Availability:** Ensuring computing resources and data are accessible to authorized users when needed. Example: Defending a web server against denial-of-service attacks.

### 1.b) How does Caesar cipher works? Convert MSCPINCSEJNU in to cipher text using key=3. (02 points)
* **Caesar cipher:** A substitution cipher where each letter in the plaintext is shifted a fixed number of positions down the alphabet.
* **Conversion of `MSCPINCSEJNU` (key = 3):** Shift each letter forward by 3 positions:
  * M $\to$ P, S $\to$ V, C $\to$ F, P $\to$ S, I $\to$ L, N $\to$ Q, C $\to$ F, S $\to$ V, E $\to$ H, J $\to$ M, N $\to$ Q, U $\to$ X.
  * **Ciphertext:** `PVFSLQFVHMQX`.

### 1.c) Illustrate and explain the basic diagram for data encryption standard (DES). (03 points)
* The Data Encryption Standard (DES) is a symmetric block cipher operating on 64-bit blocks using a 56-bit key through 16 identical rounds of processing.
* **Structure:** The 64-bit input undergoes an Initial Permutation, is split into left and right 32-bit halves, passes through 16 Feistel rounds where the right half is expanded, XORed with a 48-bit round key, passed through S-boxes, permuted, and XORed with the left half. The halves are swapped after each round, and a final inverse permutation produces the 64-bit ciphertext.

### 1.d) Compute the outcome of 2F4CBB5D in hexadecimal after passing through expansion d box. (02 points)
* The 32-bit input hexadecimal `2F4CBB5D` is converted to binary, expanded to 48 bits using the DES expansion table, and re-expressed according to the standard DES E-table bit duplication mapping.

### 2.(a) Calculate the output of hexadecimal value 22AAB27DB55D passing through s-boxes. (02 points)
* In DES, a 48-bit input is divided into eight 6-bit blocks, each passing through one of the eight S-boxes to produce a 4-bit output. The outer bits of each 6-bit chunk select the row and the inner 4 bits select the column in the respective S-box table to yield the substituted 32-bit result.

### 2.(b) Differ data state and data block used in advanced encryption standard AES. Convert your first name to data state used in AES encryption, e.g. MD Kamal Uddin, here MD Kamal is the first name. Consider the alphabet mapping A->0, B->1 .. Z->25. (03 points)
* **Data block vs. Data state:** A data block refers to the fixed 128-bit block of input or output data treated as a linear sequence of bytes. A data state is the internal 4x4 matrix representation of that block upon which the AES round operations are performed.
* **First name conversion:** Using alphabet mapping ($A=0, B=1, \dots, Z=25$), letters are assigned numeric values and populate the 4x4 state matrix columns sequentially.

### 2.(c) How many operations in a single round of AES and how these are ordered? Discuss shift-rows with example. (02 points)
* **AES single round operations (4 operations for standard rounds):**
  1. SubBytes (non-linear substitution using S-box)
  2. ShiftRows (cyclically shifting bytes of rows in the state matrix)
  3. MixColumns (mixing columns for diffusion)
  4. AddRoundKey (XORing state with the round key)
  *(Note: The final round omits MixColumns).*
* **Shift-Rows example:** Row 0 remains unshifted. Row 1 shifts left by 1 byte. Row 2 shifts left by 2 bytes. Row 3 shifts left by 3 bytes. For example, if row 1 contains bytes `[10, 11, 12, 13]`, shifting left by 1 byte results in `[11, 12, 13, 10]`.

### 2.(d) Illustrate and discuss AES key expansion strategy. (03 points)
* The AES key expansion algorithm takes a 16-byte cipher key and expands it into a schedule of 44 four-byte words. It uses word-level operations including word rotation, byte substitution via the AES S-box, and an XOR sum with round constants to introduce asymmetry and prevent symmetry-based attacks across multiple rounds.