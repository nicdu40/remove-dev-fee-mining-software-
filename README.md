# no-dev-fee-2022 for linux

runs on the same machine with the mining software or on a linux router very easely without external configuration.

Usage:sudo ./dev_fee_free "pool_server" "YOUR ADRESS"

compatible with eth, etc , ...

 
Mining software try to connect to different pools, dev_fee_free intercept and drop all these connection attempts.
 
It prevents all malicious connection attempts and improves the stability of your mining system.
 
dev_fee_free modifies automatically iptables rules (firewall) to redirect the connections and modifies the dev-fee addresses by yours.

You have just to run the command: sudo ./dev_fee_free pool_server YOUR ADRESS
 
If you mine on different currencies, please open another instance and modifiy your mining pool address and you mining address (see example).
 
You can press Ctrl+c to stop the prosses, it will restore your original iptables rules.
  
You cann add '.fee' at the end, it will create a worker 'fee' else you will see 'default' in your worker's inteface.
 
Examples:
 
For ETC on ethermine:
sudo ./dev_fee_free eu1-etc.ethermine.org 0x23e2694B7f5a1398d3572722EEEEeCE4D8C142Ca.fee
 
For ETH on ethermine:
sudo ./dev_fee_free eu1.ethermine.org 0x57a0a4777cb478d02c436a9de86150fc6ad3ea7a.fee
 
For ETC on 2miners:
sudo ./dev_fee_free etc.2miners.com 0x23e2694B7f5a1398d3572722EEEEeCE4D8C142Ca.fee
 
For ETH on 2miners:
sudo ./dev_fee_free eth.2miners.com 0x57a0a4777cb478d02c436a9de86150fc6ad3ea7a.fee
 
autorised pool server address:

asia2.ethermine.org
asia1.ethermine.org 
eu1.ethermine.org 
us1.ethermine.org 
us2.ethermine.org 
 
asia1-etc.ethermine.org
eu1-etc.ethermine.org
us1-etc.ethermine.org
 
eth.2miners.com
us-eth.2miners.com
asia-eth.2miners.com
 
etc.2miners.com
us-etc.2miners.com
asia-etc.2miners.com

![term](https://user-images.githubusercontent.com/45800260/161018610-a734306e-f2fe-4e41-9bf0-6b18ffb7258f.png)



