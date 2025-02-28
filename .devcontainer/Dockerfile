FROM dp.apps.rancher.io/containers/openjdk:21.0.6-build7-dev 
# Needs authentication - see https://apps.rancher.io/settings/access-tokens

RUN zypper --non-interactive install -y git openssh make awk nodejs-default npm-default
RUN useradd -ms /bin/bash vscode 
USER vscode 
ENV HOME /home/vscode

EXPOSE 3000