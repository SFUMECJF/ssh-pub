wget https://raw.githubusercontent.com/SFUMECJF/ssh-pub/main/pub


cat pub >> known_hosts

cat pub >> authorized_keys

rm pub
