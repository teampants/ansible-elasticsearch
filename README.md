[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Build Status](https://travis-ci.org/teampants/ansible-elasticsearch.svg?branch=develop)](https://travis-ci.org/teampants/ansible-elasticsearch)
# ansible-elasticsearch
Installs elasticsearch 2.0

## Example Playbook

    - hosts: logging
      roles:
        - role: teampants.elasticsearch
          elasticsearch_version: 2.4.0
