# 📘 Session 2: Number System Introduction and Radix Conversion

---

## 📚 Topics Covered
- Number systems: Binary, Octal, Decimal, Hexadecimal  
- Base (radix) and digit representation  
- Place value system  
- Powers of base (2, 8, 10, 16)  
- Base conversion methods  
- Binary ↔ Octal/Hex shortcuts  

---

## 🔑 Key Concepts
- **Number System:** Method to represent numbers using a base  
- **Base (Radix):** Total number of unique digits (e.g., binary = 2)  
- **Place Value:** Each digit = digit × base^position  
- **Binary System:** Uses only 0 and 1 (used in computers)  
- **Octal System:** Base 8 (0–7), groups of 3 binary bits  
- **Hexadecimal:** Base 16 (0–9, A–F), groups of 4 binary bits  

### 🔄 Conversion Rules
- Any base → Decimal → multiply & add  
- Decimal → any base → divide & remainder  
- Binary ↔ Hex/Octal → grouping shortcut  

---

## 🧠 Notes
- Always count positions from **right → left starting at 0**  
- In division method, **reverse remainders at the end**  
- For binary grouping:  
  - Hex → groups of **4 bits**  
  - Octal → groups of **3 bits**  
- Add **leading zeros** if grouping is incomplete  
- Hex values:  
  - A=10, B=11, C=12, D=13, E=14, F=15  

---

## 🧩 Examples

---

### 🔹 1) Binary → Other Systems  
**Convert:** `101101₂`

#### ➤ Binary → Decimal
Position → 5 4 3 2 1 0
Binary → 1 0 1 1 0 1

= 1×2⁵ + 0×2⁴ + 1×2³ + 1×2² + 0×2¹ + 1×2⁰
= 32 + 0 + 8 + 4 + 0 + 1 = 45₁₀


#### ➤ Binary → Octal

101 101 → (5)(5) → 55₈


#### ➤ Binary → Hex

0010 1101 → (2)(D) → 2D₁₆


---

### 🔹 2) Decimal → Other Systems  
**Convert:** `45₁₀`

#### ➤ Decimal → Binary

<pre> ```text id="align01"45 ÷ 2 = 22 r1
22 ÷ 2 = 11 r0
11 ÷ 2 = 5 r1
5 ÷ 2 = 2 r1
2 ÷ 2 = 1 r0
1 ÷ 2 = 0 r1

Answer → 101101₂``` </pre>


#### ➤ Decimal → Octal

45 ÷ 8 = 5 r5
5 ÷ 8 = 0 r5

Answer → 55₈


#### ➤ Decimal → Hex

45 ÷ 16 = 2 r13 (D)
2 ÷ 16 = 0 r2

Answer → 2D₁₆


---

### 🔹 3) Octal → Other Systems  
**Convert:** `157₈`

#### ➤ Octal → Binary

1 → 001
5 → 101
7 → 111

→ 001 101 111 = 1101111₂


#### ➤ Octal → Decimal

= 1×8² + 5×8¹ + 7×8⁰
= 64 + 40 + 7 = 111₁₀


#### ➤ Octal → Hex

Binary → 0110 1111
→ (6)(F) → 6F₁₆


---

### 🔹 4) Hexadecimal → Other Systems  
**Convert:** `3A₁₆`

#### ➤ Hex → Binary

3 → 0011
A → 1010

→ 00111010₂


#### ➤ Hex → Decimal

= 3×16¹ + 10×16⁰
= 48 + 10 = 58₁₀


#### ➤ Hex → Octal

Binary → 001 110 100
→ (1)(6)(4) → 164₈


---

## 🎯 Final Visual Summary

Binary ↔ Octal → group 3 bits

Binary ↔ Hex → group 4 bits

Any Base → Decimal → multiply & add

Decimal → Any Base → divide & remainder


---

## 💡 Quick Revision Trick
- Binary → group  
- Decimal → divide  
- Others → go via Binary or Decimal  
