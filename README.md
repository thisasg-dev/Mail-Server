 Mail-Server

A step by step Linux system administration project demonstrating the installation, configuration, and testing of a mail server on CentOS 7. Project Postfix, mailbox acess configuration using Dovecot, DNS settings, CentOS Vault repository configuration, firewall management, SELinux configuration, local email testing & real time mail log monitoring. 

🎯 Project Objectives

-Configure email transfer using Postfix (SMTP).

-Enable mailbox access services using Dovecot.

-Configure and manage Linux mail server services.

-Configure firewall rules for mail-related ports.

-Test local email delivery using Linux terminal commands.

-Monitor mail server activity and troubleshoot errors.

-Understand essential mail server security considerations.

🛠️ Technologies Used

 CentOS 7 - Server operating system

 Postfix - SMTP mail transfer service

 Dovecot - IMAP/POP3 mailbox access services

 firewalld - Firewall configuration

 SELinux - Security policy enforcement

 Linux Terminal - Server administration

 systemctl - Service management

 tail - Real-time log monitoring

 vi - Configuration file editing

 yum - Package management

🏗️ System Architecture

             👤 Mail Client User
                     |
                     | SMTP
                     v
            ✉️ Postfix Mail Server
                     |
                     v
             📂 Mail Storage
                (Maildir)
                     |
                     v
            📬 Dovecot Services
               IMAP / POP3
                     |
                     v
              💻 Mail Client
 This diagram represents the conceptual mail flow and service roles. The project primarily focuses on local-network configuration and testing.
