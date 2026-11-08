---
layout: checklist
title: Lab preparation
heading: Lab preparation checklist
intro: Work through these steps before the first lab. Tick each one as you go. Your ticks are saved on this device.
steps:
  - title: Register with Skillable using your **Training Key**
    detail: Your Training Key is in your joining email.
    links:
      - label: Skillable registration
        url: https://arrowecs-com.learnondemand.net
  - title: Write down your Skillable **username and password**
    detail: You will need them during the course and for the 180 days of lab access afterwards.
  - title: Launch the lab
    links:
      - label: Open Skillable
        url: https://arrowecs-com.learnondemand.net
  - title: Go to the **RDP-HOST** virtual machine
    detail: In the **Resources** tab, scroll to the bottom of the VM list and click **RDP-HOST**. Its username and password are shown underneath.
    images:
      - src: /common/img/0-rdp-host.png
        caption: "Resources tab – RDP-HOST is the last VM in the list"
  - title: On RDP-HOST, open File Explorer and run `C:\scripts\changes`
    detail: There are several files called **changes**. Run the one whose Type is **Windows Command Script**.
    images:
      - src: /common/img/1-file-explorer.png
        caption: "C:\\scripts – run the changes file of type Windows Command Script"
  - title: Make your choice in each of the **4 windows**, clicking **OK** after each
    detail: |
      1. Keyboard layout for the Windows VMs
      2. Timezone for the Windows VMs
      3. Region for the Gaia VMs
      4. Zone (city) for the Gaia VMs
    images:
      - src: /common/img/2-keyboard.png
        caption: "Window 1: keyboard layout (Windows VMs)"
      - src: /common/img/3-windows-timezone.png
        caption: "Window 2: timezone (Windows VMs)"
      - src: /common/img/4-gaia-region.png
        caption: "Window 3: region (Gaia VMs)"
      - src: /common/img/5-gaia-zone.png
        caption: "Window 4: zone (Gaia VMs)"
    links:
      - label: Step-by-step guide (PDF)
        url: /common/changes.pdf
  - title: Wait for all VMs to reboot
    detail: This takes 3 to 5 minutes.
  - title: Start **Lab 1A**
---

## Reference

**Course resources and lab topologies:** [all courses](../)


- [Lab navigation tips (PDF)](../common/navigation.pdf)
- [Lab keyboard and timezone guide (PDF)](../common/changes.pdf)
- [Keyboard and timezone change, full guide (PDF)](../common/keyboard-timezone.pdf)
