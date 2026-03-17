<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   $ whoami                                                  │
│   > Sakwa — Full Stack Engineer                             │
│                                                             │
│   $ cat philosophy.txt                                      │
│   > Build it right. Ship it fast. Secure it first.         │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&pause=1000&color=00FF88&center=true&vCenter=true&width=500&lines=Laravel+%7C+Vue+%7C+Docker+%7C+Redis;Security-first+architecture;Production+systems+that+don't+break;17hrs+fasted+%2B+shipping+code)](https://git.io/typing-svg)

</div>

---

## `$ ls -la /skills`

```php
$stack = [
    'backend'  => ['Laravel 12', 'Node.js', 'Django', 'Flask', '.NET Core'],
    'frontend' => ['Vue 3', 'React', 'TypeScript', 'Flutter'],
    'infra'    => ['Docker', 'Nginx', 'Redis', 'Prometheus', 'Grafana'],
    'database' => ['MySQL', 'PostgreSQL', 'MongoDB', 'Redis'],
    'security' => ['Sanctum', 'OAuth2', 'TOTP/2FA', 'Webhook Signing', 'OWASP'],
    'langs'    => ['PHP', 'Python', 'JavaScript', 'TypeScript', 'C', 'Java'],
];
```

---

## `$ cat approach.md`

> I don't just build features — I build systems.  
> Every endpoint is authorized. Every webhook is signed.  
> Every query is scoped. Every token is revocable.

**What that looks like in practice:**
- Multi-layer auth: Sanctum tokens + 2FA + trusted devices + session tracking
- Audit trails on every model mutation, every login, every payment
- Webhook handlers with pessimistic locks — race conditions don't exist here
- Observability stack: Redis metrics → Prometheus → Grafana, live in production
- GDPR-compliant account deletion with PII anonymization before soft delete

---

## `$ docker ps` — What I'm running

```
CONTAINER           STATUS        PORTS
eldorent_php        Up            Laravel 12 API
eldorent_nginx      Up            8100->80
eldorent_redis      Up            6381->6379
eldorent_reverb     Up            8181->8081 (WebSockets)
eldorent_prometheus Up            9190->9090
eldorent_grafana    Up            3100->3000
eldorent_mysql      Up (healthy)  3308->3306
mailhog             Up            8126->8025
```

*Real estate listing platform — multi-provider payments (M-Pesa, Stripe, Paystack, PesaPal), real-time notifications, role-based access, full audit trail.*

---

## `$ cat /proc/stats`

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Bsakwa&show_icons=true&theme=transparent&hide_border=true&title_color=00FF88&icon_color=00FF88&text_color=CCCCCC&count_private=true&ring_color=00FF88" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bsakwa&layout=compact&theme=transparent&hide_border=true&title_color=00FF88&text_color=CCCCCC&langs_count=8" />

<img width="90%" src="https://github-readme-activity-graph.vercel.app/graph?username=Bsakwa&theme=react-dark&hide_border=true&bg_color=0D1117&color=00FF88&line=00FF88&point=FFFFFF&area=true&area_color=00FF8820" />

</div>

---

## `$ ping Bsakwa`

```bash
# I respond to:
- Architecture discussions
- Security reviews  
- Interesting problems that need elegant solutions
- Collaboration on systems that actually need to work

# I don't respond to:
- "can you do this for free real quick"
- Tutorial-level questions Google can answer
```

<div align="center">

[![GitHub](https://img.shields.io/badge/github-Bsakwa-00FF88?style=flat-square&logo=github&logoColor=white&labelColor=0D1117)](https://github.com/Bsakwa)

```
uptime: always learning
kernel: security-hardened
status: building
```

<img src="https://komarev.com/ghpvc/?username=Bsakwa&color=00FF88&style=flat-square&label=visitors" />

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="contribution snake" />

</div>
