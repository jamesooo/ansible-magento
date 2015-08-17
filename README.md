# ansible-magento
## requirements:
-vagrant<br>
-ansible
## instructions: 
clone this repo<br>
vagrant up<br>
navigate to magento.dev in your browser.
### MySQL
database: magento<br>
username: magento<br>
password: password123<br>

this was based off the work by [jruels](https://github.com/jruels/AnsiblePlaybooks/tree/master/ansible-magento-lemp) with a few changes to steamline the process of getting up and running<br>
windows support through [geerlingguy](https://github.com/geerlingguy/JJG-Ansible-Windows)

## todo
add in memcached support<br>
use percona sql instead of mysql<br>
create tags for production vs devel servers<br>
