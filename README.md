## Scrapyd on Raspberry Pi via Resin-io and Docker

This project is a simple [Scrapyd][https://scrapyd.readthedocs.io/en/stable/] instance running on a Raspberry Pi using [Resin.io][resin-link].

This project runs `` on port `:80` of your resin.io device.

To get this project up and running, you will need to signup for a resin.io account 


```
$ git clone git@github.com:townie/scrapyd-pi.git
```
Then add your resin.io application's remote:
```
$ git remote add resin <<<>>>>
```
and push the code to the newly added remote:
```
$ git push resin master
```


Enable PUBLIC IP


## TODO 
Deploy verification and such

## Update XXXXXX to correct public IP

```
[deploy:resin]
url = https://XXXXXX.resindevice.io/
project = projectX
```