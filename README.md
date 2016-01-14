# MyTunein.bundle
Allows to listen tunein stations for a specific user

# Information for developer
* Requesting for a json with all station for a user: `curl 'http://tunein.com/profile/follows/?identifier=u159012873/follows/stations&type=&offset=20' -H 'x-requested-with: XMLHttpRequest'`
* [Setting header to HTTP Request](http://thingsinjars.com/post/297/writing-a-plex-plugin-part-i/)
* [Persisting channel information](http://forums.plex.tv/discussion/88179/storing-user-data-in-dict)

curl 'http://tunein.com/userprofile/contents/?username=adamchuk2168' -H 'x-requested-with: XMLHttpRequest'

curl 'http://tunein.com/profile/follows/?identifier=u159012873/follows/stations&type=&offset=40' -H 'x-requested-with: XMLHttpRequest'

http://tunein.com/user/adamchuk2168/
