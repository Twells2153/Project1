# Project1
Group work for Computer Systems Security, project 1.

## Introduction

## Network Diagnosis, Task II

### A) NMap commands to scan the computers and the service ports
### B) Discovered IP's and services in Network A and B
#### 1) Run NMap in A.2 on Network A

Scan all computers and services in Network A. Record the identified computers and services.
```
Starting Nmap 7.80 ( https://nmap.org ) at 2020-09-16 15:51 CDT
Nmap scan report for 172.16.0.1
Host is up (0.00073s latency).
Not shown: 999 closed ports
PORT   STATE SERVICE
22/tcp open  ssh

Nmap scan report for 172.16.0.101
Host is up (0.00088s latency).
Not shown: 998 closed ports
PORT   STATE SERVICE
22/tcp open  ssh
80/tcp open  http

Nmap scan report for 172.16.0.102
Host is up (0.00074s latency).
Not shown: 998 closed ports
PORT   STATE SERVICE
22/tcp open  ssh
80/tcp open  http
root@server:/home/user4# nmap 10.0.0.1/24
```

#### 2) Run NMap in A.2 on Network B

Scan all computers and services in Network B. Record the identified computers and services.
```
Starting Nmap 7.80 ( https://nmap.org ) at 2020-09-16 14:57 CDT
Nmap scan report for 10.0.0.1
Host is up (0.0018s latency).
Not shown: 999 closed ports
PORT   STATE SERVICE
22/tcp open  ssh

Nmap scan report for 10.0.0.2
Host is up (0.0023s latency).
Not shown: 977 closed ports
PORT     STATE SERVICE
21/tcp   open  ftp
22/tcp   open  ssh
23/tcp   open  telnet
25/tcp   open  smtp
53/tcp   open  domain
80/tcp   open  http
111/tcp  open  rpcbind
139/tcp  open  netbios-ssn
445/tcp  open  microsoft-ds
512/tcp  open  exec
513/tcp  open  login
514/tcp  open  shell
1099/tcp open  rmiregistry
1524/tcp open  ingreslock
2049/tcp open  nfs
2121/tcp open  ccproxy-ftp
3306/tcp open  mysql
5432/tcp open  postgresql
5900/tcp open  vnc
6000/tcp open  X11
6667/tcp open  irc
8009/tcp open  ajp13
8180/tcp open  unknown

Nmap scan report for 10.0.0.3
Host is up (0.0022s latency).
Not shown: 988 closed ports
PORT      STATE SERVICE
21/tcp    open  ftp
22/tcp    open  ssh
80/tcp    open  ht
```

### C) Wireshark results of checking the web service between B.1 and A.1, and, A.2 and A.1
#### B.1 and A.1
#### A.2 and A.1

### D) Wireshark results of checking the ping between B.1 and A.1, and, A.2 and A.1
#### B.1 and A.1
#### A.2 and A.1

## Impliment Security Policy, Task III
### A) Access Control Matrix
### B) Issues with Policy Compliance 
### C) iptables Rules in R

## Test Implimentation of The Security Policy, Task IV
### A) Show NMap Results of Exposure of Network A
### B) Wireshark results of checking the web service between B.1 and A.1, and, A.2 and A.1
#### B.1 and A.1, stating whether or not web service is allowed between computers.
#### A.2 and A.1, stating whether or not web service is allowed between computers.
### C) Wireshark results of checking the ping between B.1 and A.1, and, A.2 and A.1
#### B.1 and A.1, stating whether or not ping is allowed between computers.
#### A.2 and A.1, stating whether or not ping is allowed between computers.

## Closing
### A) Show iptables rules to enforce the security policy in A.1
### B) Show iptables rules to enforce the security policy in A.2
### C) Discussion of how the security policy could ensure non-Disclosuer
