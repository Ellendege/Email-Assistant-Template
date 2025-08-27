# Project 1 — Email Assistant Template

## Overview
This project builds a **reusable email assistant** using prompt engineering.  
The assistant can generate three types of emails:
- Apology emails
- Welcome emails
- Complaint responses  

Each prompt uses variables like:
- `{{customer_name}}`
- `{{issue}}`
- `{{tone}}`
- `{{make_good}}`
- `{{cta}}`  

## How It Works
1. Prompts are stored in Colab text cells (see `prompts.md`).
2. Replace variables with your own values.
3. Run the prompt in any LLM (ChatGPT, Hugging Face, OpenAI API).
4. Collect outputs → log them in Notion for iteration history.

## Sample Outputs

### Apology Email
 **Subject:** Apologies for the Delay on Your Order

Dear Sapphire Wanjiru,

We sincerely apologize for the delay in delivering your order **#3456jk**. An unexpected logistics issue held us back, but your order is now on its way and will reach you shortly.

As a token of our appreciation for your patience, we’ve added a **10% discount** on your next purchase. Simply use the code **THANKYOU10** at checkout.

We truly value your trust in us and are working hard to ensure smoother deliveries moving forward.

If you have any questions or need further assistance, please don’t hesitate to reply to this email—we’re here to help.

Warm regards,

[Your Name]

Customer Care Team

### Welcome Email
**Subject:** Welcome to the Renewable Energy Program, Brian 🌱

Hi Brian,

We’re excited to have you on board! By joining the Renewable Energy Program, you’re taking a big step toward a cleaner and smarter future. Here’s what you can look forward to:

- ⚡ Lower energy costs through sustainable solutions
- 🌍 A positive impact on the environment and your community
- 📊 Easy access to track your progress anytime

Your personalized dashboard is ready to help you get started.

👉 [Explore your dashboard]

Thanks for joining us—we’re here to support you every step of the way.

Cheers,

The Renewable Energy Team

### Complaint Response
**Subject:** We’re Here to Help with Your Gas Usage

Dear Emily,

Thank you for sharing your concern—we understand how worrying it can feel to notice lower gas usage than expected.

To help, our team will first check your meter readings and account activity to confirm everything is recording correctly. If needed, we’ll arrange a technician visit to inspect your cylinder and meter setup.

You can expect an update from us within the next **48 hours**. In the meantime, please let us know if you’ve recently changed your cooking habits or appliances, as this may also affect usage.

We’re committed to resolving this quickly and making sure you feel confident about your service.

Warm regards,

[Your Name]

Customer Support Team




## Reflections
- Clear constraints (tone, word limits, CTA) improve consistency.
- Using variables makes prompts portable across many cases.
- Next iteration: add optional signature block + alternative CTAs.

---

📌 See full prompts in [`prompts.md`](./prompts.md).  
📒 Iteration notes are logged in Notion (`Intermediate Project 1 — Email Assistant Template`).  


