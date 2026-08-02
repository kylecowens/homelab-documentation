<div align="center">

# Vertex Homelab Documentation

### Self-hosted infrastructure designed and operated by Kyle Cowens

[![Vertex Homelab](https://img.shields.io/badge/Vertex%20Homelab-Self--Hosted%20Infrastructure-69FF5C?style=for-the-badge&labelColor=0B3C68)](https://vertexhomelab.co.uk)
[![Location](https://img.shields.io/badge/Location-Guernsey-0B3C68?style=for-the-badge)](https://vertexhomelab.co.uk/kyle-cowens/)
[![Linux](https://img.shields.io/badge/Linux-Infrastructure-0B3C68?style=for-the-badge&logo=linux&logoColor=white)](#technology)
[![Docker](https://img.shields.io/badge/Docker-Containers-0B3C68?style=for-the-badge&logo=docker&logoColor=white)](#technology)

Public, sanitised documentation covering the architecture, operation and recovery principles behind Vertex Homelab.

[Website](https://vertexhomelab.co.uk) ·
[Kyle Cowens](https://vertexhomelab.co.uk/kyle-cowens/) ·
[GitHub Profile](https://github.com/kylecowens)

</div>

---

## About the project

**Vertex Homelab** is a privately operated self-hosted infrastructure platform based in Guernsey.

It was designed and is maintained by **Kyle Cowens**, with an emphasis on reliable service delivery, controlled remote access, clear documentation and recoverable configurations.

The environment combines Linux-based systems, Docker containers, network storage, private cloud services and Cloudflare-managed external access.

---

## Core principles

<table>
<tr>
<td width="50%" valign="top">

### Documented

Services, configurations and recovery procedures should be understandable without relying on memory.

</td>
<td width="50%" valign="top">

### Recoverable

A service is not properly maintained unless its data and configuration can be restored.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Separated

Business, personal, storage and media workloads should remain logically separated.

</td>
<td width="50%" valign="top">

### Controlled

Only necessary services should be exposed externally, using managed and documented access paths.

</td>
</tr>
</table>

---

## Infrastructure areas

### Systems administration

- Linux and Debian administration
- OpenMediaVault
- Docker container deployment
- Service maintenance and troubleshooting
- Filesystem and storage management
- Configuration documentation

### Networking and access

- Cloudflare Tunnel
- Reverse-proxy routing
- Secure remote access
- DNS management
- Service hostname management
- Reduced public port exposure

### Storage and recovery

- Encrypted storage
- Backup planning
- Configuration archives
- Recovery documentation
- Service continuity
- Data separation

### Hosted services

The wider platform includes services for:

- Private cloud storage
- File synchronisation
- Media management
- Music streaming
- Photo management
- Service requests
- Technical documentation

---

## Technology

<div align="center">

![Linux](https://img.shields.io/badge/Linux-0B3C68?style=flat-square&logo=linux&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-0B3C68?style=flat-square&logo=debian&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0B3C68?style=flat-square&logo=docker&logoColor=white)
![OpenMediaVault](https://img.shields.io/badge/OpenMediaVault-0B3C68?style=flat-square)
![Cloudflare](https://img.shields.io/badge/Cloudflare-0B3C68?style=flat-square&logo=cloudflare&logoColor=white)
![Nextcloud](https://img.shields.io/badge/Nextcloud-0B3C68?style=flat-square&logo=nextcloud&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-0B3C68?style=flat-square&logo=nginx&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-0B3C68?style=flat-square&logo=github&logoColor=white)

</div>

---

## Planned documentation

This repository may include sanitised material covering:

- Docker service organisation
- Container update procedures
- Backup and recovery checklists
- OpenMediaVault operating notes
- Cloudflare Tunnel principles
- Domain-migration procedures
- Website deployment workflows
- Service troubleshooting records
- Infrastructure audit templates

---

## Repository structure

```text
homelab-documentation/
├── architecture/
├── docker/
├── networking/
├── openmediavault/
├── recovery/
├── security/
└── README.md
