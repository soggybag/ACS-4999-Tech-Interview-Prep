# ACS 4999 — Technical Interview Prep: Your 7-Week Plan

This plan turns your proposal into a week-by-week schedule. Your goals are unchanged: get fluent in DSA problem solving using NeetCode and LeetCode, recognize patterns, solve under time pressure, and analyze complexity. Keep this open during the term and use it as your checklist.

---

## How this term works

### The big picture
- **You do the learning and solving on your own time:** about 4–5 hours a week, using the NeetCode videos and LeetCode.
- **We meet once a week for 30–60 minutes.** Meetings are not lectures. They are where you **show** what you can do and get feedback. Think of each one as a mini interview.
- **Weeks 4 and 7 are 60-minute meetings.** They hold your midpoint assessment and your final mock interview.

### About the problem count
Your proposal covers the full NeetCode problem set. That's the right long-term target. In 7 weeks at 4–5 hours a week, though, all 150 problems would leave about 13 minutes per problem. That isn't enough time to struggle with a problem, and struggling is how pattern recognition develops. So this plan aims for **about 8–10 problems a week (about 60 total), solved well.**

- Each week's **Core** list is in priority order. Work down it, and stop when your time runs out.
- Anything left unfinished, plus the **Stretch** list, is optional. If you're moving fast, Stretch problems get you closer to the full 150.
- Keep working through the rest of the list after the term ends, while you're applying for jobs.

---

## Why AI matters for your goals

You're entering a job market that AI is reshaping. Here's how that affects this study:

- **Coding interviews still exist, but formats are splitting.** Many companies have moved back to in-person or proctored coding rounds because candidates were using AI to cheat. Others are trying rounds where you *may* use AI, and you're graded on how well you direct it, check its output, and fix it. Be ready for both.
- **Your thinking is what gets evaluated.** AI can write a working solution, so interviewers focus on what it can't show for you: why you chose an approach, the complexity, the edge cases that break it, and the tradeoffs. **Practice thinking out loud.** It is a core skill, not polish.
- **The entry-level market is competitive.** AI has reduced junior hiring at many companies. Strong DSA skills get you through the technical screen, but they won't set you apart on their own, so keep your projects and portfolio current too.
- **Your AI/ML grad school goal.** ML-focused interviews often ask you to implement things like k-means, softmax, or a simple neural-net forward pass from scratch. Graphs, heaps, and DP also come up directly in ML search, scheduling, and sequence problems. A few optional exercises below connect to this.

### AI rules for this study
1. **No AI on a first attempt.** Turn off Copilot and autocomplete. Solve in LeetCode or a plain editor, with a timer running.
2. **After 25 honest minutes, AI can tutor you.** Ask for a *hint*, not the solution. Record it in your log.
3. **After solving, AI can review your code.** Ask it for bugs, edge cases, and the complexity, then *check its claims yourself*. AI is often wrong about complexity.
4. **Once a week, use AI as a mock interviewer.** Text or voice, with it asking follow-up questions. This is your main live-interview practice between meetings.
5. **Be honest in your log.** Mark every problem as unaided, hint, or AI-reviewed. The point is to know where you really stand.

---

## Your weekly routine

### Homework (4–5 hrs)
| Time | Activity |
|---|---|
| ~45 min | Watch the NeetCode videos and review the concepts for this week's pattern |
| ~2.5–3 hrs | Solve problems. Spend 25–35 min on each; look at the solution only after that time is up |
| ~30 min | Re-solve 2 problems from earlier weeks from scratch, without looking |
| ~30 min | Complete the weekly written deliverable |
| ~20 min | Do one AI mock interview |

### Before each meeting (24 hours ahead)
Send me:
- [ ] Your updated **problem log**
- [ ] The week's **deliverable**
- [ ] **2 problems you want help with**, plus a sentence on where you got stuck

