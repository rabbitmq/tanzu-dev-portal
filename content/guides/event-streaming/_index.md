---
title: Event Streaming
weight: 1
tags:
- Event Streaming
description: >
    Event streaming enables services to simply emit “events” that are open for any interested services to consume.
layout: single
---

Event streaming can be thought of as flipping the flow of requests in the opposite direction. Instead of a standard call-response cadence to communicate with each other, services simply emit an “event”—any significant change-of-state—that is open for any interested services to consume. Some frameworks like [Spring Cloud Stream](/guides/event-streaming/scs-what-is/) ease the integration with these messaging services.