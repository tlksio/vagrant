# tlks.io : vagrant

This is an unordered & random future ideas to discuss. Once an idea is
discussed it should be moved as a task/issue to the backlog.

Current ideas:

##### Map guest's /opt/tlks.io folder to the host?

It would be useful to map the VM guest's `/opt/tlks.io` folder to the host server?

All applications source code are deployed to this folder, perhaps it would be useful to develop because you can use IDE's or more advanced editors to edit the source code. 

##### All tlks.io related logs in one single place.

Right now front web application is generating logs, but also supervisor and maybe MongoDB and ElasticSearch does.

A list of logs we currently handle:

* Logs from the different apps.
* Logs from supervisord.
* Logs from the search index.

It would be useful to have a central place to see logs? How you would build this?
