FROM registry.redhat.io/ansible-automation-platform-24/ee-minimal-rhel8:latest
RUN ansible-galaxy collection install amazon.aws  && ansible-galaxy collection install google.cloud && pip3 install "openstacksdk>=1.0.0" && ansible-galaxy collection install openstack.cloud && ansible-galaxy collection install community.general
