# 🎯 HackTheBox Writeups

<div align="center">


Colección de writeups técnicos documentando metodologías de pentesting, análisis de vulnerabilidades y técnicas de explotación.

</div>

---

## 👤 Sobre Mí

**Yasmin Jiménez Bravo** | Junior Cybersecurity Specialist

- 🎓 **Formación**: Máster en Ciberseguridad & IA (Evolve Academy, 2025)
- 🔐 **Especialización**: Pentesting, Active Directory Exploitation, Security Analysis
- 🏆 **HackTheBox**: `yas7727` 
- 💼 **Objetivo**: Primer rol profesional como Pentester / SOC Analyst / Security Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yasmin-jiménez-bravo/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yasmin271091)
[![HackTheBox](https://img.shields.io/badge/HackTheBox-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=white)](https://app.hackthebox.com/profile/yas7727)

---

## 📋 Máquinas Completadas

### 🪟 Windows Systems

| Máquina | Dificultad | OS | Técnicas Principales | Writeup |
|---------|-----------|-----|---------------------|---------|
| **Devel** | ![Easy](https://img.shields.io/badge/Easy-brightgreen) | Windows 7 | FTP Anonymous Write to IIS Webroot, ASPX Webshell Upload, MS10-015 (KiTrap0D) Privilege Escalation | [📄 PDF](./Devel/HTB_Devel_Writeup.pdf) \| [📝 DOCX](./Devel/HTB_Devel_Writeup.docx) |
| **Optimum** | ![Easy](https://img.shields.io/badge/Easy-brightgreen) | Windows Server 2012 R2 | CVE-2014-6287 (HFS 2.3 RCE), MS16-032 Privilege Escalation | [📄 PDF](./Optimum/HTB_Optimum_Writeup.pdf) |
| **Grandpa** | ![Easy](https://img.shields.io/badge/Easy-brightgreen) | Windows Server 2003 SP2 | CVE-2017-7269 (IIS 6.0 WebDAV), MS14-058 Privilege Escalation, Process Migration | [📄 PDF](./Grandpa/HTB_Grandpa_Writeup.pdf) |
| **Active** | ![Easy](https://img.shields.io/badge/Easy-brightgreen) | Windows Server 2008 | GPP Password Abuse, Kerberoasting, AD Exploitation | 🔜 Próximamente |

### 🐧 Linux Systems

| Máquina | Dificultad | OS | Técnicas Principales | Writeup |
|---------|-----------|-----|---------------------|---------|
| _Próximamente..._ | - | - | - | - |

---

## 🛠️ Técnicas y Herramientas

### Reconnaissance & Enumeration
```bash
Nmap • Masscan • Gobuster • Dirb • Enum4linux • SMBclient • LDAP enumeration
```

### Web Exploitation
```bash
Burp Suite • OWASP ZAP • SQLmap • XSS • CSRF • LFI/RFI • WebDAV exploitation
```

### Active Directory
```bash
BloodHound • Impacket • CrackMapExec • Rubeus • Mimikatz • Kerberoasting • GPP abuse
```

### Privilege Escalation
```bash
WinPEAS • LinPEAS • GTFOBins • Kernel exploits • SUID abuse • Sudo misconfigurations
```

### Post-Exploitation
```bash
Metasploit • PowerShell Empire • Lateral movement • Persistence • Credential dumping
```


## 📖 Estructura de Writeups

Cada writeup incluye:

1. **Información de la Máquina** - OS, dificultad, IP
2. **Reconocimiento** - Escaneos y enumeración
3. **Explotación Inicial** - Vectores de ataque y foothold
4. **Post-Explotación** - Estabilización y movimiento lateral
5. **Escalada de Privilegios** - Técnicas utilizadas para obtener root/SYSTEM
6. **Flags** - Captura de user.txt y root.txt
7. **Vulnerabilidades Identificadas** - CVEs y análisis
8. **Lecciones Aprendidas** - Insights técnicos
9. **Recomendaciones** - Remediación y mejores prácticas


## 📝 Metodología

Todos los writeups siguen una metodología profesional de pentesting:
```
1. Reconnaissance
   └── Port scanning, service enumeration
   
2. Vulnerability Assessment
   └── CVE research, exploit identification
   
3. Exploitation
   └── Initial access, foothold establishment
   
4. Post-Exploitation
   └── Privilege escalation, lateral movement
   
5. Reporting
   └── Documentation, remediation advice
```

---


## ⚠️ Disclaimer

> **Nota Importante**: Todos los writeups publicados corresponden a **máquinas retiradas** de HackTheBox, siguiendo las [políticas oficiales](https://www.hackthebox.com/tos) de la plataforma. Este contenido es **exclusivamente educativo** y para fines de investigación en ciberseguridad.


## 📬 Contacto

¿Interesado en colaborar o discutir sobre ciberseguridad?

- 📧 Email: yasmin27101991@gmail.com
- 💼 LinkedIn: [yasmin-jiménez-bravo](https://www.linkedin.com/in/yasmin-jiménez-bravo/)
- 🐙 GitHub: [@Yasmin271091](https://github.com/Yasmin271091)

---

<div align="center">

**⭐ Si estos writeups te resultan útiles, considera dar una estrella al repositorio ⭐**

Made with 💙 by Yasmin | © 2025
