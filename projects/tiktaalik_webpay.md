---
layout: project
type: project
image: img/tiktaalik/tiktaalik-webpay-logo-263x300.png
title: "Tiktaalik WebPay"
date: 2022
published: true
labels:
  - PHP
  - Joomla
  - Hikashop
summary: "A Joomla plugin to enable Chile's Transbank WebPay payment platform in the Hikashop e-commerce extension."
---
 
<img class="img-fluid" src="../img/tiktaalik/tiktaalik-webpay-logo.png" alt="Tiktaalik WebPay Logo">

***Tiktaalik WebPay*** is a payment gateway plugin I created as a commercial product for my own business. The product was developed an made available for the public on 2022, and intended to adress the lack of a payments plugin that could allow Chilean buinesses to utilize the Hikashop e-commerce extension to build theit e-commerce store, and receive credit card payments from Chilean customers.

***Tiktaalik WebPay*** was implemented using PHP v7.2+, the [Hikashop e-commerce extension API](https://hikashop.com) for the Joomla Content Managment System (CMS), and the [Transbank SDK](https://www.transbankdevelopers.cl) (which required PHP 7.2).

While developing this product I learned how to integrate three different APIs into a codebase that would handle both the backend and frontend of an existing system. This also included ensuring that the transaction data was recorded in the database, and handling the different transaction results to ensure a smooth purchase experience for the customers.

The product is still fully functional and it currently powers several websites, including my own business website [Tiktaalik Dev](https://tiktaalik.dev).

<span class="text-decoration-underline">___To Do___</span>: As the product did not have the expected demand from the public, I stopped developing for the time being. But I intend to update it soon to cater for the newer versions of Joomla and Hikashop, as well as the newer versions of the Transbank WebPay API.

***The product demo page is available online*** [in my website](https://tiktaalik.dev/tienda/productos/prod/demo-webpay). This page offers a fictitious product that allows testing the plugin functionality directly in my own website.
