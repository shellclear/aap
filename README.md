Ansible Collection -shellclear.ansible_collection_aap
=====================================================

This ansible collection allow automate tasks related with Ansible Automation Platform.

Installing the collection
-------------------------

Create a requirements.yml file.

```yaml
collections:
  - name: https://github.com/shellclear/ansible_collection_aap.git
    version: main
    type: git 
```

Install the collection with ansible galaxy cli.

```console
ansible-galaxy collection install -r requirements.yml
```

If you preffer also is available another option to install from git

```command
ansible-galaxy collection install git+https://github.com/shellclear/ansible_collection_aap.git,main
```

License
-------

GNU General Public License v3.0 or later.

See [LICENSE](https://www.gnu.org/licenses/gpl-3.0.txt) to see the full text.