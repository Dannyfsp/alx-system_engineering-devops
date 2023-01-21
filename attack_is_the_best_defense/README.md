## Attack is the best defense
A readme on an optional project on Security and Network sniffing given by ALX.
### Concepts
*For this project, we are expected to look at these concepts:*
- [Network basics](https://intranet.alxswe.com/concepts/33)
- [Docker](https://intranet.alxswe.com/concepts/65)
### Background Context
#### Resources
**Read or watch:**
- [Network sniffing](https://intranet.alxswe.com/rltoken/eF4956aQFYnhS_i6IF9R-g)
- [ARP spoofing](https://intranet.alxswe.com/rltoken/RK-4WtV0YCSETDSG9lr1hw)
- [Connect to SendGrid's SMTP relay using telnet](https://intranet.alxswe.com/rltoken/twuD5E9_-V2z1zfW5nXyyg)
- [What is Docker and why is it popular](https://intranet.alxswe.com/rltoken/56VrRmkBHFq2OKLM_FQA6w)
- [Dictionary attack](https://intranet.alxswe.com/rltoken/dbAwbf71VVSCTOfeR1NRmg)
**man or help:**
- `tcpdump`
- `hydra`
- `telnet`
- `docker`

#### 1.Dictionary attack
Password-based authentication systems can be easily broken by using a dictionary attack (we’ll have to find our own password dictionary).
Let's try it on an SSH account.
- Install Docker on your machine ubuntu
- Pull and run the Docker image `sylvainkalache/264-1` with the command `docker run -p 2222:22 -d -ti sylvainkalache/264-1`
- Find a password dictionary (you might need multiple of them)
- nstall and use `hydra` to try to brute force the account `sylvain` via SSH on the Docker container
- Because the Docker container is running locally, `hydra` should access the SSH account via IP `127.0.0.1` and port `2222`
- Hint: the password is 11 characters long
**Answer file:** `1-dictionary_attack`
