<style>
  input[type="checkbox"] {
    width: 18px;
    height: 18px;
    cursor: pointer;
    transition: box-shadow 0.3s ease, background-color 0.3s ease;
  }

  input[type="checkbox"]:hover {
    box-shadow: 0 0 5px 2px rgba(59, 130, 246, 0.6);
    background-color: rgba(59, 130, 246, 0.1);
  }

  input[type="checkbox"]:focus-visible {
    outline: 2px solid rgba(59, 130, 246, 0.8);
    outline-offset: 2px;
  }
</style>

# ✅ Day 5: Bit Manipulation

## 📖 What is Bit Manipulation?

**Bit Manipulation** deals with operations directly on binary digits (bits) using operators like `&`, `|`, `^`, `~`, `<<`, `>>`. These are super-fast and allow clever tricks for common problems like counting 1s, toggling values, or generating subsets.

---

## 🚀 Why Learn It?

* ⚡ **Speed** – Bitwise ops are constant time.
* 💾 **Memory Efficient** – Multiple flags in a single int.
* 🧠 **Elegant Solutions** – Replace loops with masks.

---

## 🎥 Watch & Learn


* <input type="checkbox" id="watch-striver"> <label for="watch-striver">[Striver’s Bit Manipulation Playlist](https://www.youtube.com/playlist?list=PLgUwDviBIf0rnqh8QsJaHyIX7KUiaPUv7)</label>

---

## Codeforces Practice Problems

Try these problems to get hands-on with bit tricks:

* <input type="checkbox" id="cf-1915a"> <label for="cf-1915a">[1915A – Bit++](https://codeforces.com/problemset/problem/1915/A)</label>
* <input type="checkbox" id="cf-1915b"> <label for="cf-1915b">[1915B – Odd Grasshopper](https://codeforces.com/problemset/problem/1915/B)</label>
* <input type="checkbox" id="cf-1979b"> <label for="cf-1979b">[1979B – Grid Paths](https://codeforces.com/problemset/problem/1979/B)</label>
* <input type="checkbox" id="cf-1944b"> <label for="cf-1944b">[1944B – Set and Forget](https://codeforces.com/problemset/problem/1944/B)</label>
* <input type="checkbox" id="cf-1635a"> <label for="cf-1635a">[1635A – Min Or Sum](https://codeforces.com/problemset/problem/1635/A)</label>

🔖 Bonus Practice:

* <a href="https://leetcode.com/tag/bit-manipulation/" target="_blank">Bit Manipulation Problems on LeetCode</a>
* <a href="https://www.codechef.com/practice/bit-manipulation" target="_blank">CodeChef Bit Manipulation Practice</a>

---


---

## 🔝 Top 5 Must-Know Topics (with LeetCode links)

1. **Basic Bitwise Ops**

   * ➤ `&`, `|`, `^`, `~`, `<<`, `>>`
   * 🔗 LeetCode:

     * [Single Number](https://leetcode.com/problems/single-number/)
     * [Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/)

2. **Counting Bits**

   * ➤ Hamming weight, prefix bits
   * 🔗 LeetCode:

     * [Counting Bits](https://leetcode.com/problems/counting-bits/)
     * [Binary Gap](https://leetcode.com/problems/binary-gap/)



3. **Subset Generation with Bitmasks**

   * ➤ `for (int mask = 0; mask < (1 << n); ++mask)`
   * 🔗 LeetCode:

     * [Subsets](https://leetcode.com/problems/subsets/)
     * [Partition to K Equal Sum Subsets](https://leetcode.com/problems/partition-to-k-equal-sum-subsets/) *(uses bitmasking in advanced solutions)*



4. **Power-of-Two Checks & Range Masks**

   * ➤ `x & (x - 1) == 0`
   * 🔗 LeetCode:

     * [Power of Two](https://leetcode.com/problems/power-of-two/)
     * [Bitwise AND of Numbers Range](https://leetcode.com/problems/bitwise-and-of-numbers-range/)

5. **Advanced Patterns**

   * ➤ XOR tricks, palindromic subsequence masks
   * 🔗 LeetCode:

     * [Maximum XOR of Two Numbers in an Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/)
     * [Count Different Palindromic Subsequences](https://leetcode.com/problems/count-different-palindromic-subsequences/)

---



## 📘 Learn More

* 📚 [CP Algorithms – Bit Manipulation](https://cp-algorithms.com/algebra/bit-manipulation.html)
* 📚 [GFG – Bit Tricks You Must Know](https://www.geeksforgeeks.org/bit-tricks/)

---

## 🧾 Checklist

* <input type="checkbox" id="check-ops"> <label for="check-ops">Master all 6 bitwise operators</label>
* <input type="checkbox" id="check-hamming"> <label for="check-hamming">Practice Hamming weight & parity tricks</label>
* <input type="checkbox" id="check-subsets"> <label for="check-subsets">Use bitmasks to generate subsets</label>
* <input type="checkbox" id="check-power"> <label for="check-power">Try power-of-two and range-based problems</label>
* <input type="checkbox" id="check-codeforces"> <label for="check-codeforces">Finish Codeforces bit problems</label>

---

## 💡 Tip

> “Think in bits, solve in constant time — bit manipulation is the coder’s secret weapon.”

---

## 📣 Need Help?

Join our [Discord Doubt Channel](https://discord.gg/D3jDzyAE) for Q\&A and support!

> 🧑‍💻 *contributed by [charanreddy-git](https://github.com/charanreddy-git/)*

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const checkboxes = document.querySelectorAll('input[type="checkbox"]');
    checkboxes.forEach((checkbox) => {
      const isChecked = localStorage.getItem(checkbox.id) === "true";
      checkbox.checked = isChecked;
    });
    checkboxes.forEach((checkbox) => {
      checkbox.addEventListener("change", function () {
        localStorage.setItem(checkbox.id, checkbox.checked);
      });
    });
  });
</script>
