---
title: Telegram Dispatch Helper - Privacy Policy
---

<style>
/* The Pages theme prints the repo name ("privacy-policy") as a big
   link above the content. Hiding it keeps the page looking like a
   document rather than a directory listing. */
.markdown-body > h1:first-child { display: none; }

/* The document title: centred, without the rule under every h2. */
.markdown-body > h2:first-of-type {
  text-align: center;
  border-bottom: none;
  padding-bottom: 0;
  margin-bottom: 2rem;
}

.tdh-updated {
  margin-top: 3rem;
  text-align: right;
  font-size: 0.85em;
  font-style: italic;
  color: #656d76;
}
</style>

## PRIVACY POLICY — TELEGRAM DISPATCH HELPER

## What the extension does
It reads load updates that brokers post in a fixed list of Telegram chats and writes the check-in, check-out and ETA times into the matching load in the Logity ERP (erp.gologity.com).
It works only while you have the ERP's dispatch board open and the extension switched on, and it switches itself off after eight hours.

## Your Telegram account
You sign in by scanning a QR code with the Telegram app on your phone, on Telegram's own login.
The extension never sees or stores your Telegram password or phone code.
The login it receives (the session), and the Telegram API id and hash you type in Setup, are kept only inside Chrome on your PC.
The Telegram connection goes straight to Telegram's servers.

## Your Telegram messages
Only messages in the listed chats, from the listed senders, are read. Everything else is ignored.
A message the extension handles gets a 👍 reaction from your account, so others can see it was done.
The extension keeps a History of the last 300 handled messages, with their text and the result, on your PC only.

## Your ERP account
The extension uses the ERP login you already have in your open ERP tab. It never asks for or stores your ERP password.
It reads the dispatch board in that tab to find the load a message is about, reads that load's stops and writes the one time the message gives.
This data goes only between your browser and erp.gologity.com.

## What leaves your PC
To make sure two copies of the extension never act on the same message, and to check your subscription, the extension keeps one connection to our coordination server (hosted on Cloudflare).
It sends only:
- your numeric Telegram account id;
- whether your copy is online, with a short "still here" signal.

The server keeps:
- which copies were online, for the last hour;
- your subscription's record: your Telegram account id, your Stripe customer and subscription ids, the subscription's status and the date it is paid until.

The server never receives a Telegram message, a load, or anything from the ERP.

## Payments
Subscriptions are paid through Stripe, on Stripe's own checkout page.
Your card details go to Stripe only; the extension and our server never see them.
Stripe's own privacy policy applies to what you enter there.

## Privacy concerns
- Nothing is sold or shared with outside companies, beyond Stripe processing your payment.
- There is no advertising and no analytics.
- No data is used for anything other than the features described here.

## Removing everything
To remove the extension, right-click its icon and select "Remove from Chrome". Everything it kept on your PC — the Telegram login, the API id and hash, the History and the settings — is deleted with it.
Cancelling your subscription is done from the Subscription box in the extension's Setup page.
To have your subscription record deleted from our server, contact the developer.

## Not affiliated
This extension is not made by, endorsed by or affiliated with Telegram or Logity.

## Contact
Contact the developer through the extension's Chrome Web Store page.

<p class="tdh-updated">3 October 2026</p>
