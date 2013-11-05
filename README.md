drupalsolrcloud
===============

Reference https://drupal.org/node/2064377 https://drupal.org/node/2107417 we made a workable version of solrcloud with drupal configuration

This project aims at maintain those component required to connect drupal & solrcloud

How to use
===============
For solrcloud, it need to use zookeeper, please upload this config to zookeeper and it will download to all your solrcloud node.

In the example / your solr running folder:
"cloud-scripts/zkcli.sh -cmd upconfig -zkhost <zookeeper_server>:2181 -d <location_to_this_project_conf(solrcloud please use 4.x)> -n <your solr configration naming>"
