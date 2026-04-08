# How to Set Up Announcements

## What are Announcements?

Announcements are short messages displayed at the top of your cart drawer. They can be used to create urgency, promote offers, or communicate important information. You can choose from several styles including static text, cart reservation countdowns, rotating messages, and running-line (marquee) text.

## Why use Announcements?

- **Create urgency** — A cart reservation timer motivates customers to complete their purchase before items are released.
- **Promote offers** — Rotating or running-line announcements let you showcase multiple messages like free shipping thresholds or sales.
- **Guide shoppers** — Use a simple text announcement to share helpful info like shipping cut-off times or return policies.

## Requirements before using

- You must have the **AOV.ai Cart Drawer** app installed and active.
- The Cart Editor should be set up with at least the basic configuration.

## How to Set Up?

### Step 1: Open Announcements Settings

1. Go to **AOV.ai Cart Drawer > Cart Editor**.
2. Click **Announcements** in the left menu under **Body**.

<!-- screenshot: Announcements menu item in the Cart Editor sidebar | page: /cart-editor | element: .announcements-menu | annotate: yes -->

![Open announcements settings](/.gitbook/assets/announcements/step-1.png)

### Step 2: Choose an Announcement Type

1. Under **Announcements type**, select one:
   - **Normal text** — A single static message displayed at the top of the drawer.
   - **Cart reservation** — A countdown timer that reserves the cart for a set duration, creating urgency.
   - **Rotating** — Multiple messages that cycle through automatically, like a carousel.
   - **Running line** — A scrolling marquee-style message that moves across the announcement bar.

<!-- screenshot: Announcements type selector showing Normal text, Cart reservation, Rotating, Running line | page: /cart-editor | element: .announcements-type-selector | annotate: yes -->

![Choose announcement type](/.gitbook/assets/announcements/step-2.png)

### Step 3: Configure the Message and Timer

1. Enter your **Announcement message**. You can use markdown formatting:
   - Use `**content**` for **bold** text.
   - Use `*content*` for *italic* text.
2. If you selected **Cart reservation**, configure:
   - **Timer duration (minutes)** — How long the reservation countdown lasts.
   - **Action when time's up** — Choose what happens when the timer runs out:
     - **Hide the countdown** — Simply removes the timer.
     - **Repeat the countdown** — Restarts the timer automatically.
     - **Remove all items** — Clears the cart when time expires.
3. If you selected **Rotating**, click **Add new message** to add multiple messages and set:
   - **Announcement carousel auto play** toggle.
   - **Interval (Seconds)** — How long each message displays before rotating.
4. If you selected **Running line**, enter the scrolling message text.

<!-- screenshot: Message input field and timer configuration for Cart reservation | page: /cart-editor | element: .announcements-message-section | annotate: yes -->

![Message and timer settings](/.gitbook/assets/announcements/step-3.png)

### Step 4: Customize Announcement Colors

1. Under **Colors**, set the visual style:
   - **Background color** — The background of the announcement bar.
   - **Text color** — The color of the announcement message.
   - **Countdown timer color** — The color of the timer digits (for Cart reservation type).
   - (Optional) Toggle **Enable gradient background** and set **Gradient start color** and **Gradient end color**.

<!-- screenshot: Color settings for announcement bar | page: /cart-editor | element: .announcements-colors-section | annotate: yes -->

![Announcement colors](/.gitbook/assets/announcements/step-4.png)

### Step 5: Preview and Save

1. Review the announcement in the live preview on the right panel.
2. Click **Save** to apply your announcement settings.

<!-- screenshot: Preview showing announcement bar at top of cart drawer with Save button | page: /cart-editor | element: button:has-text('Save') | annotate: yes -->

![Preview and save](/.gitbook/assets/announcements/step-5.png)

Your announcement is now active in the cart drawer. Use urgency and promotional messages to motivate customers to complete their purchase! 🚀
