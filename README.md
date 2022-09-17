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

If you preffer there are some different options available to install the collection:

install the collection from git repo via https and main branch

```command
ansible-galaxy collection install git+https://github.com/shellclear/ansible_collection_aap.git,main
```

install from a local git repo

```command
git clone https://github.com/shellclear/ansible_collection_aap.git /tmp/ansible_collection_aap
ansible-galaxy collection install git+file:///tmp/ansible_collection_aap
```

License
-------

GNU General Public License v3.0 or later.

See [LICENSE](https://www.gnu.org/licenses/gpl-3.0.txt) to see the full text.