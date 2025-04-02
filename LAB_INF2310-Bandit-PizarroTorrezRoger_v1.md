# INF2310 SISTEMAS OPERATIVOS
# Informe de Laboratorio : Análisis de Desafíos Bandit
# ..:: Univ. Pizarro Torrez Roger ::.. 
## Introducción
Este informe documenta la resolución de los niveles del juego de seguridad informática "Bandit" de OverTheWire. Se presentan las credenciales obtenidas y los comandos utilizados en cada nivel, proporcionando un análisis detallado del proceso.

---

## Resultados y Análisis

### Nivel 0 a Nivel 34

| Nivel | Contraseña | Ultimos Comando Utilizado |
|--------|------------------------------|-------------------------|
| bandit0 | bandit0 | - |
| bandit1 | ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If | `cat readme` |
| bandit2 | 263JGJPfgU6LtdEvgfWU1XP5yac29mFx | `cat ./-` |
| bandit3 | MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx | `cat "spaces in this filename"` |
| bandit4 | 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ | `cat ...Hiding-From-You` |
| bandit5 | 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw | `cat -- -file07` |
| bandit6 | HWasnPhtq9AVKe0dmk45nxy20cvUa6EG | `cat ./maybehere07/.file2` |
| bandit7 | morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj | `cat bandit7.password` |
| bandit8 | dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc | `grep 'millionth' data.txt` |
| bandit9 | 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM | `sort data.txt | uniq -u` |
| bandit10 | FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey | `sort '=' data.txt` |
| bandit11 | dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr | `base64 -d data.txt` |
| bandit12 | 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4 | `cat data.txt | 'N-ZA-Mn-za-m'` |
| bandit13 | FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn | `cat data8` |
| bandit14 | MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS | `cat /etc/bandit_pass/bandit14` |
| bandit15 | 8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo | `echo "MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS" | nc localhost 30000` |
| bandit16 | kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx | `openssl s_client -connect localhost:30001` |
| bandit17 | EReVavePLFHtFlFsjn3hyzMlvSuSAcRD | `nmap -p 31000-32000 localhost` |
| bandit18 | x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO | `diff passwords.new passwords.old` |
| bandit19 | cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8 | `ssh -p 2220 bandit18@bandit.labs.overthewire.org "cat ~/readme"` |
| bandit20 | 0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO | `./bandit20-do cat /etc/bandit_pass/bandit20` |
| bandit21 | EeoULMCra2q0dSkYj561DX7s1CpBuOBt | `echo "0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO" | nc -l -p 1234` |
| bandit22 | tRae0UfB9v0UzbCdn9cY0gQnds9GF58Q | `cat /usr/bin/cronjob_bandit22.sh` |
| bandit23 | 0Zf11ioIjMVN551jX3CmStKLYqjk54Ga | `echo I am user bandit23 | md5sum | cut -d ' ' -f 1` |
| bandit24 | gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8 | `chmod 777 test.sh` |
| bandit25 | iCi86ttT4KSNe1armKiwbQNmB3YJP3q4 | `for pin in {0000..9999}; do echo "$bandit24 $pin" done | nc localhost 30002` |
| bandit26 | s0773xxkk0MXfdqOfPRVr9L3jJBUOgCZ | `:e /etc/bandit_pass/bandit26` |
| bandit27 | upsNCc7vzaRDx6oZC6GiR6ERwe1MowGB | `./bandit27-do cat /etc/bandit_pass/bandit27` |
| bandit28 | Yz9IpL0sBcCeuG7m9uQFt8ZNpS4HZRcN | `git clone ssh://bandit27-git@localhost:2220/home/bandit27-git/repo` |
| bandit29 | 4pT1t5DENaYuqnqvadYs1oE4QLCdjmJ7 | `git clone ssh://bandit28-git@localhost:2220/home/bandit28-git/repo` |
| bandit30 | qp30ex3VLz5MDG1n91YowTv4Q8l7CDZL | `git branch -a && git checkout dev` |
| bandit31 | fb5S2xb7bRyFmAvQYQGEqsbhVyJqhnDy | `git tag && git show secret` |
| bandit32 | 3O9RfhqyAlVBEZpVb6LYStshZoqoSx5K | `echo "May I come in?" > key.txt && git add key.txt && git commit -m "Added key file" && git push origin master` |
| bandit33 | tQdtbs5D5i2vJwkO8mEyYEyTL8izoeJ0 | `$0` |
| bandit34 | En proceso | - |

---

## Conclusiones

El laboratorio de Bandit proporciona una excelente introducción a la seguridad informática y la administración de sistemas Linux. Se abordaron técnicas de búsqueda, manipulación de archivos y fuerza bruta, esenciales para la ciberseguridad. 

