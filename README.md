# Liste des ips à blacklister sur vos serveurs

Sur la base d'attaques, une liste noire est générée. Cette liste est mise à jour chaque jour avec les attaques de la journée. 
Un script pour bloquer les ips (via iptables et nftables) est généré (aussi mis à jour chaque jour) afin de vous permettre de bloquer rapidement ces ips sur vos serveurs. 
On générera aussi un script Ansible afin de déployer plus efficacement cette liste noire.
