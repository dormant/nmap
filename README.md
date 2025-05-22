# nmap

## ~/src/nmap

## nmap_chron.sh

* Script for running nmap on the MVO network.
* Creates web page accessible in notWebobs: http://webobs.mvo.ms:8080/mvofls2/monitoring_data/status/nmap/nmap.html
* Runs once a day as a cronjob on *opsproc3*.
```
# nmap scan of 172.17.102 network
0 8 * * * /home/seisan/src/nmap/nmap_cron.sh 2>&1
```
## Author

Roderick Stewart, Dormant Services Ltd

rod@dormant.org

https://services.dormant.org/

## Version History

* 1.0-dev
    * Working version

## License

This project is the property of Montserrat Volcano Observatory.
