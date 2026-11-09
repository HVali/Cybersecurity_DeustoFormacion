<h1 align="center">Cybersecurity Portfolio</h1>

<p align="center">Computer forensics, security auditing, server hardening, wireless security and data protection compliance</p>

---

This repository contains the cybersecurity projects I completed during the Curso Superior de Ciberseguridad at Deusto Formación. I finished the 200-hour course with a final grade of 9.9. These projects show the knowledge I gained.

Each project includes the documentation as I submitted it to the course, in Spanish, and a full English version.

## Index

- [Projects](#projects)
  - [Final Project – USB Forensic Analysis](#final-project--usb-forensic-analysis)
  - [Wi-Fi Network Security Analysis](#wi-fi-network-security-analysis)
  - [Information Asset Identification](#information-asset-identification)
  - [GDPR Implementation](#gdpr-implementation)
  - [Secure Web Server on Ubuntu](#secure-web-server-on-ubuntu)
  - [Browsing History Recovery](#browsing-history-recovery)
- [Skills](#skills)
- [Tools](#tools)
- [Course and Certificate](#course-and-certificate)

---

## Projects

| Project | Type | Documentation |
|---|---|---|
| [Final Project – USB Forensic Analysis](Final%20Project) | Computer forensics | [EN](Final%20Project/Final_Project_USB_Forensic_Analysis_Valentina_Hatos.pdf) · [ES](Final%20Project/Proyecto_Final_Analisis_Forense_USB_Valentina_Hatos.pdf) |
| [Wi-Fi Network Security Analysis](Wi-Fi%20Network%20Security%20Analysis) | Wireless security | [EN](Wi-Fi%20Network%20Security%20Analysis/WiFi_Security_Analysis_Valentina_Hatos.pdf) · [ES](Wi-Fi%20Network%20Security%20Analysis/Analisis_Seguridad_Red_WiFi_Valentina_Hatos.pdf) |
| [Information Asset Identification](Information%20Asset%20Identification) | Security audit | [EN](Information%20Asset%20Identification/Information_Asset_Identification_Valentina_Hatos.pdf) · [ES](Information%20Asset%20Identification/Identificacion_Activos_Informacion_Valentina_Hatos.pdf) |
| [GDPR Implementation](GDPR%20Implementation) | Data protection compliance | [EN](GDPR%20Implementation/GDPR_Implementation_AgroVerdeDeusto_Valentina_Hatos.pdf) · [ES](GDPR%20Implementation/Implementacion_RGPD_AgroVerdeDeusto_Valentina_Hatos.pdf) |
| [Secure Web Server on Ubuntu](Secure%20Web%20Server%20Ubuntu) | Server hardening | [EN](Secure%20Web%20Server%20Ubuntu/Secure_Web_Server_Ubuntu_Valentina_Hatos.pdf) · [ES](Secure%20Web%20Server%20Ubuntu/Servidor_Web_Seguro_Ubuntu_Valentina_Hatos.pdf) |
| [Browsing History Recovery](Browsing%20History%20Recovery) | Computer forensics | [EN](Browsing%20History%20Recovery/Browsing_History_Recovery_Autopsy_Valentina_Hatos.pdf) · [ES](Browsing%20History%20Recovery/Recuperacion_Historial_Navegacion_Autopsy_Valentina_Hatos.pdf) |

### Final Project – USB Forensic Analysis

I carried out the forensic analysis of a USB pendrive, following UNE standards and Spanish legislation. I created a bit-by-bit E01 image with FTK Imager and verified its integrity with MD5 and SHA1 hashes. I analysed the image in Autopsy, recovered 3 deleted files and documented their metadata. The result is an expert report with 3 annexes.

### Wi-Fi Network Security Analysis

I scanned my Wi-Fi network with Acrylic Analyzer before and after changing the router password to a strong 20-character password. I compared the Network Quality scores (6/10 before, 7/10 after) and explained what the scanner measures.

### Information Asset Identification

As part of a security audit for a real estate agency with a LAN, a central server and ten workstations, I identified 21 information assets: 7 physical, 7 logical and 7 records. I registered each asset in Dradis Framework and listed the risks found.

### GDPR Implementation

I used the Facilita RGPD tool of the Spanish Data Protection Agency (AEPD) to generate the compliance documentation for a company that sells plant protection products. I wrote a practical implementation report: information clauses, contracts with 3 data processors, video surveillance, security measures, staff training and a procedure for handling data subject rights requests.

### Secure Web Server on Ubuntu

I installed and configured Apache on Ubuntu Server in a VirtualBox virtual machine. I opened HTTP and HTTPS traffic in the UFW firewall, created a self-signed SSL certificate with OpenSSL and enabled HTTPS.

### Browsing History Recovery

I verified that Autopsy can recover the browsing history of Google Chrome after it was deleted in the usual way. I analysed the Web History results and generated an Excel report of the case.

---

## Skills

| Area | What I can do | Where you can see it |
|---|---|---|
| Forensic acquisition | Identify and label evidence, create a bit-by-bit E01 image and verify its integrity with hashes | [Final Project](Final%20Project) |
| Forensic analysis | Analyse a forensic image or logical files in Autopsy, recover deleted files and browsing history, and collect metadata | [Final Project](Final%20Project), [Browsing History Recovery](Browsing%20History%20Recovery) |
| Forensic reporting | Write expert reports structured according to UNE 197010, UNE 71505 and UNE 71506 | [Final Project](Final%20Project), [Browsing History Recovery](Browsing%20History%20Recovery) |
| Security auditing | Build an inventory of physical, logical and record assets and identify the related risks | [Information Asset Identification](Information%20Asset%20Identification) |
| Server hardening | Install a web server, configure the firewall and enable HTTPS with an SSL certificate | [Secure Web Server on Ubuntu](Secure%20Web%20Server%20Ubuntu) |
| Wireless security | Scan a Wi-Fi network, interpret the results and apply a strong password policy | [Wi-Fi Network Security Analysis](Wi-Fi%20Network%20Security%20Analysis) |
| Data protection | Prepare GDPR compliance documentation and internal procedures for a company | [GDPR Implementation](GDPR%20Implementation) |

---

## Tools

| Tool | What I used it for |
|---|---|
| FTK Imager | Forensic E01 image and hash verification |
| Autopsy | Forensic analysis, recovery of deleted files and browsing history, metadata and reports |
| Dradis Framework | Registering the information assets of the audit |
| Kali Linux | Environment for Dradis Framework |
| Acrylic Analyzer | Wi-Fi network scanning |
| Ubuntu Server, Apache, UFW, OpenSSL | Web server, firewall and SSL certificate |
| Oracle VirtualBox | Virtual machines for the lab environments |
| Facilita RGPD (AEPD) | GDPR compliance documentation |

---

## Course and Certificate

| | Details |
|---|---|
| Course | Curso Superior de Ciberseguridad |
| Provider | Deusto Formación |
| Duration | 200 hours |
| Start date | 02/07/2024 |
| Diploma awarded | 09/01/2026 |
| Final grade | 9.9 |
| Certificate | [Certificado - Calificacion.pdf](Certificado%20-%20Calificacion.pdf) |
