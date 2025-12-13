---
title: "Laptop Won't Connect to WiFi? 11 Fixes That Work"
category: Laptop Guides
keywords: laptop, screen, dark spots, fix
published: 2025-12-13
---

# Laptop Won't Connect to WiFi? 11 Fixes That Work

# Laptop Won't Connect to WiFi? 11 Fixes That Work (2024)

Your laptop refuses to connect to WiFi, but your phone and other devices work fine. This device-specific connection failure is incredibly common and almost always fixable without professional help.

The problem is usually related to your laptop's network adapter, drivers, or settings—not your router or internet service.

This guide covers every proven fix for laptops that won't connect to WiFi.

**Need immediate help?** **[Talk to a Live Tech Expert](https://bit.ly/ask-a-tech)** for real-time assistance.

*This article is part of our complete [WiFi Troubleshooting Guide](/guides/how-to-fix-problems-with-wifi-connection).*

## Quick Checks First

Before diving into fixes, verify these basics:

- **Is WiFi turned on?** Check for a physical WiFi switch or Fn key combination (like Fn+F2)
- **Is Airplane Mode off?** Check the notification area or Settings
- **Can other devices connect?** If not, the problem is your router, not your laptop
- **Are you in range?** Move closer to the router to test

## Fix 1: Toggle Airplane Mode

The quickest fix—toggle airplane mode to reset your wireless adapter:

1. Click the network icon in the taskbar
2. Click the Airplane Mode tile to turn it ON
3. Wait 10 seconds
4. Click again to turn it OFF
5. Try connecting

## Fix 2: Restart Your Laptop

A restart clears temporary issues with the network adapter:

1. Save your work
2. Click Start → Power → Restart (not Shut down)
3. Try connecting after restart

## Fix 3: Forget and Reconnect to the Network

**Windows 10/11:**
1. Settings → Network & Internet → WiFi
2. Click "Manage known networks"
3. Select your network → Forget
4. Click the WiFi icon and reconnect with your password

**Mac:**
1. System Preferences → Network → WiFi → Advanced
2. Select your network → minus (-) button
3. Click OK → Apply
4. Reconnect with password

## Fix 4: Run Windows Network Troubleshooter

Windows has a built-in diagnostic tool:

1. Right-click the WiFi icon in taskbar
2. Select "Troubleshoot problems"
3. Follow the prompts
4. Apply any fixes it suggests

## Fix 5: Update WiFi Drivers

Outdated or corrupted drivers are the #1 cause of laptop WiFi issues:

1. Press Windows + X → Device Manager
2. Expand "Network adapters"
3. Right-click your wireless adapter (Intel, Realtek, Broadcom, etc.)
4. Select "Update driver" → "Search automatically"
5. Restart your laptop

**If that doesn't work, try reinstalling:**
1. Right-click the adapter → Uninstall device
2. Check "Delete the driver software" if prompted
3. Restart your laptop—Windows will reinstall the driver

## Fix 6: Disable and Re-enable the Network Adapter

1. Press Windows + X → Device Manager
2. Expand "Network adapters"
3. Right-click your wireless adapter → Disable device
4. Wait 30 seconds
5. Right-click again → Enable device
6. Try connecting

## Fix 7: Reset TCP/IP and Winsock

This resets your core network components:

1. Open Command Prompt as Administrator
2. Run these commands (press Enter after each):
   - `netsh winsock reset`
   - `netsh int ip reset`
   - `ipconfig /release`
   - `ipconfig /renew`
   - `ipconfig /flushdns`
3. Restart your laptop

## Fix 8: Check Power Management Settings

Windows may be turning off your WiFi adapter to save power:

1. Device Manager → Network adapters
2. Right-click wireless adapter → Properties
3. Power Management tab
4. Uncheck "Allow the computer to turn off this device to save power"
5. Click OK

## Fix 9: Disable IPv6

Some networks have IPv6 configuration issues:

1. Control Panel → Network and Sharing Center
2. Click your WiFi connection
3. Click Properties
4. Uncheck "Internet Protocol Version 6 (TCP/IPv6)"
5. Click OK and try connecting

## Fix 10: Reset Network Settings Completely

**Windows:**
1. Settings → Network & Internet → Status
2. Scroll down → Network reset
3. Click "Reset now"
4. Your laptop will restart

**Mac:**
1. System Preferences → Network
2. Select WiFi → click minus (-)
3. Click plus (+) → select WiFi → Create
4. Click Apply

## Fix 11: Check for Hardware Issues

If nothing works, your WiFi adapter may have a hardware problem:

1. **Try a USB WiFi adapter** - Plug one in and see if it works
2. **Check Device Manager for errors** - Yellow exclamation marks indicate problems
3. **Test in Safe Mode** - If WiFi works in Safe Mode, it's a software conflict

## Recommended Products

If your built-in WiFi adapter is failing:

- [USB WiFi Adapters](https://www.amazon.com/s?k=usb+wifi+adapter&tag=petart01-20) - Quick replacement solution
- [WiFi 6 USB Adapters](https://www.amazon.com/s?k=wifi+6+usb+adapter&tag=petart01-20) - Faster than most built-in adapters
- [USB-C WiFi Adapters](https://www.amazon.com/s?k=usb+c+wifi+adapter&tag=petart01-20) - For newer laptops

**Pro Tip:** Use [ShopBack](https://www.shopback.com) to earn cashback on Amazon!

## Related WiFi Issues

- [WiFi Not Showing Up on Laptop](/guides/wifi-not-showing-up-on-laptop)
- [WiFi Connected But No Internet](/guides/wifi-connected-but-no-internet)
- [Complete WiFi Fix Guide](/guides/how-to-fix-problems-with-wifi-connection)

---

**Still can't connect?** **[Talk to a Live Tech Expert](https://bit.ly/ask-a-tech)** who can diagnose your specific laptop issue.

---

**Categories:** Laptop Guides  
**Keywords:** laptop, screen, dark spots, fix

*Published on MrGrid.io - Your authoritative source for technical error codes and solutions.*
