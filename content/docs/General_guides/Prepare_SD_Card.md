---
bookFlatSection: true
weight: 1
title: "Prepare your microSD card"
---

# Prepare your microSD card

## 1. Download the tools.

We are going to use a Open Source tool called **balenaEtcher** for writing Orange Pi OS images to MicroSD card. Download the tool using following link.

[Download balenaEtcher from here.](https://www.balena.io/etcher/)

## 2. Select an Orange Pi OS image.

Click on **Flash from file** and select a OS Image.

![Etcher](/docs/General_guides/images/etcher0.png)

![Etcher](/docs/General_guides/images/etcher1.png)

## 3. Select a MicroSD card drive.

Click on **Select target** and select your **MicroSD** drive. 

![Etcher](/docs/General_guides/images/etcher2.png)

![Etcher](/docs/General_guides/images/etcher3.png)

## 4. Perform the Write opration

Click on the **Flash!** button to write OS image to MicroSD card.

![Etcher](/docs/General_guides/images/etcher4a.png)

{{< hint info >}}
Sometimes Etcher gives you a warnning about MicroSD card being unusually large if you use a large size MicroSD card.
{{< /hint >}}

![Etcher](/docs/General_guides/images/etcher4b.png)


{{< hint info >}}
You may have to give **Root permission** to perform the write opration.
{{< /hint >}}


![Etcher](/docs/General_guides/images/etcher4c.png)

Wait for Etcher to finish the write opration.

![Etcher](/docs/General_guides/images/etcher5.png)

## 5. Success!

If you see **1 Successful target** then this MicroSD card is ready to boot on Orange Pi SBC.

![Etcher](/docs/General_guides/images/etcher6.png)