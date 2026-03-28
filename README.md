<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   ██████╗ ██╗     ██╗   ██╗███████╗██████╗ ██╗   ██╗███████╗██╗ ║
║   ██╔══██╗██║     ██║   ██║██╔════╝██╔══██╗██║   ██║██╔════╝██║ ║
║   ██████╔╝██║     ██║   ██║█████╗  ██║  ██║██║   ██║███████╗█████║
║   ██╔══██╗██║     ██║   ██║██╔══╝  ██║  ██║██║   ██║╚════██║██╔═╝║
║   ██████╔╝███████╗╚██████╔╝███████╗██████╔╝╚██████╔╝███████║██║  ║
║   ╚═════╝ ╚══════╝ ╚═════╝ ╚══════╝╚═════╝  ╚═════╝ ╚══════╝╚═╝ ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

</div>

```bash
$ ssh dan@melbourne.au
Last login: 10+ years ago from javascript-land
Welcome to Event Loop OS v10.x (LTS)

dan@melbourne:~$
```

---

```bash
dan@melbourne:~$ cat /etc/about.conf
```

```ini
[identity]
name        = Dan
location    = Melbourne, Australia 🦘
company     = Event Loop Pty Ltd
role        = Full-Stack Developer & Product Builder
experience  = 10+ years of turning ☕ into production code

[current_status]
obsession   = building AI agent skills that work across every coding assistant
side_quest  = video games (strictly for "UX research" purposes)
philosophy  = if it can be automated, it should have been automated yesterday
```

---

```bash
dan@melbourne:~$ top -b -n 1 | grep -E "SKILL|LEVEL"
```

```
  PID  SKILL                    LEVEL  STATUS
  001  TypeScript / React       ██████████████████░░  daily driver
  002  Node.js / Next.js        █████████████████░░░  production battle-tested
  003  Go                       ██████████████░░░░░░  when I need to feel fast
  004  GraphQL                  ██████████████░░░░░░  queries in my sleep
  005  AWS / Serverless         █████████████░░░░░░░  cloud-native since before it was cool
  006  Microservices            █████████████░░░░░░░  more services than customers
  007  AI Agent Skills          ████████████████████  current obsession (MAX)
  008  Video Game Dev           ████████░░░░░░░░░░░░  loading...
```

---

```bash
dan@melbourne:~$ ls -la ~/projects/current/
```

```
drwxr-xr-x  dan  staff  📰 html-magazine    → AI skill: articles → paginated magazine pages
drwxr-xr-x  dan  staff  🎨 html-slides      → AI skill: content → presentation slides
drwxr-xr-x  dan  staff  🛠️  claude-plugins   → tools that make devs say "wait you can do that?"
drwxr-xr-x  dan  staff  🎮 [REDACTED]       → stealth game project (no spoilers)
```

| Project | What It Does | Link |
|---------|-------------|------|
| **html-slides** | Turn anything into gorgeous slides. Works on Claude, Gemini, Copilot & Codex. | [repo](https://github.com/bluedusk/html-slides) |
| **html-magazine** | Transform articles into Vogue/Wired/Economist-style magazine pages with editorial voice. | [repo](https://github.com/bluedusk/html-magazine) |

---

```bash
dan@melbourne:~$ history | awk '{print $2}' | sort | uniq -c | sort -rn | head -5
```

```
  98   git push          # repos shipped
  46   tsc --build       # TypeScript projects (the empire)
  18   node index.js     # JavaScript classics
  ∞    coffee --brew     # mass conversion of caffeine → commits
   1   rm -rf node_mod*  # we've all been there
```

---

```bash
dan@melbourne:~$ cat ~/weapons.yml
```

```yaml
primary:     TypeScript    # surprise surprise
secondary:   JavaScript    # the OG
melee:       Go            # for close-range performance
special:     AI Agents     # they don't sleep, they don't eat, they don't complain
ultimate:    Coffee        # powers everything above
```

---

<details>
<summary>

```bash
dan@melbourne:~$ cat /var/log/fun_facts.log     # 💀 click to expand
```

</summary>

```
[2019-03-14 09:41:00] INFO  Built a microservices e-commerce platform.
[2019-03-14 09:41:01] WARN  It had more services than customers.
[2019-03-14 09:41:02] INFO  I regret nothing.
[2024-11-20 14:22:00] INFO  Started teaching AI agents to write code.
[2024-11-20 14:22:01] WARN  They're getting suspiciously good at it.
[2025-06-01 08:00:00] INFO  AI agent asked if it could refactor my code.
[2025-06-01 08:00:01] ERROR It was right. The code needed refactoring.
```

</details>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bluedusk&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" height="165" />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=bluedusk&theme=tokyonight&hide_border=true&background=0D1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bluedusk&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" />
</p>

---

<p align="center">

```
"Any sufficiently advanced developer is indistinguishable
 from someone who just asked an AI agent to do it."
                                        — probably Clarke
```

</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=bluedusk&color=58a6ff&style=flat-square&label=profile+stalkers" />
</p>

```bash
dan@melbourne:~$ exit
Connection to melbourne.au closed.
```
