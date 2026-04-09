# Ticket 001: Wi-Fi Connectivity Failure

## Summary
User unable to connect to corporate Wi-Fi network.

## Symptoms
- SSID visible but cannot authenticate  
- Intermittent connectivity  

## Investigation
- Verified wireless adapter settings  
- Checked saved credentials  
- Confirmed access point operational  
- Conducted `ipconfig /release` and `ipconfig /renew`  

## Root Cause
Incorrect saved network credentials  

## Resolution
- Removed saved network profile  
- Re-entered correct credentials  
- Confirmed stable connection  

## Outcome
User regained full Wi-Fi connectivity. Documented ticket resolution for knowledge base.
