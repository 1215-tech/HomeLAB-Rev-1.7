# HomeLAB-Rev-1.7
## Big software QOL overhaul
##### Currently we have problems with running anything other then docker containers due to internal limitations of Unraid. The idea so far is to run Proxmox on bare metal and put Unraid in a VM. The current working map is this:

![map v1](/pics/map_v1.jpg "map v1")

##### We aslo have to update the services we host, add new ones, rework remote access for admins and add DDNS for public services. 

### The list of services so far (this will be running in unraid):
 - ~~Jellyfin~~
 - ~~QBittorrent~~
 - ~~Prowler (for Jellyfin)~~
 - ~~VOIP since discord asks for IDs now~~ (TS)
 - ~~Hommar/Dashdot or both (need to properly set up the thing lol)~~
   - Configure properly
 - ~~Some kind of remote access~~ (Tailscale for now, Netbird in testing)
 - ~~UptimeKuma~~
 - ~~Navidrome and everything to do with that~~
 - Look into spotify API n8n -> spotify integration
 - IQAS website
 - 11Customs website (if we figure out how to selfhost payments)
 - Internal knowlege base
 - Discord music bot (need to make that from scratch since muse is fucking ass)
 - Telegram bot for convinience
 - Some kind of backup solution (need storage for that, and that come only after the rev2.o of homelab prob)
 - Various game servers
 - DDNS for public facing services (Grey IP address, shelved for now)
 - Bitwarden
 - Security stuff (figure this out)
 - Gitlab remote runner
 - ~~n8n automatisation layer~~
   - Configure properly
 ### The list of stuff running directly in ProxMox:
 - Propper VMs for stuff
 - Propper LLM for internal use (prob need a gpu for that)
 - Unraid
