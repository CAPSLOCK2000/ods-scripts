ods-scripts
===========

Scripts to assist OpenDNSSEC

 * ods-dsseen               Check the availability of a new DS/DNSKEY in the parent DNS.
 * ods-keycheck             Overview of keys that should be published to the parent.
 * ods-deadkeys             Overview of keys that are published in DNS but are not/no longer in use.
 * receive-dnskeys          Accept DNSKEYS from OpenDNSSEC and forward them to an appropriate script
 * ods-uploadkeys           Upload DNSKEYS to a registrar using their API.
 * ods-agenda               Overview of current and upcomming events for OpenDNSSEC.
 * ods-eta <zone>           Overview of the keys of a zone and when the next event is to be expected.
 * ods-ha                   Copy the entire state of a running OpenDNSSEC-server to another server.
 * ods-write-trust-anchor   Export a DNSKEY in a format that Unbound can use for a trust anchor.
