# A Quagga-Based RPKI-Enabled Router

## Configure

Installing and running should be as easy as:

1. Install VirtualBox
2. Install Vagrant
3. cd quagga-rpki-router
4. run "vagrant up"

## Run the router

1. Connect with "vagrant ssh" to the recently-created box
2. Start bgpd with
```
	bgpd -d &
```
3. Check it's working correctly
```
	show rpki prefix-table
	show rpki cache-connection
```

## Author and Contact Information