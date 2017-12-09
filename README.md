[![Build Status](https://travis-ci.org/bendews/ansible-container-flask-demo.svg?branch=master)](https://travis-ci.org/bendews/ansible-container-flask-demo)

# Ansible Container - Flask Demo
Demo for creating a 3-Tier multi-container Flask app using Ansible Container.
See the accompanying blog post at [bendews.com](https://bendews.com/posts/hello-world-with-ansible-container/).

## Requirements

- [Ansible Container](http://docs.ansible.com/ansible-container/installation.html)
- docker

## Build & Run

Use Ansible Galaxy to download the project, then build and run:
```bash
ansible-container init bendews.container-flask-demo
ansible-container build
ansible-container run
```

# License

MIT

# Author Information

Created in 2017 by [Ben Dews](bendews.com)
