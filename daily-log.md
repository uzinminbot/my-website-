# Daily Log — Quick Capture for my-website

သရုပ်ပြချက်
- ဤဖိုင်သည် နေ့စဉ်လုပ်ဆောင်ချက်များကို ချက်ချင်း ဖမ်းရန်နှင့် Git မှာ micro-commit ဖြင့် သိမ်းဆည်းရန် အချက်အလက်ရရေးဖိုင် ဖြစ်သည်။

နည်းလမ်း ၆ ချက် (Quick-capture + Micro-commit)

1) ချက်ချင်းဖမ်းရန် — အကြမ်းဖျင်း
   - အလုပ်စတင်တိုင်း 1–2 စက္ကန့်တွင် "ဘာလုပ်နေသည်" တစ်ကြောင်း မိုဘိုင်း Notes သို့ မိုက်ကရို voice memo ဖန်တီးပါ။
   - ဥပမာ: "09:15 — header CSS ပြင်, margin ပြင်"

2) Micro-commits (git ဖြင့်)
   - တစ်ခုချင်းတာပြီးချင်း git add . && git commit -m "wip: header CSS fix — responsive"
   - အလုပ်တစ်ခုစီအတွက် သေးငယ်သော commit များ စုဆောင်းပါ။

3) ရိုးရှင်းတဲ့ daily-log ဖိုင်
   - ဤ repo အတွင်း daily-log.md ထဲတွင် တိုက်ရိုက်လိုင်းတစ်ကြောင်းဖြင့် မှတ်တမ်းထားပါ။
   - Format နမူနာ:
     - 2026-09-12 09:15 — Update header CSS — committed wip:header
     - 2026-09-12 10:40 — Fixed responsive layout — commit: wip:responsive

4) အလုပ်ကို သေးငယ်စိတ်ပိုင်း (chunking)
   - တစ်ခုစီကို 10–25 မိနစ်အတွင်း ပြီးမြောက်စေဖို့ အာရုံချပြီး Pomodoro စတိုင်လုပ်ပါ။
   - ပြီးသည့်အခါ commit တစ်ချက်နှင့် daily-log ထဲတွင် မှတ်တမ်းထည့်ပါ။

5) အလိုအလျောက် (automation) - ရွေးချယ်စရာ
   - GitHub Action တစ်ခုရေး၍ commit message တွေကို parse လုပ်ပြီး daily-log.md ကို auto-append ပြုလုပ်စေပါ။
   - (သင့်လိုလျှင် ငါ Action ကို ဖန်တီးပေးနိုင်သည်။)

6) ရိုးရှင်း template များ
   - Commit message template (short):
     - type(scope): short summary
     - Why: (optional short note)
     - TODO: (optional)
   - daily-log entry (one-line): timestamp + short action + commit message


How to use (ကြိုတင်အဆင့်များ)
- အလုပ်ပြီးချင်း terminal မှာ
  - git add -A
  - git commit -m "wip:<short> — <why?>"
  - git push
- တစ်ချိန်ချိန်တွင် daily-log.md ထဲကို တိုက်ရိုက် တစ်လိုင်းထည့်ပါ (သို့) commit message အရ GitHub Action ကိုသုံး၍ auto-append လုပ်ပါ။

Entry Examples
- 2026-09-12 09:15 — Update header CSS — committed wip:header
- 2026-09-12 10:40 — Fixed responsive layout — commit: wip:responsive

Notes
- ဒီဖိုင်သည် အလွန်ရိုးရှင်းပြီး တိုက်ရိုက်ဖတ်ရလွယ်စေရန် ဖန်တီးထားပါသည်။
- ကြိုက်သလိ�� format ပြင်ပါ — အရေးကြီးတာက "ချက်ချင်းဖမ်းပြီး သေးငယ်သော commit" ကို အလေ့လုပ်ရန်ပဲ။

---

Generated for repository: uzinminbot/my-website-
