---
id: stripe
title: Stripe Subscriptions
hide_title: true
hide_table_of_contents: false
sidebar_label: Stripe Subscriptions
description: This guide will show you how to setup a Stripe subscription and how to cancel it if neccesary.
keywords:
  - stripe
  - subscriptions
  - stripe recurring
---

<div class="text--center">
<img src="https://bloom.host/logo-white.svg" alt="logo" height="50%" width="50%"/>
<h1>Stripe Subscriptions</h1>
</div>

Hey Bloomers! In this guide we will be going over how to configure or cancel a Stripe Subscription.


## Configuring a Stripe Subscription when you first order a server

To configure a Stripe Subscription when you first order a server just select "Credit/Debit Card - Subscription (Stripe)" as the payment method.

<div class="text--center">
<img src={require('../../static/imgs/billing/stripe/1.png').default} alt="img"/></div>

## Configuring a PayPal Subscription when you are already a customer

If you have already a plan with us you will need to wait until the next invoice generates, then go to the invoices section on our [billing portal](https://billing.bloom.host/clientarea.php?action=invoices), select the latest unpaid invoice and under payment method select "Credit/Debit Card - Subscription" and configure the subscription.

<div class="text--center">
<img src={require('../../static/imgs/billing/stripe/2.png').default} alt="img"/></div>

## How to cancel a Stripe Subscription (Stop Recurring Payment)

To cancel a Stripe Subscription / Stop Recurring Payments you can go to the [Payment Methods](https://billing.bloom.host/index.php?rp=/account/paymentmethods) section of our billing portal and delete the Credit/Debit Card linked to your account. 

<div class="text--center">
<img src={require('../../static/imgs/billing/stripe/3.png').default} alt="img"/></div>

<div class="text--center">
<img src={require('../../static/imgs/billing/stripe/4.png').default} alt="img"/></div>