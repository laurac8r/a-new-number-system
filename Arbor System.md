Let's build one from scratch. To make a number system, we need three things: a **Base** (how high we count before carrying over), a set of **Symbols** (digits), and a **Direction** (how we read place value).

Let’s create a Base-6 system inspired by nature. We’ll call it the **Arbor System**.

### The Arbor System (Base-6)

Because it's Base-6, we only need six symbols (representing 0 through 5). Instead of arbitrary squiggles, Arbor uses symbols that mimic the growth of a plant.

| Arbor Symbol | Symbol Name | Base-10 Value | Meaning |
| --- | --- | --- | --- |
| `.` | Seed | 0 | The origin, emptiness. |
| `|` | Sprout | 1 | A single upward growth. |
| `v` | Leaf | 2 | Two directions. |
| `Y` | Branch | 3 | Three points. |
| `+` | Canopy | 4 | Four directions. |
| `*` | Bloom | 5 | Maximum growth before reseeding. |

---

### How Place Value Works

In our standard Base-10 system, each place value is a power of 10 (1s, 10s, 100s).
In the Arbor System, each place value is a power of 6 ($6^0$, $6^1$, $6^2$, $6^3$).

* **1st position (right):** Singles (1s)
* **2nd position (middle):** Sixes (6s)
* **3rd position (left):** Thirty-sixes (36s)

*Note: In the lore of the Arbor system, numbers are actually written vertically from bottom to top (like a tree growing), but for the sake of typing, we'll write them left to right like standard numbers.*

---

### Counting in Arbor

Let's look at how you count from 0 to 15 to see the pattern in action:

* **0:** `.` (0)
* **1:** `|` (1)
* **2:** `v` (2)
* **3:** `Y` (3)
* **4:** `+` (4)
* **5:** `*` (5)
* **6:** `|.` (One 6, zero 1s)
* **7:** `||` (One 6, one 1)
* **8:** `|v` (One 6, two 1s)
* **11:** `|*` (One 6, five 1s)
* **12:** `v.` (Two 6s, zero 1s)
* **13:** `v|` (Two 6s, one 1)
* **15:** `vY` (Two 6s, three 1s)

---

### Doing Math in Arbor

Arithmetic works exactly the same as our normal system; you just carry over whenever you hit 6 instead of 10.

**Addition Example: 8 + 5 = 13**

* **8** in Arbor is `|v`
* **5** in Arbor is `*`
* Let's add them: `|v` + `*`
* Add the singles: `v` (2) + `*` (5) = 7.
* Since 7 is larger than 5, we carry over a six. 7 is one 6 and one 1. So we write down the `|` (1) and carry the `|` (6).
* Add the carried `|` to the existing sixes column: `|` + `|` = `v` (2).
* **Result:** `v|` (which is exactly 13 in Base-10).

---

Would you like me to translate your age, favorite number, or a specific math equation into the Arbor system?