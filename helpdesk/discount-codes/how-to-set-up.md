# How to Set Up Discount Codes

## What are Discount Codes?

The Discount Codes feature adds a field inside the cart drawer where customers can enter and apply discount codes before proceeding to checkout. This saves them from having to wait until the checkout page to see their savings.

![Discount Codes in cart drawer](/.gitbook/assets/discount-codes/what-is.png)

## Why use Discount Codes?

- **Reduce friction** — Customers can apply discounts right in the cart drawer, making the experience faster and smoother.
- **Build confidence** — Seeing the discount applied before checkout reassures customers and reduces cart abandonment.
- **Drive promotions** — Encourage customers to use your promo codes by making the input field visible and accessible.

## Requirements before using

- You must have the **AOV.ai Cart Drawer** app installed and active.
- Discount codes must be created in **Shopify Admin > Discounts** before they can be used in the cart drawer.

## How to Set Up?

### Step 1: Open Discount Codes Settings

1. Go to **AOV.ai Cart Drawer > Cart Editor**.
2. Click **Discount codes** in the left menu under **Body**.

<!-- screenshot: Discount codes menu item in the Cart Editor sidebar | page: /cart-editor | element: .discount-codes-menu | annotate: yes -->

![Open discount codes settings](/.gitbook/assets/discount-codes/step-1.png)

### Step 2: Configure Labels and Text

1. Enter the **Discount trigger label** — The text on the collapsible trigger that customers click to reveal the discount input field.
2. Enter the **Discount title** — The heading above the input field.
3. Enter the **Button label** — The text on the apply button (e.g., "Apply").
4. Enter the **Placeholder** — The hint text inside the input field (e.g., "Enter discount code").
5. Enter the **Error message** — The message shown when an invalid code is entered.

<!-- screenshot: Discount codes label fields - trigger label, title, button label, placeholder, error message | page: /cart-editor | element: .discount-codes-labels | annotate: yes -->

![Discount codes labels and text](/.gitbook/assets/discount-codes/step-2.png)

### Step 3: Configure Additional Options

1. Toggle **Show remove discount button** to let customers remove an applied discount code.
2. Review the **Discount limitations** section to understand what is supported:
   - Free shipping discounts are not supported in the cart drawer. Customers must go to checkout to apply free shipping discounts.
   - Shopify Plus stores using checkout.liquid are not supported. The discount codes module will be hidden on the real storefront if your store is using checkout.liquid.

<!-- screenshot: Remove button toggle and discount limitations notice | page: /cart-editor | element: .discount-codes-options | annotate: yes -->

![Additional options and limitations](/.gitbook/assets/discount-codes/step-3.png)

### Step 4: Preview and Save

1. Review the discount codes section in the live preview on the right panel.
2. Click **Save** to apply your settings.

<!-- screenshot: Preview showing discount codes section with Save button | page: /cart-editor | element: button:has-text('Save') | annotate: yes -->

![Preview and save](/.gitbook/assets/discount-codes/step-4.png)

Your discount codes field is now active in the cart drawer. Customers can apply their promo codes instantly and see their savings before checkout! 🚀
