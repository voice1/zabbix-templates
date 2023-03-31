# Switchvox PBX Monitoring

Enables SNMP monitoring of your Digium/Sangoma Switchvox PBX.


## Linked Templates
- This requires the use of `Linux SNMP` template to get additional monitoring points.
- Digium Telephony Cards: This provides SNMP stats for Digium add on Telephony Cards


## External Scripts
None

## Macros
{$CURRENT_VERSION}       Update to current build number. _[manual update]_. Used to trigger notification of updates on monitored PBX installs.
{$DISK_CRITICAL}                Percentage to trigger Ciritical Disk Usage (75%)
{$DISK_WARNING}               Percentage to trigger warning (50%)
{$MIN_VOIP_PROVIDERS}. It is recommended to have at least 2 SIP trunks for reliability (defaults 2)
{$REGCODE}                        System registration code.
{$STORAGE_UTIL_CRIT}     
{$STORAGE_UTIL_WARN}



## Monitored Points.
This template proivdes a number of monitored endpoints as provided by  SNMP. 

Controller Status
CPU Load
Current Calls Conference
Current Calls Parked
Current Calls Queued
Current Calls Total	
Days Left Expired
Device 0 Status
Device 1 Status		
Device 2 Status		
Device 3 Status		
Disk Load		
Disk Percent Used
Disk Total		
Disk Used		
Last Update (Memory/Swap)		
Last Update Disk		
Logical Device Status
Max Concurrent Calls		
Max Extensions		
Max Feature Packs		
Memory Total		
Memory Used		
Number of calls agent_login		
Number of calls agent_out		
Number of calls in conference		
Number of calls in state monitoring		
Number of calls in state ringing		
Number of calls in state talking		
Number of calls in state unknown		
Number of Reachable SIP Phones		
Number of SIP Phones		
Number of Sip Phones in Green State		
Number of Sip Phones in Yellow State		
Number of VoIP Providers		
SIP Phone Registration Status		
Software Version
Subscription Expiration Date		
Swap Percentage Used
Swap Total		
Swap Used		
Used Extensions		
Used Feature Packs		
VoIP Providers Ok