### What happens in a meeting
**30-minute meeting**
- **10 min — Cold explain-back.** I pick one of your homework problems. You re-solve it and talk through it, with no notes.
- **15 min — Your stuck problems**, or a pattern drill ("Here are 3 problem statements. Which pattern fits each, and why?").
- **5 min — Feedback and next week.**

**60-minute meeting:** the same, plus a 25-minute live problem you haven't seen, under interview conditions.

### Problem log
Keep a spreadsheet with one row per problem:

| Problem | Pattern | Time taken | Unaided / Hint / AI-reviewed | Time & space complexity | Would I recognize this again? (Y/N) | Revisit on |
|---|---|---|---|---|---|---|

Any problem marked "N" or "Hint" goes into your re-solve rotation.

---

## Week-by-week

### Week 1 — Arrays & Hashing, Two Pointers, Big-O
- **Learn:** Big-O analysis, hash map/set tradeoffs, sorting as preprocessing, converging and fast/slow pointers.
- **Core:** Contains Duplicate · Valid Anagram · Two Sum · Group Anagrams · Top K Frequent Elements · Product of Array Except Self · Valid Palindrome · Two Sum II · 3Sum · Container With Most Water
- **Stretch:** Longest Consecutive Sequence · Encode/Decode Strings · Trapping Rain Water
- **Deliverable:** *Complexity annotations.* For each problem you solved: time and space complexity, a one-line justification, and the brute-force complexity for comparison.
- **AI exercise:** Have AI solve one problem you've already solved. Find and write down one flaw or unstated assumption in its answer.

### Week 2 — Sliding Window, Stack, Binary Search
- **Learn:** Fixed vs. variable windows, monotonic stack, binary search on the answer space.
- **Core:** Best Time to Buy/Sell Stock · Longest Substring Without Repeating Characters · Longest Repeating Character Replacement · Permutation in String · Valid Parentheses · Min Stack · Daily Temperatures · Binary Search · Search a 2D Matrix · Koko Eating Bananas · Find Min in Rotated Sorted Array
- **Stretch:** Minimum Window Substring · Car Fleet · Search in Rotated Sorted Array · Time-Based Key-Value Store
- **Deliverable:** *Templates from memory.* Write the binary search and sliding-window templates without looking, with notes on off-by-one traps (`lo <= hi` vs. `lo < hi`).
- **AI exercise:** Your first AI mock interview. Focus on asking clarifying questions *before* you start coding.

### Week 3 — Linked Lists, Trees
- **Learn:** Dummy nodes, pointer reversal, cycle detection; recursive DFS (pre/in/post-order), BFS level order, BST properties.
- **Core:** Reverse Linked List · Merge Two Sorted Lists · Linked List Cycle · Reorder List · Remove Nth Node From End · Invert Binary Tree · Max Depth of Binary Tree · Diameter of Binary Tree · Same Tree · Lowest Common Ancestor of a BST · Level Order Traversal · Validate BST
- **Stretch:** LRU Cache · Kth Smallest in BST · Construct Tree from Preorder/Inorder · Binary Tree Max Path Sum
- **Deliverable:** *Pattern cheat sheet.* One page covering Weeks 1–3 that answers "how do I recognize this?": the phrases in a problem that point to a pattern, mapped to that pattern.
- **AI exercise:** Implement LRU Cache yourself, then compare it with an AI version. Which one is clearer, and why?

### Week 4 — Heaps, Tries, Backtracking + Midpoint Assessment
- **Learn:** Heaps for top-k and streaming problems, the two-heap median; trie insert/search; backtracking (choose → explore → un-choose).
- **Core:** Kth Largest Element in a Stream · Last Stone Weight · K Closest Points to Origin · Kth Largest Element in Array · Implement Trie · Design Add and Search Words · Subsets · Combination Sum · Permutations · Word Search
- **Stretch:** Find Median from Data Stream · Task Scheduler · Subsets II · N-Queens · Word Search II
- **Deliverable:** *Backtracking template from memory*, plus a hand-drawn recursion tree for one problem.
- **Midpoint assessment (60-minute meeting):** a 30-minute live medium problem you haven't seen, then 15 minutes scoring it together on the rubric below. This is your baseline. It isn't a pass/fail test; it shows where to focus for the rest of the term.

