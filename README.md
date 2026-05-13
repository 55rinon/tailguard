# TailGuard

TailGuard is a retail-friendly crypto risk guidance layer that fetches market data, detects abnormal stress, and converts it into position guidance before users size a trade.

## What it does

TailGuard turns market stress into a simple retail decision interface:

- Risk Level
- 24h Change
- Suggested Size
- Why / Action / Goal
- Agent Action Log

## Current MVP

The current MVP is built in Bubble.

Current BTC demo flow:

1. Select BTC
2. Fetch market data from API
3. Convert market stress into a retail-facing risk state
4. Show suggested position size
5. Show short decision guidance for the user

Current BTC interface shows:

- Risk Level
- 24h Change
- Suggested Size
- Why / Action / Goal
- Agent Action Log

## Why it matters

Retail users often see market data but still do not know how aggressively they should trade.

TailGuard focuses on risk control rather than prediction. It helps users detect abnormal stress conditions early and convert them into clear position guidance before taking risk.

## Current direction

TailGuard is evolving from a static tail-risk dashboard into an API-backed retail risk decision prototype.

The current direction is:

- market data input
- risk interpretation
- position guidance
- action-oriented explanation

## Status

Working MVP / MOC

## Stack

- Bubble
- SoDEX Spot API
- GitHub

## What is already working

- Bubble MVP UI
- API connection through Bubble API Connector
- BTC ticker fetch from SoDEX Spot API
- 24h Change display
- rule-based Risk Level display
- rule-based Suggested Size display
- retail-facing explanation blocks

## Data flow

Current flow:

`Asset selection → market data fetch → risk interpretation → suggested size`

## Product thesis

TailGuard does not try to predict the next move perfectly.

Instead, it helps users detect stress before they size a trade.

## Next steps

- improve live API-backed explanation logic
- expand beyond BTC
- refine action logic from guidance to stronger execution flow
- improve product clarity for retail users
- add more complete insight-to-action workflow

## Demo Screenshot

Current TailGuard MVP interface showing BTC risk state, 24h change, suggested size, and action-oriented guidance.

![TailGuard demo](tailguard-demo.png)

## About

Retail-friendly crypto tail-risk dashboard and risk guidance tool.
