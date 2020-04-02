# Seedlab

Records & Reports for Seedlabs (https://seedsecuritylabs.org/) on Ubuntu 16.04

---

## Build

To generate `pdf` README of each lab, enter the corresponding folder and use

```
pandoc -s -listings -H ../code_style.tex -o readme.pdf README.MD
```

---

## References

Du, W. (2019). [*Computer & Internet Security: A Hands-on Approach.*](https://www.handsonsecurity.net/) Wenliang Du.

Export `bibtex` as:

```bibtex
@book{du2019computer,
  title={Computer \& Internet Security: A Hands-on Approach},
  author={Du, W.},
  isbn={9781733003933},
  url={https://books.google.com/books?id=HclQxQEACAAJ},
  year={2019},
  publisher={Wenliang Du}
}
```

Besides,

### Thanks to

- Some code from the seed book: https://github.com/kevin-w-du/BookCode
- Figures in the seed book: https://www.handsonsecurity.net/files/misc/SEEDBook_figs_2nd.pdf 

---

## To-do List

Ref: http://www.cis.syr.edu/~wedu/seed/toc.pdf

- [ ] Software Security
    - [x] [Buffer Overflow Vulnerability Lab](./Buffer-Overflow)
    - [ ] [Return-to-libc Attack Lab](./Return-to-libc-Attack)
        - [x] Task 1-5
        - [ ] Task 6
    - [x] [Format String Vulnerability Lab](./Format-String-Vulnerability)
    - [x] [Race Condition Vulnerability Lab](./Race-Condition-Vulnerability)
    - [x] [Environment Variable and Set-UID Lab](Environment-Variable-and-Set-UID-Program-Lab)
    - [x] [Shellshock Attack Lab](./Shellshock-Attack)
    - [ ] *Dirty COW Attack Lab*
- [ ] Web Security
    - [ ] Cross-Site Request Forgery Attack Lab
    - [ ] Cross-Site Scripting Attack Lab
    - [ ] SQL Injection Attack Lab
- [ ] Network Security
    - [x] [Packet Sniffing & Spoofing Lab](./Packet-Sniffing-and-Spoofing)
    - [x] [TCP Attack Lab](./TCP-IP-Attack)
    - [x] [Linux Firewall Lab](./Firewall-Exploration)
    - [ ] [Bypassing Firewall using VPN](./Firewall-VPN)
    - [ ] Local DNS Attack Lab
    - [ ] Remote DNS Cache Poisoning Attack Lab
    - [ ] [*Heartbleed Attack Lab (only for `ubuntu` 16.04)*](./Heartbleed-Attack)
    - [ ] VPN Lab
- [ ] Crypto
    - [ ]  [Secret-Key Encryption Lab](./Secret-Key-EncryptionD)
    - [ ]  Pseudo Random Number Generation Lab
    - [ ]  MD5 Collision Attack Lab
    - [ ]  RSA Encryption and Signature Lab
    - [ ]  Public-Key Infrastructure (PKI) Lab
    - [ ]  Man-In-The-Middle (MITM) Attack Lab
- [x] System Security
    - [x] [Meltdown Attack Lab](./Meltdown-Attack)
    - [x] [Spectre Attack Lab](./Spectre-Attack)
- [ ] Mobile Security
    - [ ] Android Repackaging Attack Lab
    - [ ] Android Rooting Lab
    - [ ] Android ClickJacking Attack Lab