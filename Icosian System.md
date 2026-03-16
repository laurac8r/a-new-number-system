Let's build a Base-20 (vigesimal) number system. It's a structure that revolves entirely around the number 20—a perfect framework for anyone who regularly thinks in terms of a 20-sided die.

Let's call it the **Icosian System** (derived from the icosahedron, the geometric shape of a d20).

### The Logic of Icosian Digits

In our standard Base-10 system, we have ten unique symbols (0-9). In a Base-20 system, we need twenty unique symbols representing 0 through 19.

To make it intuitive rather than memorizing twenty random squiggles, Icosian digits are constructed using a sub-base of 5 (similar to how a tally system works):

* **The Void ( `O` ):** Represents 0.
* **The Slash ( `/` ):** Represents 1.
* **The Strike ( `—` ):** Represents 5.

You build numbers 1 through 19 by stacking these marks.

* **3** is `///`
* **5** is `—`
* **8** is `— ///`
* **14** is `— — ////`
* **19** is `— — — ////` (The highest single digit you can roll before the number "rolls over" to the next place value).

### The Place Values

In Base-10, place values multiply by 10 (1s, 10s, 100s, 1000s). In Icosian, place values multiply by 20. We read them from left to right, separating the "places" with a colon for readability.

* **1st Place (Units):** $20^0 = 1$
* **2nd Place (Crits):** $20^1 = 20$
* **3rd Place (Realms):** $20^2 = 400$
* **4th Place (Epics):** $20^3 = 8000$

Whenever a place value reaches 20, it resets to `O` and carries a `/` over to the next place to the left.

### Translating Numbers

Let's see how our standard Base-10 numbers translate into the Icosian System.

**Example 1: The Number 45**

* How many 20s fit into 45? **Two** (which equals 40).
* What is the remainder in the Units place? **Five**.
* **Icosian Translation:** `// : —`

**Example 2: The Year 2026**
To write 2026, we have to look at our place values (8000, 400, 20, 1).

* How many 400s (Realms) fit into 2026? **Five** ($5 \times 400 = 2000$).
* That leaves 26. How many 20s (Crits) fit into 26? **One** ($1 \times 20 = 20$).
* That leaves **Six** for the Units place.
* The Base-20 values are 5, 1, and 6.
* **Icosian Translation:** `— : / : — /`

### The Arithmetic

Because it relies on a visual tally system, addition is extremely visual. To add two numbers together, you just physically combine their marks and then "trade up" whenever you hit a threshold:

* Five Slashes (`/////`) transform into one Strike (`—`).
* Four Strikes (`— — — —`) transform into a `O` and carry a `/` to the next place value.

Would you like me to translate a specific number into Icosian, or should we try writing out a basic math equation using these new rules?