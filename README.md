# Sysadmin Bootcamp
Lab personal para preparación de entrevista Linux Sysadmin.

## Topología del lab (LAN 192.168.0.0/24)
| VM | OS | Rol | IP | MAC |
|----|----|----|----|----|
| srv-debian-01 | Debian 12 | Ansible controller | 192.168.0.100 | 00:15:5d:00:49:05 |
| srv-rocky-01 | Rocky 9 | FreeIPA + iSCSI target | 192.168.0.51 | 00:15:5d:00:00:51 |
| cli-debian-01 | Debian 12 + XFCE | Cliente + escritorios + iPXE | 192.168.0.52 | 00:15:5d:00:00:52 |
| nas-truenas | TrueNAS Scale (opcional) | NAS + iSCSI target | 192.168.0.53 | 00:15:5d:00:00:53 |

## Hipervisor
Hyper-V en Windows (DESKTOP-TET7ULM)
Switch virtual externo: LabNet (Realtek Gaming 2.5GbE)

## Usuario
german (sudo sin password en cada VM del lab)
