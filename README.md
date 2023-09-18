# Installing Ansible
-------------------------------
Ubuntu yapıları burada bir PPA'da mevcuttur. PPA'yı makinenizde yapılandırmak ve Ansible'ı kurmak için şu komutları çalıştırın:

    sudo apt update

    sudo apt install software-properties-common

    sudo add-apt-repository --yes --update ppa:ansible/ansible

    sudo apt install ansible

Ansible'ı RHEL, CentOS veya Fedora'ya Kurma
Fedora'da:

    sudo dnf install ansible

RHEL'de:

    sudo yum install ansible

CentOS'ta:
    
    sudo yum install epel-release
    
    sudo yum install ansible
  
RHEL 8 için Ansible Engine deposunu etkinleştirmek için aşağıdaki komutu çalıştırın:
    
    sudo subscription-manager repos --enable ansible-2.9-for-rhel-8-x86_64-rpms

RHEL 7 için Ansible Engine deposunu etkinleştirmek için aşağıdaki komutu çalıştırın:
    
    sudo subscription-manager repos --enable rhel-7-server-ansible-2.9-rpms

https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html

# For Infrastructure Model:
Infrastructure.pdf
