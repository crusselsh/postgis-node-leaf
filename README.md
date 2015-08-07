## Postgis <-> node.js <-> Leaflet
simple node.js implementation to connect to postgresql db. Follows examples from
- github.com/ryanj/restify-postGIS.git,
- https://blog.openshift.com/instant-mapping-applications-with-postgis-and-nodejs/
- among others to be added

### current version
Loads all tables that are registered in the geometry_columns view

### To do
- update original ryanj/restify-postGIS.git/bin/db.js functions
- write data from client instance
- add socket.io to share a) connected user locations and/or b) active data loaded (eg for collaborative pg saved spatial data editing)