### Week 5 — Graphs
- **Learn:** Adjacency lists, grid BFS/DFS, multi-source BFS, topological sort, union-find.
- **Core:** Number of Islands · Clone Graph · Max Area of Island · Rotting Oranges · Pacific Atlantic Water Flow · Course Schedule · Course Schedule II · Graph Valid Tree · Number of Connected Components · Redundant Connection
- **Stretch:** Surrounded Regions · Word Ladder · Network Delay Time (Dijkstra) · Min Cost to Connect All Points (Prim/Kruskal)
- **Deliverable:** *Graph templates from memory:* BFS, DFS, topological sort (Kahn's algorithm), and union-find with path compression.
- **AI/ML exercise:** A short write-up on where graph algorithms appear in AI/ML (search in planning, dependency DAGs in training pipelines, kNN graphs).

### Week 6 — Dynamic Programming
- **Learn:** Define the state and recurrence first, then memoize, then tabulate, then reduce space.
- **Core:** Climbing Stairs · Min Cost Climbing Stairs · House Robber · House Robber II · Longest Palindromic Substring · Coin Change · Longest Increasing Subsequence · Word Break · Unique Paths · Longest Common Subsequence
- **Stretch:** Decode Ways · Partition Equal Subset Sum · Edit Distance · Best Time to Buy/Sell with Cooldown
- **Deliverable:** *DP recurrence notes.* For each problem, write the state definition, recurrence, base cases, and evaluation order *before* writing any code.
- **AI/ML exercise (optional):** Implement k-means, or softmax with cross-entropy, from scratch using only NumPy, and analyze its complexity.
- **Start early on the Week 7 AI exercise** (below). If this week's meeting runs 60 minutes, we'll review it.

### Week 7 — Putting It Together + Final Mock Interview
- **Practice:** Three timed mixed sets. Each set is 2 problems in 45 minutes, with the topic not labeled, the way a real interview works. Then re-solve the 5 weakest problems from your log.
- **AI exercise:** Take a buggy, AI-style solution, find and fix the bugs, and write a short explanation. Then do one AI-allowed mock interview: prompt deliberately, verify everything it gives you, and be able to explain every line.
- **Behavioral prep:** Write 3 STAR stories (Situation, Task, Action, Result). Make one of them about a time you caught a wrong AI output or chose not to rely on AI.
- **Deliverable:** A *final pattern reference* combining your notes from Weeks 1–6, plus a short reflection: how you've grown since the midpoint, and your plan for continued practice during your job search.
- **Final mock interview (60-minute meeting):** 45 minutes run like a real interview (brief intro, one medium problem with a possible follow-up, complexity discussion, your questions), then 15 minutes of feedback on the rubric, compared with your midpoint.

---

## How you'll be evaluated

| Component | What counts |
|---|---|
| **1-on-1 real-time assessment** | Your weekly cold explain-backs and the Week 4 midpoint |
| **Prepared notes** | Your problem log, the weekly deliverables, and your final pattern reference |
| **Final mock interview** | Scored on the rubric below and compared with your midpoint |

### Mock interview rubric
Each area is scored 1–4. These are the same areas real interviewers look at, so use them to check your own practice too.

1. **Problem understanding:** Do you ask about inputs, constraints, and edge cases before coding?
2. **Approach:** Do you identify the pattern, state the brute-force solution, then improve on it?
3. **Communication:** Do you explain your reasoning out loud the whole way through?
4. **Code correctness:** Is your code working and readable, without needing hints?
5. **Complexity analysis:** Are your time and space complexity correct, and can you justify them?
6. **Testing:** Do you walk through examples and edge cases, and catch your own bugs?

---

## Resources
- **NeetCode** (neetcode.io): problem roadmap and video explanations
- **LeetCode** (leetcode.com): where you solve the problems
- **Your problem log**: your most important study tool by the end of the term
