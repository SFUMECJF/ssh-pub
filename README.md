wget https://raw.githubusercontent.com/SFUMECJF/ssh-pub/main/pub

cat pub >> authorized_keys

rm pub

cat pub >> known_hosts
