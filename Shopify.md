Here's the final procedure. It includes everything from the test runs, and all the steps worked on the test store.

# Zetra AI Chat: Shopify demo video

**Target length:** 4 to 6 minutes (Shopify accepts 3 to 8).

## Before you record

1. **Recorder.** Use Loom, OBS, or the Windows Snipping Tool's video mode, set to 1080p. Narration is recommended; captions are fine too.
2. **Clean browser.** Use Chrome. Close unrelated tabs, hide the bookmarks bar, turn off notifications, and set the zoom to 100%.
3. **Accounts.** Stay signed in to **zetra.chat** and to **Shopify** (with access to **zetra-dev-store**).
4. **Incognito window for Scene 4.** Open one now and leave it on the side. The storefront there won't show Shopify's admin bar, which otherwise covers the chat bubble.
5. **Have these ready:**
   - Order number: **#1001**
   - Checkout email: **test-customer@zetra.chat**
   - The storefront password: in the store admin, go to **Online Store → Preferences**
6. **Optional:** to keep the inbox tidy on screen, delete or close the old test tickets in Zetra's **Helpdesk inbox → All**.
7. **Rehearse once** without recording. When you finish rehearsing, uninstall the app again (**Settings → Apps → Zetra AI Chat → ⋯ → Uninstall**) so the recording starts fresh.

## Scene 1: Install the app (about 1 minute)

1. Go to **dev.shopify.com/dashboard** and open **Zetra AI Chat**.
2. In the **Installs** box on the right, click **Install app**. A new tab opens. Choose **zetra-dev-store**.
3. Shopify shows **"Install app"** with **"Zetra AI Chat needs access to:"**. Explain each section:
   - **View store data – products, orders, Online Store:** product answers and product cards; order tracking, including orders older than 60 days; checking that the chat bubble is switched on in the theme.
   - **View customer data:** checking the order number against the checkout email or phone before showing an order.
   - **View staff and contributor data (store owner):** the store's basic account details, which come with the install.
4. Click **Install**. Point out that you land straight in Zetra. Shopify reviewers check for this.

## Scene 2: Connect your Zetra account (about 1 minute)

1. Zetra opens **"Connect your store to Zetra"** for zetra-dev-store.myshopify.com. Sign in if asked.
2. Click **My Store**. You have two agents, so Zetra asks you to choose.
3. Zetra opens **My Store → Channels → Shopify**, which shows **"Connected – zetra-dev-store.myshopify.com"**.
4. Walk through the **App embeds** guide and the numbered setup steps on this page.

## Scene 3: Merchant setup (about 1.5 minutes)

1. Click **Open theme editor**. The **App embeds** panel opens, and **Zetra chat** is already **on**.
   - Point at the switch and say that this is the one switch a merchant turns on.
   - Optionally, switch it off and on again, then click **Save**.
2. Go back to Zetra and open **Playground → Display**. Show the bubble's name **"Zetra Store"**, the welcome message, and the three suggested questions.
3. Open **Build → Data sources**. Show the two sources: **Shopify products** and **Zetra Store: shipping, returns and support**.
4. In the **Playground**, ask **"Do you offer free shipping?"** It should answer: free on orders over $75, otherwise $6.

## Scene 4: The customer's view (about 2 minutes)

1. Switch to the **incognito window**. Open **zetra-dev-store.myshopify.com** and enter the store password.
2. Click the chat bubble in the bottom-right corner. Show the **Zetra Store** greeting and the suggested questions.
3. Click **"Do you have a green bomber jacket?"**
   - Product cards appear, starting with the **Zetra Forest Green Bomber Jacket ($129)**.
   - Click **Select options** to open the product page.
4. Type **"What sizes does it come in?"** Expected answer: XS, S, L and XL (M is sold out).
5. Type **"Is the denim trucker jacket on sale?"** Expected answer: on sale for $110, down from $140.
6. Type **"Where is my order?"** When Zetra asks, type **#1001, test-customer@zetra.chat**. Show the order card: **#1001 · October 1, 2026 · $9.95**, Selling Plans Ski Wax, Confirmed, with a **View details** button.
7. Type **"I'd like to talk to a person."** A ticket card appears, saying the team will follow up.
8. *(Optional)* Type **"Can you check order #1001 for wrong-person@example.com?"** Zetra refuses to share the order. Do this **after** step 7, so the ticket shows the real customer.
9. Go back to Zetra and open **Helpdesk inbox**. Click **All**, because **My inbox** starts empty. The new ticket is at the top.

## Ending

Don't uninstall the app at the end. Leave it installed with the chat bubble on, so Shopify's reviewers find the store ready to test.

## After recording

1. Trim pauses and dead time, and check the audio.
2. Upload to **YouTube as Unlisted**. Shopify's reviewers can't open Private videos, Google Drive or Vimeo.
3. Send me the link. I'll add it to the listing, save it, and ask you before clicking **Submit for review**.
