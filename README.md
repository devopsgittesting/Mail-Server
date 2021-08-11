# Mail-Server
How to send mail alert to master node if memory usages above 10% threshold 
Use Ansible Playbook to execute shell script on client machine to check memory usages
shell script for check memory usages & if memory usages reach threshold send mail alert to master node using local mail system

First install & configure postfix mail server on bother machines
configure DNS for mail server for more info check below link
https://www.golinuxcloud.com/configure-postfix-mail-server-smtp-relay-rhel/

