# raspi-cluster-k3s

## sette opp Raspberry pi'ene
### Hardware
* 4 raspberry pi 3 b+ eller nyere
* 4 ports usb strømtilførsel
* 4 micro-usb ledninger (strøm til rbpi'ene)
* 4 micro-SD 
* 5 ethernet kabler(4 til raspb pi'ene og 1 til switch til routeren din)
* kabinetter som kan stabler for raspb pi'ene

### Software
#### Raspbian OS
1. last ned image av ønsket os
2. skriv os til sd-kortet
3. gå inn i booth og opprett en til som heter ssh
4. opprett fil for enable wifi
5. sett opp ssh-key

#### pytohn og pip
#### Installere Ansible og sette opp raspberry pi
1. pip install ansible
2. last ned filene fra repoet: https://github.com/tomvingaas/raspi-cluster-k3s
3. lag en inventory fil og legg inn ip'ene til raspberry pi'ene
4. kjør. ansibel playbook'en