- `sudo apt-add-repository -y ppa:ansible/ansible`
- `sudo apt-get install -y software-properties-common build-essential ansible`
- `ansible-pull -U git@github.com:halfdane/setup_laptop.git -fi localhost, --full --purge playbook.yml -K`

ansible-playbook playbook.yml -K
