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

# 📦 Day 7 – CP Resource Dump

Today’s the last day of the summer camp. No new topics, no practice problems.  
Just dumping a list of good resources. Use them whenever you're stuck or want to improve.

---

## 🔗 Useful CP Sheets

- [Striver’s A2Z DSA Sheet](https://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2/)
- [TLE Eliminators CP Sheet](https://www.tle-eliminators.com/cp-sheet)
- [Striver’s CP Sheet (Interview Style)](https://takeuforward.org/interview-experience/strivers-cp-sheet)
- [A2OJ Ladders (for CF rating-wise practice)](https://earthshakira.github.io/a2oj-clientside/server/Ladders.html)
- [CSES Problem Set](https://cses.fi/problemset/)

---

## 📚 Books and Guides

- [CSES Competitive Programming Handbook (PDF)](https://cses.fi/book/book.pdf)
- [USACO Guide](https://usaco.guide/dashboard/)
- [Codeforces EDU Courses](https://codeforces.com/edu/course/2)

---

## 📺 YouTube Channels

- [Errichto (CF + Concepts)](https://www.youtube.com/@Errichto)
- [Gaurav Sen (Concepts)](https://www.youtube.com/@gkcs)
- [NeetCode (DSA Patterns)](https://www.youtube.com/@NeetCode)
- [take U forward (Striver)](https://www.youtube.com/@takeUforward)

---

## 🧰 Other Cool Stuff

- [Codeforces Topic-Wise Problems (Catalog)](https://codeforces.com/catalog)
- [Kunal Kushwaha’s CP Resources](https://github.com/kunal-kushwaha/Competitive-Programming-Resources)

---

---

## 🏁 Virtual Contest Challenge

To simulate real contests and test your current level, try this contest as a **virtual participant**:

👉 [Codeforces Round #719 (Div. 3)](https://codeforces.com/contest/1520)

- 8 problems total. Difficulty ramps up gradually.
- Don’t worry if you can’t solve them all, aim to do at least 3.
- Use upsolving to learn after the contest.

📌 Go to the link → Click "Virtual Participation" → Start whenever you want.

---

## ✅ Checklist

- <input type="checkbox" id="a1">Check out at least 1 CP sheet (A2Z, TLE, etc.).
- <input type="checkbox" id="a2">Try the CSES Problem Set.
- <input type="checkbox" id="a3">Explore the Codeforces EDU courses.
- <input type="checkbox" id="a4">Bookmark 1 YouTube channel and watch a video.
- <input type="checkbox" id="a5">Skim through the CP Handbook (CSES PDF).
- <input type="checkbox" id="a6">Join Codeforces and do a virtual contest.

---

## 💭 Final Words

This is just the start. Use these resources wisely.  
Improve slowly and steadily. Don’t chase speed, chase clarity.
What are you waiting for? Start Practicing!!!!.

---

## 💬 Need Help?

Join our **Discord Doubt Channel** anytime. Ask questions. Help others. Improve together.

[![Join us on Discord](https://img.icons8.com/color/48/discord-logo.png)](https://discord.gg/D3jDzyAE)

---

> Contributed by [udaykiran2427](https://github.com/udaykiran2427)

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
