```
 ____            _                          _     _
|  _ \ _ __ ___ | |_ __ _  __ _  ___  _ __ (_)___| |_ ___ ___
| |_) | '__/ _ \| __/ _` |/ _` |/ _ \| '_ \| / __| __/ __/ __|
|  __/| | | (_) | || (_| | (_| | (_) | | | | \__ \ |_\__ \__ \
|_|   |_|  \___/ \__\__,_|\__, |\___/|_| |_|_|___/\__|___/___/
                          |___/
```

```bash
$ whoami
> Protagonistss

$ cat /etc/motd
> A passionate developer navigating the matrix.
> Currently deep-diving into Rust 🦀

$ cat ~/.interests
> ["Rust", "JavaScript", "Open Source", "Systems Programming"]

$ echo $EDITOR
> vim
```

---

```rust
// src/me.rs

#[derive(Debug)]
struct Developer<'a> {
    name: &'a str,
    role: &'a str,
    interests: Vec<&'a str>,
    editor: &'a str,
}

impl<'a> Developer<'a> {
    fn new() -> Self {
        Developer {
            name: "Protagonistss",
            role: "Full-Stack Developer",
            interests: vec!["Rust 🦀", "JavaScript 💛", "Vue", "React"],
            editor: "Vim ✨",
        }
    }

    fn say_hi(&self) {
        println!("Always open to collaborate on interesting projects!");
        println!("Feel free to reach out 😁");
    }
}
```

---

```bash
$ ls ~/tech-stack/

languages/    rust  javascript  typescript  python  java  c++
frameworks/   react  vue  node.js
tools/        vim  git  linux  docker
```

---

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Protagonistss&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&bg_color=00000000">
    <img height="170" src="https://github-readme-stats.vercel.app/api?username=Protagonistss&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=true" />
  </picture>
  &nbsp;&nbsp;
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Protagonistss&layout=compact&theme=github_dark&hide_border=true&bg_color=00000000">
    <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Protagonistss&layout=compact&theme=default&hide_border=true" />
  </picture>
</div>

---

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Protagonistss/Protagonistss/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Protagonistss/Protagonistss/output/github-contribution-grid-snake.svg">
    <img alt="contribution snake" src="https://raw.githubusercontent.com/Protagonistss/Protagonistss/output/github-contribution-grid-snake.svg">
  </picture>
</div>

---

<div align="center">
  <sub>// auto-updated daily via GitHub Actions</sub>
</div>
