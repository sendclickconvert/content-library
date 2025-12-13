---
title: "WiFi Connected But No Internet? 9 Fixes That Actually Work"
category: Laptop Guides
keywords: laptop, screen, dark spots, fix
published: 2025-12-13
---

# WiFi Connected But No Internet? 9 Fixes That Actually Work

# WiFi Connected But No Internet? 9 Fixes That Actually Work (2024)

Your device shows full WiFi bars. The connection looks perfect. But when you try to open a webpage or use an app—nothing. This is one of the most frustrating tech problems because everything appears to be working, yet you have no internet access.

This issue affects Windows laptops, Macs, iPhones, Android phones, and tablets equally. The good news is that it's almost always fixable without calling tech support.

This guide covers every proven solution, starting with the quickest fixes and moving to more advanced troubleshooting.

**Need immediate help?** **[Talk to a Live Tech Expert](https://bit.ly/ask-a-tech)** who can walk you through the fix.

*This article is part of our complete [WiFi Troubleshooting Guide](/guides/how-to-fix-problems-with-wifi-connection) covering every WiFi issue.*

## Why This Happens

When your device connects to WiFi but can't reach the internet, the problem is usually one of these:

- **Router connected to WiFi but not internet** - Your router talks to your device fine, but it can't reach your ISP
- **DNS issues** - Your device can't translate website names into addresses
- **IP address conflict** - Two devices trying to use the same address
- **ISP outage** - The problem is on your provider's end

Let's fix it.

## Fix 1: Restart Your Router (The Right Way)

This fixes the problem about 50% of the time. But you need to do it correctly:

1. Unplug your router from power completely
2. If you have a separate modem, unplug that too
3. Wait 30 full seconds (this is important)
4. Plug the modem back in first, wait 2 minutes
5. Plug the router back in, wait 2 minutes
6. Try connecting again

The wait time matters because the router needs to fully discharge and clear its memory.

## Fix 2: Check If It's Your ISP

Before troubleshooting your equipment, verify your internet service is actually working:

1. Look at your router/modem lights. The "Internet" or "WAN" light should be solid green. If it's red or off, the problem is likely your ISP
2. Connect a device directly to your modem with an ethernet cable. If that doesn't work, call your ISP
3. Use your phone's cellular data to visit [downdetector.com](https://downdetector.com) and search for your ISP

If your ISP is down, no amount of troubleshooting will help—you'll need to wait for them to fix it.

## Fix 3: Forget and Reconnect to WiFi

Corrupted network profiles cause this problem frequently. Forgetting the network and reconnecting fresh often fixes it.

**Windows:**
1. Click the WiFi icon in taskbar
2. Right-click your network → Forget
3. Click the network again and enter your password

**Mac:**
1. System Preferences → Network → WiFi → Advanced
2. Select your network, click minus (-) to remove
3. Reconnect with your password

**iPhone/iPad:**
1. Settings → WiFi → tap (i) next to network
2. Tap "Forget This Network"
3. Reconnect with password

**Android:**
1. Settings → WiFi → long-press network
2. Tap "Forget network"
3. Reconnect with password

## Fix 4: Flush Your DNS Cache

DNS translates website names (like google.com) into IP addresses. A corrupted DNS cache prevents this translation, causing "connected but no internet."

**Windows:**
1. Open Command Prompt as Administrator
2. Type these commands, pressing Enter after each:
   - `ipconfig /flushdns`
   - `ipconfig /release`
   - `ipconfig /renew`
3. Try browsing again

**Mac:**
1. Open Terminal
2. Type: `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`
3. Enter your password when prompted

## Fix 5: Change Your DNS Server

Your ISP's DNS servers can be slow or unreliable. Switching to Google or Cloudflare DNS often fixes connection issues and speeds up browsing.

**Windows:**
1. Control Panel → Network and Internet → Network and Sharing Center
2. Click your WiFi connection name
3. Click Properties → Internet Protocol Version 4 (TCP/IPv4) → Properties
4. Select "Use the following DNS server addresses"
5. Enter:
   - Primary: 8.8.8.8 (Google) or 1.1.1.1 (Cloudflare)
   - Secondary: 8.8.4.4 (Google) or 1.0.0.1 (Cloudflare)
6. Click OK

**Mac:**
1. System Preferences → Network → WiFi → Advanced → DNS
2. Click + and add 8.8.8.8 and 8.8.4.4
3. Click OK → Apply

## Fix 6: Reset TCP/IP Stack (Windows)

This resets your computer's core networking components:

1. Open Command Prompt as Administrator
2. Type these commands, pressing Enter after each:
   - `netsh winsock reset`
   - `netsh int ip reset`
3. Restart your computer
4. Reconnect to WiFi

## Fix 7: Disable VPN and Proxy

VPNs and proxies can interfere with your connection. Temporarily disable them:

**Windows:**
1. Settings → Network & Internet → VPN → disconnect any active VPN
2. Settings → Network & Internet → Proxy → turn off "Use a proxy server"

**Mac:**
1. System Preferences → Network → select your VPN → disconnect
2. System Preferences → Network → WiFi → Advanced → Proxies → uncheck all

## Fix 8: Update Network Drivers (Windows)

Outdated or corrupted network drivers cause connection issues:

1. Press Windows + X → Device Manager
2. Expand "Network adapters"
3. Right-click your wireless adapter → Update driver
4. Select "Search automatically for drivers"
5. Restart your computer if updates are found

If no updates are found, try uninstalling the driver (right-click → Uninstall device), then restart. Windows will reinstall it automatically.

## Fix 9: Reset Network Settings

As a last resort, reset all network settings to factory defaults:

**Windows:**
1. Settings → Network & Internet → Status
2. Scroll down → Network reset
3. Click "Reset now"
4. Your PC will restart

**Mac:**
1. System Preferences → Network
2. Select WiFi → click minus (-) to remove
3. Click plus (+) to add WiFi back
4. Click Apply

**iPhone:**
1. Settings → General → Transfer or Reset iPhone
2. Reset → Reset Network Settings

**Android:**
1. Settings → System → Reset options
2. Reset WiFi, mobile & Bluetooth

## Still Not Working?

If none of these fixes work:

1. **Try a different device** - If other devices connect fine, the problem is device-specific
2. **Contact your ISP** - They can run diagnostics on your line
3. **Consider router issues** - Old routers (5+ years) often need replacing

**[Get Live Expert Help Now](https://bit.ly/ask-a-tech)** - Our tech specialists can diagnose your specific issue in real-time.

## Recommended Products

If your router is outdated, these upgrades can solve persistent connection issues:

- [WiFi 6 Routers](https://www.amazon.com/s?k=wifi+6+router&tag=petart01-20) - Latest technology for better reliability
- [Mesh WiFi Systems](https://www.amazon.com/s?k=mesh+wifi+system&tag=petart01-20) - Eliminate dead zones throughout your home
- [Network Diagnostic Tools](https://www.amazon.com/s?k=network+cable+tester&tag=petart01-20) - Test your connections

**Pro Tip:** Use [ShopBack](https://www.shopback.com) to earn cashback on your Amazon purchases!

## Related WiFi Issues

- [WiFi Keeps Disconnecting](/guides/wifi-keeps-disconnecting) - Constant drops
- [WiFi Not Showing Up](/guides/wifi-not-showing-up-on-laptop) - Network invisible
- [Complete WiFi Fix Guide](/guides/how-to-fix-problems-with-wifi-connection) - Every solution

---

**Still stuck?** **[Talk to a Live Tech Expert](https://bit.ly/ask-a-tech)** who can solve even the trickiest connection problems.

---

**Categories:** Laptop Guides  
**Keywords:** laptop, screen, dark spots, fix

*Published on MrGrid.io - Your authoritative source for technical error codes and solutions.*
