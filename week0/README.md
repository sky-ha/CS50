# CS50 Week 0: Scratch

## 📚 Lecture Context
- **Binary:** The only reality for computers. Everything is just a switch (0 or 1).
- **Standards (ASCII, RGB):** The "Agreements" that transform raw bits into human-readable information.
- **Algorithm:** Finding the most efficient logic to manipulate those bits.
- **Scratch:** A tool to learn control flow (Logic) while ignoring syntax details.
---
## 🧠 Key Insights
### 1. Hardware Reality (Electric Path)
> **"Computers don't 'think', they just flow."**
Computers are not magic calculators. They are physical circuits where electricity flows through logic gates. What looks like "calculation" to us is just the rapid blinking of 0s and 1s following a pre-set path.

### 2. The CEO Mindset (Algorithms)
> **"A developer is a manager of billions of subordinates who can only say 'Yes' or 'No'."**
How you utilize these massive resources depends entirely on the manager's capability. A bad algorithm means wasting the labor of billions of transistors ($O(N^2)$), while a good one maximizes efficiency ($O(log N)$).

### 3. Developer vs Hacker (Abstraction)
- **Developer:** Uses the abstraction. Trusts that the function works as intended to build services.
- **Hacker:** Doubts the abstraction. Searches for the vulnerability in the "well-working" function.

### 4. The Core: RIP Register (Control Flow)
- **The Physical Handle:** The "Control" of a program isn't an abstract concept. It is physically determined by the **RIP (Instruction Pointer) Register**, a specific set of transistors holding the address of the next instruction.
- **Blind Obedience:** The CPU has no moral compass. It blindly executes whatever address is in the RIP.
- **Hacker's Target:** If I can overwrite the RIP (e.g., via Buffer Overflow), I physically seize control of the machine's steering wheel.
---
## 🛠️ Problem Set 0
- **Project Name:** 
- **Implementation:** [Link to Write-up](./pset0/WRITEUP.md)
- ...