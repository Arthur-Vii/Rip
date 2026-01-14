# Rip
router 1
Router> enable
Router# configure terminal
Router(config)# router rip
Router(config-router)# version 1
Router(config-router)# network 192.168.1.0 
Router(config-router)# network 192.168.2.0 
Router(config-router)# exit

router 2
Router> enable
Router# configure terminal
Router(config)# router rip
Router(config-router)# version 1
Router(config-router)# network 192.168.10.0 
Router(config-router)# network 192.168.20.0 
Router(config-router)# exit
