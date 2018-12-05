- `sudo apt-add-repository -y ppa:ansible/ansible`
- `sudo apt-get install -y software-properties-common build-essential ansible`
- `ansible-pull -U git@github.com:halfdane/setup.git -fi localhost, --full --purge playbook.yml`

ansible-playbook playbook.yml --ask-become-pass
