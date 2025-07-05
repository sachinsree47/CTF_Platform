# 🎯 CTF Training Platform

The CTF Training Platform is a self-contained lab environment designed to help students learn ethical hacking, penetration testing, and real-world vulnerability exploitation in a safe and legal setting. Built using Docker and open-source tools, it features intentionally vulnerable applications, a modern scoreboard system, and a collection of custom-made challenges across different categories.

This project is ideal for educational institutions, cybersecurity clubs, and independent learners who want to build practical offensive security skills.

---

## 🧠 What's Inside

This platform includes three major components:

- **CTFd** – A lightweight, modern Capture The Flag (CTF) scoreboard for managing users, challenges, hints, and scoreboards.
- **DVWA (Damn Vulnerable Web Application)** – A classic web app designed to expose users to common web vulnerabilities such as SQLi, XSS, and command injection.
- **OWASP Juice Shop** – One of the most modern and realistic vulnerable web apps, packed with dozens of hidden vulnerabilities.

Alongside these tools, the platform also includes a custom set of beginner-friendly challenges organized by category. Each challenge comes with its own flag, task description, and writeup for learning after completion.

---

## 🎮 Challenges

The platform includes hands-on CTF challenges in categories such as web, crypto, and miscellaneous. These are designed to help students practice real-world attack techniques while learning the underlying security flaws.

Each challenge includes a clear task description (`challenge.md`), a hidden flag, and an optional `writeup.md` that explains the solution. This structure promotes both self-practice and guided learning, making it ideal for training sessions, workshops, and classroom environments.

---

## 🌐 Accessing the Platform

Once the services are running, users can access:

- **CTFd scoreboard** at `http://localhost:8000`
- **DVWA** at `http://localhost:8081`
- **Juice Shop** at `http://localhost:3000`

The platform runs entirely in Docker, allowing for quick deployment and clean resets. No external setup is required beyond Docker and Git.

---

## 🧑‍🎓 Educational Impact

This platform is built to support **learning-first** cybersecurity education. Unlike competitive CTFs focused on difficulty, this environment encourages students to understand the vulnerabilities, test ideas, and read solutions after solving each challenge.

It’s a project with lasting impact — providing safe, practical, and fun hacking experience for aspiring ethical hackers.

---

## 🛡️ Legal & Ethical Notice

This project is intended for educational and ethical hacking purposes **only**. Do not use this platform or any of its components in unauthorized environments or for malicious purposes. Always operate within a controlled network and with proper permissions.

---

## ❤️ Credits

Special thanks to the amazing open-source communities that made this possible:

- [CTFd](https://github.com/CTFd/CTFd)
- [DVWA](https://github.com/digininja/DVWA)
- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)

---

## 📬 Contact

Made with ❤️ by students, for students. Contributions, suggestions, and feedback are always welcome.
