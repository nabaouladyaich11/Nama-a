<div align="center">

# نماء | Namaa
### قرارك اليوم... نماءٌ لغدك
**المدير المالي الذكي للمنشآت الصغيرة والمتوسطة**

An AI CFO for Saudi SMEs — reads the business's own invoices, predicts cash deficits
before they happen, and proposes an optimal, owner-approved payment plan.

🔗 **جرّب المنتج مباشرة: [namaly.app](https://namaly.app)**

Built for **Amad 2026 Hackathon** — Tuwaiq Academy × **مصرف الإنماء | Alinma Bank**
مسار الذكاء الاصطناعي التوليدي للتقنية المالية

`React + TypeScript` · `Python AI Engine` · `RTL Arabic UI` · `Live on namaly.app`

</div>

---

## 💡 What Namaa does — احمِ · وفّر · انمُ

| Pillar | Capability |
|---|---|
| 🛡️ **احمِ** | Probabilistic 45-day cashflow simulation detects deficits with date, amount, and probability — then an RL agent proposes the optimal fix (defer within supplier terms / split invoices). **Payroll is locked out of the action space by design.** |
| 💰 **وفّر** | Profit-leak detector: duplicate invoices, gradual supplier price creep — recovered **5,500 SAR** in the demo scenario without any user action. |
| 📈 **انمُ** | "اسأل نماء" decision simulator: inventory, hiring, and expansion questions answered from the business's own numbers. Usage builds a credit-ready financial profile — a qualified financing channel for the bank. |

**Trust model:** الوكيل يجهّز — المالك يقرر. Financial numbers come from a deterministic, auditable engine (zero hallucination); the owner approves every action.

## 🖥️ Live prototype — [namaly.app](https://namaly.app)

Five connected Arabic RTL screens: لوحة التحكم (health score 71→84) → الفواتير (upload + extraction) → التدفق النقدي (deficit radar + AI plan) → الموافقات (supplier negotiation message, one-tap approve) → اسأل نماء (proactive CFO briefing).

Demo scenario: **متجر أثير للعطور** — a Saudi online perfume brand whose payment-gateway settlements arrive after payroll day.

## 🧠 AI Engine — [`engine/`](./engine)

Runnable proof pack (Google Colab, one cell):
- **2,000 synthetic invoices** matching Saudi e-invoice (فاتورة) field structure
- **Monte Carlo cashflow** — 3,000 runs: deficit probability near-certain → **10%** with Namaa's plan
- **Q-learning scheduler** — 4,000 episodes, converges on the optimal plan, salaries never touched
- **Auditable health score** — weighted composite, 71 → 84

## 🛠️ Tech Stack

**Frontend:** React + TypeScript, Vite, Tailwind, Chart.js — Arabic RTL, Cairo font
**AI Engine:** Python, NumPy, Matplotlib (Monte Carlo + Q-learning)
**Build & Deploy:** Replit (published at namaly.app), Google Colab, GitHub

## 🎓 Team — فريق نماء

Built at **Amad 2026 Hackathon** (أمد — Tuwaiq Academy × Alinma Bank) by:

- **نبأ عبد الرحمن أولاد يعيش**
- **لينة سعود المطرفي**
- **أريام حمدان الهذلي**
- **رتاج عنيبر القارحي**
- **سندس علي العمري**
---

<div align="center">

**نماء — لأن كل منشأة تستحق مديرًا ماليًا 🌱**

</div>
