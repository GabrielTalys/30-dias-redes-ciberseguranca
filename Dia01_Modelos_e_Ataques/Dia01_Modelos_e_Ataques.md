# 📅 Dia 1 – Modelos OSI vs TCP/IP + Ataques por Camada (Foco em Cibersegurança)

Este é o primeiro dia do meu desafio de **30 dias estudando Redes com foco em Cibersegurança**.

---

## 🔷 Modelos OSI e TCP/IP

### 🧱 Modelo OSI – 7 camadas

| Nº | Camada            | Função Principal                                |
|----|-------------------|--------------------------------------------------|
| 7  | Aplicação          | Interface com o usuário e serviços de rede (HTTP, FTP) |
| 6  | Apresentação       | Codificação, criptografia, compressão           |
| 5  | Sessão             | Gerenciamento de sessões e conexões             |
| 4  | Transporte          | Controle de fluxo, confiabilidade (TCP, UDP)    |
| 3  | Rede                | Endereçamento e roteamento (IP, ICMP)           |
| 2  | Enlace de Dados     | Comunicação entre dispositivos na mesma rede    |
| 1  | Física              | Transmissão física de bits (cabos, sinais)      |

---

### 🌐 Modelo TCP/IP – 4 camadas

| Camada TCP/IP      | Equivalente OSI                    | Função                                           |
|--------------------|-------------------------------------|--------------------------------------------------|
| Aplicação           | Aplicação + Apresentação + Sessão  | Interface com software (HTTP, DNS, SMTP...)     |
| Transporte          | Transporte                         | TCP, UDP – envio confiável ou rápido             |
| Internet            | Rede                               | IP, ICMP, roteamento                             |
| Acesso à Rede       | Enlace + Física                    | Comunicação direta com o hardware de rede        |

---

## 🛡️ Ataques por camada – Modelo OSI

| Camada OSI         | Exemplos de Ataques                          | Ferramentas e Técnicas                 |
|--------------------|----------------------------------------------|----------------------------------------|
| Aplicação (7)      | Phishing, SQL Injection, Buffer Overflow     | Burp Suite, SQLmap, OWASP ZAP          |
| Apresentação (6)   | Arquivos maliciosos, codificação manipulada  | Binwalk, engenharia reversa            |
| Sessão (5)         | Session Hijacking, roubo de tokens/cookies   | Wireshark, Cookie Editor               |
| Transporte (4)     | SYN Flood, TCP Reset, UDP Flood              | hping3, Scapy                          |
| Rede (3)           | IP Spoofing, DDoS, roteamento malicioso      | LOIC, Nemesis, traceroute              |
| Enlace (2)         | ARP Spoofing, MAC Flooding                   | Ettercap, Macof, Yersinia              |
| Física (1)         | Escutas, cortes de cabo, jamming             | Sniffers físicos, ferramentas de hardware |

---

## 🧠 Conclusão do dia

> Compreender como os modelos OSI e TCP/IP estruturam a comunicação de rede me ajudou a identificar onde os ataques realmente ocorrem.  
> Saber **qual camada é afetada** torna possível aplicar defesas mais precisas e eficazes.  
>  
> Isso é a base para qualquer profissional de cibersegurança.
