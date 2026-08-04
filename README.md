```console
avi@arch:~$ ./welcome.sh
```

```console
🟢 Started graphical session (wayland)
🟢 Reached target Homelab
🟢 Mounted /dev/coffee
🟡 5 tests flaky, investigating
🟢 Started welcome.sh - avi@arch
```

```console
avi@arch
---------
OS: Arch Linux x86_64
Shell: fish
Editor: zed
Location: Montevideo, UY
```

```console
QA automation engineer @ Qubika · learning Rust & Python
Homelab and infrastructure enthusiast
Open source contributor - upstream PRs and AUR packages
Wrote Chisp8, a Chip8 interpreter in C# (hobby project)
Montevideo, UY · any pronouns
```

<details>
<summary>avi@arch:~$ ls ~/contributions</summary>

```console
total 4
OptiScaler/   C++ - GPU upscaling / frame-gen bridge
Glass/       C++ - KDE Plasma blur/glass effect
AUR/         Arch - packages I maintain
Chisp8/       C# - Chip8 interpreter (hobby project)
```
</details>

<details>
<summary>avi@arch:~$ systemctl status avi.service</summary>

```console
● avi.service - QA automation engineer
     Loaded: loaded (/etc/systemd/system/avi.service; enabled)
     Active: 🟢 active (running)
   Main PID: 1 (avi)
      Tasks: 42 (limit: 98304)
     Memory: 2.5G (mostly /dev/coffee)
     Status: "Writing tests that pass on the first run"
```
</details>

<details>
<summary>avi@arch:~$ sudo pacman -S --noconfirm coffee</summary>

```console
[sudo] password for avi:
resolving dependencies... done
🟡 warning: coffee-2.0 is up to date - already installed
:: Nothing to do.
```
</details>

<details>
<summary>avi@arch:~$ ./welcome.sh --help</summary>

```console
Usage: avi [OPTIONS]
  --about          read my bio
  --contributions  open source work
  --homelab         status of my self-hosted services
  --email           say hi
  --easter-egg      there is one. find it.
```
</details>

---

say hi: [avi@babi.uy](mailto:avi@babi.uy) · site: [avitretiak.dev](https://avitretiak.dev)
