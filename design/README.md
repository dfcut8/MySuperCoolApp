# Parcel tracking app — screen concepts

Three light-appearance iOS screen concepts generated with the built-in image generation tool. These are raster design mockups with illustrative data, not implemented application screens.

- `01-deliveries.png`: active shipments, status summaries, search, and navigation.
- `02-parcel-details.png`: arrival estimate, milestones, tracking history, and notifications.
- `03-add-parcel.png`: barcode scanning, manual tracking entry, carrier detection, and parcel naming.

## Generation prompts

### 01-deliveries.png

```text
Use case: ui-mockup.
Asset type: High-fidelity iOS parcel-tracking application screen for design review.
Generate exactly ONE flat, front-facing, full-bleed app screenshot, portrait 1200x2600 (approximately 6:13), no physical phone frame, no surrounding presentation background, no perspective, no watermark.
Design system shared across a three-screen set: native iOS light appearance, very pale cool gray grouped background, white cards with subtle borders, almost-black text, system blue primary actions, semantic green and orange status badges with written labels, SF Pro-like typography, SF Symbols-like thin line icons, 24pt horizontal safe margins at logical 400pt width, 20pt card corners, restrained shadows, strong type hierarchy and generous whitespace. Crisp legible text. Status bar 9:41 with cellular/Wi-Fi/battery, black Dynamic Island centered, bottom home indicator. No gradients or decorative illustrations. Design should feel polished and practical. Preserve all requested exact wording; do not add extraneous copy. Dummy data only.
Screen 1: Deliveries dashboard.
Below safe area show small date "FRIDAY, NOVEMBER 13", then large title "Deliveries", a blue circular plus button to add a parcel aligned at title right.
Search field "Search parcels".
Native segmented filter "Active 3" selected, "Delivered 12" unselected.
Prominent blue-tinted summary card: small line "ARRIVING TODAY", large "Your next delivery", small "1 parcel is out for delivery" and a simple outlined package icon.
Next heading "On the way" and three white parcel cards stacked, each with a small line icon tile, strong title and carrier line, written status badge, clear ETA and right chevron:
1. "Running shoes", "UPS · …8421", green "Out for delivery", "Today, 2–6 PM", tiny progress strip nearly complete.
2. "Desk lamp", "FedEx · …1904", blue "In transit", "Arrives tomorrow", tiny progress strip halfway.
3. "Coffee beans", "USPS · …0736", neutral "Label created", "Estimate pending", tiny progress strip just started.
Bottom fixed light translucent native tab bar with three equal destinations: "Deliveries" selected blue with shipping-box icon, "History" gray with clock icon, "Settings" gray with gear icon. Comfortable whitespace before tab bar, all cards fully visible.
```

### 02-parcel-details.png

```text
Use case: ui-mockup.
Asset type: High-fidelity iOS parcel-tracking application screen for design review.
Generate exactly ONE flat, front-facing, full-bleed app screenshot, portrait 1200x2600 (approximately 6:13), no physical phone frame, no surrounding presentation background, no perspective, no watermark.
Design system shared across a three-screen set: native iOS light appearance, very pale cool gray grouped background, white cards with subtle borders, almost-black text, system blue primary actions, semantic green and orange status badges with written labels, SF Pro-like typography, SF Symbols-like thin line icons, 24pt horizontal safe margins at logical 400pt width, 20pt card corners, restrained shadows, strong type hierarchy and generous whitespace. Crisp legible text. Status bar 9:41 with cellular/Wi-Fi/battery, black Dynamic Island centered, bottom home indicator. No gradients or decorative illustrations. Design should feel polished and practical. Preserve all requested exact wording; do not add extraneous copy. Dummy data only.
Screen 2: Parcel tracking detail, same app.
Top navigation: blue back chevron with "Deliveries", centered small "Parcel details", ellipsis action right.
Large title "Running shoes"; subtitle "UPS · …8421".
Green pill with check/truck icon "Out for delivery".
A blue-tinted arrival card with small "ESTIMATED DELIVERY", large "Today, 2–6 PM", supporting "Last updated at 9:38 AM".
Below this a clean thin 4-step horizontal milestone line with first three steps filled blue and final step outlined; labels "Confirmed", "In transit", "Out for delivery", "Delivered". Make current step clear.
Heading "Tracking activity". White grouped timeline card, reverse chronological, connected vertical line, blue current event and muted prior events:
"Out for delivery" / "Indianapolis, IN · Today, 8:42 AM"
"Arrived at local facility" / "Indianapolis, IN · Today, 6:15 AM"
"In transit" / "Louisville, KY · Yesterday, 11:20 PM"
"Shipment received" / "Louisville, KY · Nov 11, 3:10 PM".
Below, compact white grouped row "Delivery notifications" with green ON switch.
A full-width blue bottom action "View carrier website" with external-link icon.
Do not include a map or live vehicle location. No tab bar on this pushed detail screen. All text fits cleanly above bottom safe area.
```

### 03-add-parcel.png

```text
Use case: ui-mockup.
Asset type: High-fidelity iOS parcel-tracking application screen for design review.
Generate exactly ONE flat, front-facing, full-bleed app screenshot, portrait 1200x2600 (approximately 6:13), no physical phone frame, no surrounding presentation background, no perspective, no watermark.
Design system shared across a three-screen set: native iOS light appearance, very pale cool gray grouped background, white cards with subtle borders, almost-black text, system blue primary actions, semantic green and orange status badges with written labels, SF Pro-like typography, SF Symbols-like thin line icons, 24pt horizontal safe margins at logical 400pt width, 20pt card corners, restrained shadows, strong type hierarchy and generous whitespace. Crisp legible text. Status bar 9:41 with cellular/Wi-Fi/battery, black Dynamic Island centered, bottom home indicator. No gradients or decorative illustrations. Design should feel polished and practical. Preserve all requested exact wording; do not add extraneous copy. Dummy data only.
Screen 3: Add parcel form, same app.
Top navigation blue "Cancel" at left, centered "Add parcel". Large title "Track a delivery"; supporting text "Add a tracking number to get started."
A wide pale-blue button with scan barcode icon and exact text "Scan barcode", subtext "Use your camera".
Small divider text "or enter manually".
Form, separate labels above generous white rounded input fields:
Label "Tracking number", filled value "1Z999AA10123456784", copy/paste icon on right.
Label "Carrier", white selector with small generic parcel icon, "UPS", small blue "Detected" pill, right chevron.
Label "Parcel name (optional)", filled value "Running shoes".
White grouped row with bell icon, text "Delivery notifications", green ON switch; below in secondary text "Get updates when your parcel moves."
Substantial deliberate whitespace in lower half; no keyboard. Full-width blue primary action "Add parcel" anchored above bottom home indicator, enabled. No tab bar. This is the populated ready-to-submit state.
```
