---
marp: true
theme: gaia
_class: lead
paginate: false
color: #f5f7fa
style: |
    /* Dutch flag palette: red #AE1C28, white #FFFFFF, blue #21468B */
    section {
        background: linear-gradient(135deg, #21468B 0%, #16305f 55%, #0d1b33 100%) !important;
        color: #f5f7fa;
    }
    section.lead {
        background:
            linear-gradient(180deg, #AE1C28 0%, #AE1C28 6%, #ffffff 6%, #ffffff 9%, rgba(255, 255, 255, 0) 9%),
            linear-gradient(0deg, #AE1C28 0%, #AE1C28 6%, #ffffff 6%, #ffffff 9%, rgba(255, 255, 255, 0) 9%),
            linear-gradient(135deg, #21468B 0%, #16305f 55%, #0d1b33 100%) !important;
    }
    section.lead h1,
    section.lead h2 {
        color: #ffffff;
        text-shadow: 0 2px 10px rgba(13, 27, 51, 0.75);
    }
    section.lead h2 {
        border-bottom: none;
    }
    h1, h2 {
        color: #ffffff;
    }
    h1 {
        text-shadow: 0 2px 12px rgba(174, 28, 40, 0.45);
    }
    h2 {
        border-bottom: 4px solid #AE1C28;
        padding-bottom: 0.15em;
    }
    h3 {
        color: #ffffff;
    }
    strong {
        color: #ff8a94;
    }
    a {
        color: #ffffff;
        text-decoration-color: #AE1C28;
    }
    section::after {
        color: #ffffff;
    }
    table {
        font-size: 0.85em;
    }
    th {
        background: rgba(255, 255, 255, 0.14) !important;
        color: #ffffff !important;
        border-bottom: 3px solid #AE1C28 !important;
        font-weight: 600;
    }
    td {
        background: rgba(255, 255, 255, 0.08);
    }
    .container {
        display: flex;
        gap: 1em;
    }
    .col {
        flex: 1;
        padding: 0.1em;
    }
    .col-35 {
        flex: 0 0 35%;
    }
    .bottom-right {
        position: absolute;
        bottom: 80px;
        right: 80px;
    }
    .logo-position {
        position: absolute;
        top: 63px;
        right: 73px;
        width: fit-content;
    }
    .logo-card {
        background: #ffffff;
        border-radius: 20px;
        padding: 18px;
        box-shadow: 0 6px 18px rgba(13, 27, 51, 0.35);
        font-size: 0;
        overflow: hidden;
    }
    .logo-card img {
        display: block;
        margin: 0;
        border-radius: 4px;
    }
    blockquote::before,
    blockquote::after {
        content: '';
    }
    blockquote {
        font-style: italic;
        border-left: 6px solid #AE1C28;
        color: #ffffff;
    }
    .main-name {
        position: absolute;
        bottom: 16px;
        right: 100px;
        font-size: 0.9em;
        color: #ffffff;
    }
    .pill {
        display: inline-block;
        background: #AE1C28;
        color: #ffffff;
        border-radius: 20px;
        padding: 0.15em 0.7em;
        font-size: 0.7em;
        font-weight: 600;
        text-transform: uppercase;
        letter-spacing: 0.5px;
    }
    /* Closing slide: photo background + readable overlay */
    section.closing {
        background-image: linear-gradient(90deg, rgba(13, 27, 51, 0.78) 0%, rgba(13, 27, 51, 0.55) 35%, rgba(13, 27, 51, 0.35) 100%), url('template/nam_background.png') !important;
        background-size: cover, contain !important;
        background-position: center !important;
        background-repeat: no-repeat !important;
        color: #ffffff;
    }
    section.closing h2 {
        border-bottom: 4px solid #AE1C28;
    }
    section.closing h3 a,
    section.closing a {
        color: #ffffff;
    }
    section.closing strong {
        color: #ffffff;
    }
    .qr-box {
        position: absolute;
        bottom: 70px;
        right: 70px;
        background: #ffffff;
        padding: 12px;
        border-radius: 12px;
        border: 4px solid #AE1C28;
        font-size: 0;
        line-height: 0;
    }
    .qr-box img {
        display: block;
        margin: 0;
    }
    .center-stage {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 80%;
        text-align: center;
    }
---

# NLNAM

## A Home for Network Automation
## in the Netherlands

![height:170px](template/nlnam_logo_transparent.png)

<!--
* Thank you for the time and opportunity to present
* Proud, Stoked, Excited
* Start - Dan Peachey and I, AC3, 2025
* Launched 2026
* Now a real community
-->

---
<div class="logo-position">
<div class="logo-card">

![w:240px](template/Dream.jpg)

</div>
</div>

## Bart Dorlandt

- Freelance Network Automation Solution Architect
- Lives by: __*There must be a better way*__
- Co-organizer of PyUtrecht
- Advisory board member of Network Automation Forum (NAF)

- https://dreamnetworking.nl/
- https://linkedin.com/in/bartdorlandt/

<!--
- Coming from networking
- Spend the last 10 years in network automation
-->

---

## So what is NLNAM?

> The **N**ether**L**ands **N**etwork **A**utomation **M**eetup

- A **volunteer-run community** — free to attend
- For **network|automation engineers, DevOps & developers**
- Regular meetups across the Netherlands: **talks + networking**

*A home for everyone automating (a network).*

<!--
For some:
- Be away from the kids just a bit longer
- No pressure of work, but you still love the tech
- To each there own, but we all share the same passion
- Free food

Goals:
- Knowledge sharing         - Networking
- Food, duh, food!!!        - Having a great time
-->

---

## Past & future meetups

| #   |      Date | Host              | Where           |
| --- | --------: | ----------------- | --------------- |
| 1   |     5 Feb | Adyen + Netpicker | Amsterdam       |
| 2   |    13 May | APNT              | Alphen a/d Rijn |
| 3   | **9 Sep** | **One Zero IT**   | **Utrecht**     |
| 4   |    26 Nov | Schuberg Philis   | Schiphol-Rijk   |
| 5   |   Feb '27 | Huawei            | Rijswijk        |

<!--
Website has previous meetups and presentations
-->

---

## Topics for the September event

- Zero Trust Automation: From Complexity to Control
- Network Automation Framework overview
- Using JSON schema to describe your data model and perform validation
- Manage a pan-european network with WFO and Ansible

<!--
- Infrastructure as Code        - Source of Truth
- Configuration Management      - (Network) Programming

- Monitoring & Observability    - Cloud Networking
- Validation & Testing          - Workflow Automation

Occasionally, AI
-->

---
<!-- _class: closing -->
<div class="center-stage">

*Automating the future of (Dutch) Networking*

https://net-auto.nl/
</div>
<div class="qr-box">

![w:200px](template/qr_netauto.png)

</div>

<!--
Awesome to have this NA community in the Netherlands.
So excited!
We are always looking for great topics and speakers.

Hope to see you at the next event!

Thank you & enjoy your food.
- Because it is always the food that brings us together, right?
-->
