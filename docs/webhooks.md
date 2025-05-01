# Webhook Configuration

Follow these steps to configure your TastyIgniter webhook so that TaCo (TastyIgniter Companion) receives real-time **order** updates.

---

## 1. Open Webhooks in TastyIgniter Admin

1. Log in to your TastyIgniter back-end.  
2. Go to **System → Settings → Webhooks**.  
3. Click **Create New** (or edit an existing webhook).

---

## 2. Basic Settings

- **Name**: `Order`  
  _(This helps you identify the webhook — it can be anything, but “Order” is clear.)_

- **Payload URL**:  
https://tastycompanion.dineabyte.de/api/receive-event/restaurant.com

![](webhooks.images/1.png)