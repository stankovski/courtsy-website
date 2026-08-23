---
layout: default
title: Security at Courtsy
description: How Courtsy protects court reservation, account, and billing information.
permalink: /security/
page_class: document
---

# Security at Courtsy

Effective date: August 22, 2026

Courtsy helps communities manage court reservations. We design the service to collect only the information it needs and to protect it while it is in use. This page explains our approach in plain language. No online service can guarantee perfect security, but we work to prevent unauthorized access, limit the data we retain, and respond to problems.

## Protecting Personal Data

We collect personal information only when it is needed for sign-in, reservations, account administration, billing, or support. People viewing a public court schedule do not need to provide an email address.

We use passwordless sign-in links, signed court and cancellation links, and secure session cookies to help verify requests and protect access. Public reservation schedules show only a booker's first name and last initial, never an email address.

We apply browser protections that help prevent common web attacks. These include encrypted connections in production, restrictions on which site resources can load, protection against unwanted framing, limits on browser features, and controls that reduce unsafe content handling.

We limit how long we keep most of the data: active daily reservation data expires at the court's next local midnight, and closed support cases are retained for 30 days.

## Protecting Billing Data

Paid subscriptions use Stripe Checkout. Card details are entered with Stripe, and Courtsy does not store full payment card numbers. We retain payment-related references and the billing details needed to operate the subscription, support the account, and meet legal obligations.

## Keeping the Service Available

Courtsy continuously monitors critical service operations and infrastructure and our team is ready to respond to incidents 24x7.

## Monitoring and Incident Response

We collect limited operational and error information to maintain security and reliability. Before errors are sent to telemetry, we redact email addresses, authentication tokens, secrets, credentials in connection strings, and URL query values.

If we identify a security issue, we investigate, contain it, and take reasonable steps to address it. When required by applicable law, we will notify affected people or organizations about a confirmed breach of personal data.

## Your Role

Keep your email account secure because it may be used to receive Courtsy sign-in and reservation links. Do not forward sign-in or cancellation links to others. Contact us promptly if you think someone has accessed your Courtsy account without permission.

## Report a Security Concern

To report a possible security vulnerability or security concern, use the Courtsy contact page. Please include enough detail for us to investigate, but do not send passwords, payment card numbers, authentication tokens, or other sensitive information in your message.

For more information about how we collect and use personal information, see the [Privacy Policy]({{ '/privacy/' | relative_url }}).

## Changes to This Page

We may update this page as our security practices change. The effective date above shows when it was last revised.