# Niyyah Email Health Dashboard

A real-time dashboard for monitoring email sending health metrics.

## Features

- DNS Authentication status (SPF, DKIM, DMARC)
- Bounce and complaint rate monitoring
- Open and click rate tracking
- Email activity summary
- Auto-refresh every 60 seconds

## Setup

This dashboard connects to a Supabase Edge Function that provides the health data.

### Password

Default password: `niyyah2024`

To change it, update the `DASHBOARD_PASSWORD` secret in Supabase.

## Live URL

https://niyyah.github.io/email-dashboard/
