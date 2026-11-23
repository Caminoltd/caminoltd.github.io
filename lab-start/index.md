---
layout: checklist
title: Lab preparation with Lab Start
heading: Lab preparation checklist
intro: Work through these steps before the first lab. Everything is done from A-GUI with Camino Lab Start. Tick each step as you go. Your ticks are saved on this device.
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
  - title: Log in to **A-GUI**
    detail: A-GUI is the Windows VM you work from in every lab. Its username and password are shown under it in the **Resources** tab.
  - title: Open **PowerShell** on A-GUI
    detail: Click **Start**, type `PowerShell` and press **Enter**. A normal window is fine; it does not need to be run as administrator.
  - title: Start **Lab Start** with this command
    detail: |
      ```
      irm caminoltd.github.io/start.txt | iex
      ```
      Copy the command on your own computer, then in the lab window use Skillable's **Type Clipboard Text** to type it into PowerShell, and press **Enter**. You can also type it by hand.

      Lab Start opens in its own window and puts a **Lab Start** shortcut on the desktop, so you can open it again at any time.
  - title: Choose **your course** at the top right of Lab Start
    detail: Lab Start then shows the logins, documents and notes for your course.
  - title: Set your **keyboard and time zone** in tab 1, **Localise**
    detail: |
      Choose your country and keyboard, then click **Apply**. Lab Start sets every lab VM, Windows and Gaia, from A-GUI.

      Nothing restarts. Wait until the Localise tab says **Done** (usually a few minutes).
  - title: Note the **logins and IP addresses** in tab 3
    detail: Double-click any value to copy it. They are also on the 3rd page of every lab in your lab guide.
  - title: Read the **lab notes** in tab 5
    detail: Corrections and tips, including lab steps to skip (for example the Hyper-V Manager steps).
  - title: Start **Lab 1A**
---

## Reference

**Course resources and lab topologies:** [all courses](../)

- [Lab navigation tips (PDF)](../common/navigation.pdf)
- The earlier method, using `changes.cmd` on RDP-HOST: [previous lab preparation checklist](../lab-preparation/)
