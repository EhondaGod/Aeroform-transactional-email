# Aeroform — Transactional Order Receipt Email

A responsive, hand-coded HTML email template built for **Aeroform**, a custom computer shop. This transactional receipt confirms customer orders with itemized pricing, shipping details, and support information.

## 🛠 Technical Highlights
* **Raw HTML Table Architecture:** Built entirely using nested `<table>` layouts (`role="presentation"`) rather than modern CSS Grid or Flexbox to ensure consistent rendering across legacy and modern email clients (Outlook, Gmail, Apple Mail).
* **Inline CSS:** All styling is applied inline to prevent email clients from stripping `<style>` blocks.
* **Clean & Scannable Layout:** Structured for quick readability with clear visual hierarchy for order numbers, itemized hardware components, and billing totals.

## 📂 Usage
1. Clone or download the HTML file.
2. Replace the placeholder variables (e.g., `{{customer_name}}`, `{{order_id}}`, `{{line_items}}`) with your backend templating engine or ESP tags.
3. Inline any remaining styles if modifying the code, then test via your preferred email testing tool before deploying.
