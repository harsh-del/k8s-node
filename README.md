Worker
=========

This role is going to help you in creating your instance as a **Kubernetes Worker Node**

Requirements
------------

You have to upload your **ssh_private_key_file** in files folder of the role in place of **K8sKy.pem**.

Dependencies
------------

You can use **K8s-master** role for Configuration of instance as a **Master Node** of **Kubernetes**.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
I am showing an example of Setup Playbook for an **AWS Instance** whose tag is `Name=node`.

    - hosts: tag_Name_node
      roles:
         - K8s_slave


Author Information
------------------

**Harsh Goenka**
[Contact Me](harshgoe19055@gmail.com)
