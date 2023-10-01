substitutions:

###### CHANGE ME START ######

  name: "muse-luxe" 
  wifi_ssid: !secret wifi_ssid
  wifi_password: !secret wifi_password

##### CHANGE ME END #####

##### DO NOT CHANGE ANYTHING! #####

packages:
  ##### download esphome code from Github
  remote_package:
    url: https://github.com/semakka1975/muse-luxe
    ref: main
    files: [raspi-a-muse-luxe.yaml]
    refresh: 300s

##### DO NOT CHANGE ANYTHING! #####
