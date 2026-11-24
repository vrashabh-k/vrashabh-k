<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1200&color=2F81F7&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+Vrashabh+%F0%9F%91%8B;Full-stack+developer+%C2%B7+Bengaluru%2C+India;I+build+things+with+React%2C+Node+%26+Python;Now+exploring%3A+monitoring%2C+automation+%26+AI%2FML" alt="Typing intro" />

[![Portfolio](https://img.shields.io/badge/Portfolio-vrashabh--k.github.io-2F81F7?style=for-the-badge&logo=githubpages&logoColor=white)](https://vrashabh-k.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-vrashabh--k-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vrashabh-k)
[![Email](https://img.shields.io/badge/Email-vvkam17%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vvkam17@gmail.com)

</div>

---

## `$ whoami`

```python
class Vrashabh:
    role      = "Full-stack developer (B.E. Computer Science, KLE Tech)"
    based_in  = "Bengaluru, India"
    works_on  = "Enterprise web applications at RCS Tech"
    good_at   = ["debugging", "tracing a bug to its root cause", "REST APIs", "React UIs"]
    exploring = ["observability", "anomaly detection", "automation", "AI/ML"]
    won       = "1st prize, a rope-climbing robot project (2022)"

    def open_to(self):
        return "software engineering roles, collaborations, and good coffee"
```

## 🚀 Featured project: Service Health Monitor

> A mini observability platform. It watches microservices, **learns what "normal" looks like by itself**, and flags unusual latency or errors within seconds, with a dashboard a manager can read.

```
 customers ──> orders ──> payments
                  └─────> inventory
                              │ metrics every 5s
                         Prometheus ──> Grafana
                              │
                  Detector (Python + scikit-learn)
                              │
                       React dashboard
```

- **Detects** slow responses and failing requests using a robust z-score plus an Isolation Forest.
- **Explains** itself: a plain-English summary, a likely root cause (when Orders is slow because Payments is), and live charts.
- **Lets you break things safely:** inject a fault, then watch it get detected and cleared.
- Runs with one command: `docker compose up --build`.

<details>
<summary><b>How does it spot problems?</b></summary>

1. Every 5 seconds it reads the last 15 minutes of p95 latency and error rate from Prometheus.
2. It compares "now" with that service's own baseline using median and MAD, so earlier spikes don't hide new ones.
3. An Isolation Forest checks whether latency and errors look unusual *together*.
4. A z-score above 4 raises a warning; agreement from the forest, or a very large score, makes it critical.

</details>

[**View the repo →**](https://github.com/vrashabh-k/service-health-monitor)

## 🧰 Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=js,py,cpp,react,nodejs,express,flask,mongodb,mysql,docker,linux,git,prometheus,grafana" alt="Tech stack" />
</p>

`JavaScript` `Python` `C++` `SQL` `REST APIs` `scikit-learn` `Postman` `Log analysis`

## 🌱 Currently

- 🔭 Building out observability: alerting, incident grouping, CI/CD
- 📚 Learning Go, Kubernetes and more distributed-systems fundamentals
- 💬 Ask me about debugging production-style issues, or how anomaly detection works

## 🐍 Contribution snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vrashabh-k/vrashabh-k/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/vrashabh-k/vrashabh-k/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/vrashabh-k/vrashabh-k/output/github-snake.svg" />
</picture>

---

<div align="center">

```bash
$ ./connect.sh --with vrashabh
> Opening https://vrashabh-k.github.io ... done
```

</div>
