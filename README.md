wget https://raw.githubusercontent.com/SFUMECJF/ssh-pub/main/pub

cat pub >> authorized_keys

cat pub >> known_hosts

rm pub
