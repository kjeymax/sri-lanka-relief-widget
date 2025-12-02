# 🇱🇰 Sri Lanka Relief Widget

A lightweight, zero-dependency JavaScript widget to display disaster-relief and donation prompts on any website.  
Designed for **Sinhala & English**, fully responsive, and CDN-ready.

Supports multiple visual layouts (variants) that can be embedded anywhere in your site with a single script.

---

## ✨ Features

- ✅ Popup Modal (with floating trigger)
- ✅ Floating Action Button
- ✅ Sticky Header Banner
- ✅ Snackbar Notification
- ✅ Navigation Bar Banner
- ✅ In-Feed Content Card
- ✅ Mobile responsive
- ✅ Sinhala + English friendly
- ✅ No dependencies (pure JavaScript)
- ✅ CDN ready via jsDelivr
- ✅ Custom placement & target selector
- ✅ Clean UI with modern animations

---

## 🚀 Quick Installation

Add this before your closing `</body>` tag:

```html
<script>
  window.HSL_CONFIG = {
    variant: "popup",
    placement: "bottom-right",
    modal_title: "අපේම මිනිසුන් වෙනුවෙන් ❤️",
    modal_body: "ආපදා සහ අභියෝග හමුවේ පීඩාවට පත් අපේම සහෝදර ජනතාවට උදව් කරන්න."
  };
</script>

<script src="https://cdn.jsdelivr.net/gh/YOUR_USERNAME/YOUR_REPO@main/dist/slfldnt.js"></script>
