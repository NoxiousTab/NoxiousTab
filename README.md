<div align="center">

# Tabish Ahmed

**Systems programming, search & optimization, backend engineering, security**

<br/>

<a href="https://www.linkedin.com/in/ahmed-tabish"><img src="https://cdn.simpleicons.org/linkedin/0A66C2" alt="LinkedIn" height="28" /></a>&nbsp;&nbsp;&nbsp;
<a href="mailto:noxioustab@gmail.com"><img src="https://cdn.simpleicons.org/gmail/EA4335" alt="Email" height="28" /></a>&nbsp;&nbsp;&nbsp;
<a href="https://codeforces.com/profile/noxious_tab"><img src="https://cdn.simpleicons.org/codeforces/1F8ACB" alt="Codeforces" height="28" /></a>&nbsp;&nbsp;&nbsp;
<a href="https://www.codechef.com/users/noxioustab"><img src="https://cdn.simpleicons.org/codechef/8B6B4E" alt="CodeChef" height="28" /></a>

</div>

<br/>

## About

I'm a computer science undergraduate based in Pune. I'm most interested in what happens underneath the abstractions: how a search algorithm prunes a game tree, how a query planner is being asked to do too much work, how a packet moves through a network stack, how a kernel boots. I like writing software where correctness can be verified and performance can be measured, and I like it more when both are true.

Outside of projects, I compete on **Codeforces (Candidate Master)**, **CodeChef** and **GeeksforGeeks**, and I work through offensive security challenges on **HackTheBox**, where I'm ranked **Pro Hacker** and **#2 in India**, with 55+ machines rooted.

<br/>

## Technical Focus

<table>
  <tr>
    <td width="200"><b>Systems & Algorithms</b></td>
    <td>
      <img src="https://cdn.simpleicons.org/cplusplus/00599C" height="30" alt="C++" title="C++" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/c/A8B9CC" height="30" alt="C" title="C" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/gnubash/4EAA25" height="30" alt="Bash" title="Bash" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/linux/FCC624" height="30" alt="Linux" title="Linux" />
    </td>
  </tr>
  <tr>
    <td><b>Backend & Cloud</b></td>
    <td>
      <img src="https://cdn.simpleicons.org/python/3776AB" height="30" alt="Python" title="Python" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/django/44B78B" height="30" alt="Django" title="Django" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/flask/8C8C8C" height="30" alt="Flask" title="Flask" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/dotnet/512BD4" height="30" alt=".NET" title=".NET" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/microsoftazure/0078D4" height="30" alt="Azure" title="Azure" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/docker/2496ED" height="30" alt="Docker" title="Docker" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/githubactions/2088FF" height="30" alt="GitHub Actions" title="GitHub Actions" />
    </td>
  </tr>
  <tr>
    <td><b>Data</b></td>
    <td>
      <img src="https://cdn.simpleicons.org/postgresql/4169E1" height="30" alt="PostgreSQL" title="PostgreSQL" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/supabase/3ECF8E" height="30" alt="Supabase" title="Supabase" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/mysql/4479A1" height="30" alt="MySQL" title="MySQL" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/sqlite/5B9BD5" height="30" alt="SQLite" title="SQLite" />
    </td>
  </tr>
  <tr>
    <td><b>Frontend & Mobile</b></td>
    <td>
      <img src="https://cdn.simpleicons.org/typescript/3178C6" height="30" alt="TypeScript" title="TypeScript" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/react/61DAFB" height="30" alt="React" title="React" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/nextdotjs/8C8C8C" height="30" alt="Next.js" title="Next.js" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/tailwindcss/06B6D4" height="30" alt="Tailwind CSS" title="Tailwind CSS" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/kotlin/7F52FF" height="30" alt="Kotlin" title="Kotlin" />
    </td>
  </tr>
  <tr>
    <td><b>Machine Learning</b></td>
    <td>
      <img src="https://cdn.simpleicons.org/pytorch/EE4C2C" height="30" alt="PyTorch" title="PyTorch" />&nbsp;&nbsp;
      <img src="https://cdn.simpleicons.org/huggingface/FFD21E" height="30" alt="Hugging Face" title="Hugging Face" />
    </td>
  </tr>
  <tr>
    <td><b>Also</b></td>
    <td>Java, C#, SQL, Git</td>
  </tr>
</table>

<br/>

## Selected Projects

### [nox_engine](https://github.com/NoxiousTab/nox_engine)
A UCI-compliant chess engine in C++17. Multithreaded alpha-beta search with iterative deepening, principal variation search, null-move, late-move-reduction and futility pruning, and a transposition table. Move generation is validated with Perft (119M+ nodes). It also includes a neural evaluation network trained in PyTorch, exported to a native binary, and benchmarked through automated self-play A/B testing.
<sub>C++17 · PyTorch · Alpha-beta · Bitboards</sub>

### [nox_os](https://github.com/NoxiousTab/nox_os)
A custom operating system written from scratch. Not a Linux distribution.
<sub>C</sub>

### [nox_sniffer](https://github.com/NoxiousTab/nox_sniffer)
A packet sniffer written from scratch in C, built for the love of low-level programming.
<sub>C</sub>

### [codesense](https://github.com/NoxiousTab/codesense)
Semantic code search over your own codebase. Source is parsed with Tree-sitter, embedded with Hugging Face models, indexed in FAISS, and queried through a Streamlit interface.
<sub>Python · Tree-sitter · FAISS · Hugging Face · Streamlit</sub>

### [practice_judge](https://github.com/NoxiousTab/practice_judge)
An online coding judge supporting three languages with sandboxed execution through Judge0. Judging is asynchronous via Edge Functions and Realtime, backed by an RLS-secured Postgres schema, with admin tooling for bulk testcase imports.
<sub>React · TypeScript · Supabase · Judge0 · Docker</sub>

<br/>

## What I'm Into

**Search and the cost of a decision.** Chess engines are the most honest playground I know for algorithms. Every pruning heuristic is a bet that you can safely skip work, and the engine either wins games or it doesn't. I like that the feedback is brutal and quantifiable: node counts, Perft correctness, and self-play results decide what stays.

**Building it once from scratch.** An OS, a packet sniffer, a chess engine. Writing the layer that others take for granted is the fastest way I've found to actually understand it, and it changes how I write code on top of those layers.

**Performance as a habit, not a phase.** The most satisfying diff is the one that does the same thing with less: fewer queries, fewer round trips, fewer allocations. I care about measuring first and being able to say exactly what changed and by how much.

**Where classical engineering meets learned systems.** Neural evaluation inside a hand-tuned search, or embeddings behind a code search tool. I'm interested in the seams: what to learn, what to keep deterministic, and how to ship a model as part of a real binary.

**Offense to understand defense.** HackTheBox and CTFs keep me honest about how systems actually fail. Reading a machine the way an attacker does makes me a more careful engineer.

**Competitive programming.** Fast, precise problem solving under time pressure. It keeps my fundamentals sharp and is the reason data structures and complexity analysis are reflexes rather than lookups.

<br/>

<div align="center">
  <sub>Open to interesting systems and backend problems. Reach me on LinkedIn or by email.</sub>
</div>