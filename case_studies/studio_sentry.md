# Case Study: StudioSentry
## The Deterministic Triage Engine

### 🧐 The "Industrialist" Bet
**The Neglected Vertical:** Creative freelancers and boutique studios (photographers, designers, artists).
**The Friction:** The "Success Tax"—as a creative gets better, they get more inquiries, which leads to more time spent on email/DMs and less time on the actual craft.
**Why Enterprise Fails Here:** CRM tools (Salesforce, HubSpot) are too expensive and complex for a solo creator. Generic AI chatbots are too probabilistic and prone to hallucinating pricing or availability, which damages a creative's reputation.

### ⚡ Builder Advocacy in Action
*   **Velocity:** Built a full Django + Gemini integration in 5 days.
*   **Sovereignty:** Instead of using a standard "Chat UI," I advocated for a **Blueprint-First** architecture. This ensures that the AI is grounded in the studio's "DNA" (rules, pricing, FAQs) before it ever sends a response.
*   **The Bargain:** Proved that a single architect can deploy a custom "Business DNA" scraper and classifier faster than a studio owner could manually triage their inbox for a week.

### ♿ The Universal Accessibility Impact
*   **Accessibility:** Focused on high-contrast lead-capture forms that work on older mobile devices (common for clients on the go).
*   **Dignity:** The system doesn't just "collect leads"; it treats every inquiry with professional precision, ensuring that even "low-budget" inquiries get a respectful, deterministic "No" or a referral, rather than being ignored in an overflowing inbox.

### 📊 5-Day MVP Benchmarks
- **Day 1:** Business DNA Schema design (Pydantic models).
- **Day 2:** Django backend and Lead Triage logic.
- **Day 3:** Gemini 2.5 Flash integration with `instructor`.
- **Day 4:** Bootstrap 5 UI and Lead Dashboard.
- **Day 5:** Deployment to Render and validation tests.
