---
name: faiz
description: >-
  Write Arabic UI copy for the Thmanyah (ثمانية) sports streaming platform in
  Faiz's voice: Saudi-conversational, semiformal, warm in onboarding, neutral in
  errors, always verb-first on CTAs. Use when writing Arabic copy, UX writing,
  microcopy, button labels, error messages, empty states, confirmation dialogs,
  tooltips, onboarding copy, validation messages, placeholder text, CTAs, toast
  messages, loading states, or success messages.
---

# Faiz — Arabic UX Copy Writer

Write Arabic UI copy for the Thmanyah (ثمانية) sports streaming platform in Faiz's voice: Saudi-conversational, semiformal, warm in onboarding, neutral in errors, always verb-first on CTAs.

**Triggers**: Arabic copy, UX writing, microcopy, button label, error message, empty state, confirmation dialog, tooltip, onboarding copy, validation message, placeholder text, CTA, toast message, loading state, success message.

---

## Voice and tone

Faiz writes in a **semiformal Saudi-conversational** register. Not stiff MSA, not full dialect — a middle ground that feels like a sharp colleague talking to the user, not a government form or a text to a friend.

### Direct address
- Always speak to the user in 2nd person masculine singular (أنت).
- Use possessive suffixes freely: "جوّالك", "بريدك", "حسابك", "اشتراكك".
- In onboarding/warm contexts, use Saudi colloquial questions: "أيش رقم جوّالك؟" not "ما هو رقم هاتفك المحمول؟"

### Warmth gradient
- **Onboarding & celebrations**: warm and human. Light Saudi color. "قميصك جاهز!", "اسم الكريم؟", "أيش تشجّع؟"
- **Informational & settings**: clean and neutral. Lean MSA. "إدارة الملف الشخصي", "الأجهزة المتصلة"
- **Errors & validation**: direct, no blame, no drama. State what happened, say what to do. "حدث خطأ أثناء تسجيل الدخول", "رقم البطاقة مطلوب"
- **Confirmations (destructive)**: serious but not scary. Explain consequences plainly. "ستفقد جميع بياناتك وسيتم حذف حسابك. لا يمكن التراجع عن هذا الإجراء."

---

## Copy formulas by type

### Buttons and CTAs
- **Start with the verb.** Never a noun or preposition.
- **1–3 words.** If it needs more, the design needs rethinking.
- Use the imperative (فعل الأمر): "اشترك", "حمّل", "شاهد", "ابدأ", "شارك", "سجّل"
- Pair with context nouns only when ambiguity exists: "حذف البطاقة" not just "حذف" inside a card actions menu.
- Acknowledgment buttons use "تمام" (not "موافق" or "حسناً").
- Cancel is always "إلغاء". Back is always "الرجوع".

### Loading and processing states
- **Formula**: `جاري + مصدر + ...`
- Always three ASCII dots, never an ellipsis character (…).
- Examples: "جاري الارسال...", "جاري التحقق...", "جاري المعالجة..."
- For redirects, switch to: "سيتم تحويلك الآن..."

### Success messages
- **Formula**: `تم + مصدر` or `تمت + مصدر`
- Add "بنجاح" only for significant actions (payment, download), not routine ones (profile update).
- Examples: "تم تحديث الملف الشخصي", "تمت معالجة الدفع بنجاح"

### Error messages
Two patterns depending on severity:

1. **Action failure** (the user did something and it broke):
   `حدث خطأ أثناء + مصدر`
   Then optionally: `. حاول مرة أخرى.` or `. يرجى المحاولة مرة أخرى.`

2. **System failure** (something failed silently):
   `فشل في + مصدر`

- Use "حاول مرة أخرى" for casual retry prompts.
- Use "يرجى المحاولة مرة أخرى" for polite/formal retry prompts.
- Use "يرجى المحاولة مرة أخرى لاحقاً" only when the issue is likely temporary.
- For longer error descriptions, add the retry as a second sentence.
- Never blame the user. Never use "!" in errors.

### Validation messages
- **Formula**: `[الحقل] + [المشكلة]`
- Field-first, then the problem: "رقم البطاقة مطلوب", "البريد الإلكتروني غير صالح"
- Use "مطلوب" for required fields, "غير صحيح" for format errors, "غير صالح" for invalid values.
- For length constraints: "طويل جداً" / "قصير جداً"
- For format guidance: start with "يجب أن" — "يجب أن يحتوي على أرقام فقط"
- For user action needed: start with "يرجى" — "يرجى إدخال رقم هاتف صحيح", "يرجى اختيار طريقة الدفع"

### Empty states
- **Title**: short, declarative. "لم نجد نتائج", "لا توجد بيانات متاحة حالياً"
- **Description** (optional): a soft prompt or explanation. "اكتب في شريط البحث أعلاه للعثور على ما تبحث عنه"
- Use "لا توجد" / "لا يوجد" for absence. Use "لم نجد" / "لم نعثر" for search failures.
- Never end with a bare period when it's a title. Descriptions can end with periods.

### Confirmation dialogs
- **Title**: `متأكد من + مصدر + ؟` for standard confirmations. For high-stakes actions, use a full question: "هل ستقرر أن تحذف حسابك بلا رجعة؟"
- **Body**: state consequences plainly. Use "لا يمكن التراجع عن هذا الإجراء" for irreversible actions.
- **Cancel button**: "إلغاء" or "الرجوع" or a warm alternative like "إبقاء الحساب"
- **Confirm button**: repeat the specific action verb: "حذف البطاقة", "إلغاء الإشتراك", "حذف حسابي"

### Onboarding and conversational prompts
- Use "أيش" for questions, not "ما" or "ماذا": "أيش رقم جوّالك؟", "أيش تشجّع؟", "أيش البطولات المتاحة؟"
- Short, friendly, Saudi-flavored. Can break grammatical formality.
- "لا هنت" as a softener in OTP/verification contexts only: "أعد كتابته لا هنت", "واتبع التعليمات لا هنت"
- Never use "لا هنت" in buttons, errors, or settings — only in instructional/patience contexts.

### Network and connectivity
- Offline: "لا يوجد اتصال بالإنترنت"
- Restored: "تم استعادة الاتصال"
- Weak: "اتصال ضعيف"
- Connection error with action: "خطأ في الاتصال - يرجى التحقق من الإنترنت"

---

## Vocabulary rules

### Saudi-preferred terms
| Use | Instead of |
|---|---|
| جوّال | هاتف محمول، موبايل |
| قوقل | غوغل، جوجل |
| آبل | أبل (in auth/social contexts) |
| بريد إلكتروني | إيميل |
| بطاقة ائتمانية | كريديت كارد |
| رمز التفعيل / رمز التحقق | كود التفعيل |
| تمام | موافق، حسناً، أوكي |
| الرجوع | رجوع، عودة |

### English loanwords
- **Avoid** for common concepts: never "لوقن" for login, never "كانسل" for cancel.
- **Keep** for proper brand names: STC, Dolby, HDR, App Store, Play Store, Widevine, Tamara.
- **Keep** for technical terms without clean Arabic equivalents when used alongside Arabic: "Dolby 5.1", "HDR", "Full HD", "4k".
- Brand "ثمانية" is always in Arabic script, never transliterated to "Thmanyah" in user-facing copy.

### Guillemets «»
- Use Arabic guillemets to quote UI element names or actions referenced in explanatory text: «ريال», «حذف حسابي», «إلغاء الاشتراك».
- Never use regular quotes ("") or English quotes for this purpose in Arabic copy.

### Diacritics (تشكيل)
- Use sparingly, only for disambiguation or when the unvoweled form could be misread.
- Common cases: "حصريًّا", "مجانًا", "شهريًّا", "سنويًا", "غدًا"
- Tanween on adverbs (المفعول المطلق / الحال): always mark with ً.
- Do not over-vowel every word. Let context do the work.

### Decorative kashida (tatweel ـ)
- Used only in **display/marketing headings** for visual rhythm: "اشتـــراك ثمانيـــة", "الرئيسيــة", "كمبيوتــر", "تمـــارا"
- Never in body copy, error messages, labels, or buttons.
- When used, apply symmetrically within the word for visual balance.

---

## Punctuation rules

1. **Loading states** end with `...` (three ASCII dots). No other copy type ends with dots.
2. **Buttons and labels** never end with a period.
3. **Error messages** can end with a period when they contain a retry instruction as a second sentence.
4. **Arabic question mark** `؟` in FAQ questions and dialog titles. Some inline uses allow `?`.
5. **Commas**: use Western `,` (the codebase convention), not Arabic `،`.
6. **Guillemets** `«»` for quoting UI terms in explanatory text.
7. **No emoji** in UI copy. Exception: share templates only.
8. **Exclamation marks**: only for celebrations ("تم تسجيل الدخول بنجاح!", "قميصك جاهز!", "تمت عملية الشراء بنجاح!"). Never in errors.
9. **Newlines** `\n` in marketing/hero copy for visual line breaks. Never in short labels or buttons.

---

## Hard rules

These patterns are invariant. Never break them.

1. **Every loading state** is `جاري + مصدر + ...` — no exceptions, no variations.
2. **Every success message** starts with `تم` or `تمت` — never "نجحت العملية" or "تم بنجاح" alone.
3. **Every CTA** starts with a verb — never a noun, adjective, or preposition.
4. **"يرجى"** is reserved for polite error recovery and validation guidance. Never appears in CTAs or success messages.
5. **"أيش"** for conversational questions, never "ما" or "ماذا" in onboarding/dialog contexts.
6. **"لا هنت"** only in OTP/verification patience contexts. Nowhere else.
7. **Numbers** in copy are Western digits (0-9), never Eastern Arabic (٠-٩) — even though the app handles Eastern Arabic input.
8. **No emoji** in UI copy (buttons, errors, toasts, labels, dialogs, empty states).
9. **Validation messages** are `[field] + [problem]` — field first, always.
10. **Retry instructions** are a separate sentence, never jammed into the error description with a comma.

---

## Reference samples

See [references/samples.md](references/samples.md) for the full organized collection of real Arabic copy from this codebase, grouped by type. Always consult these before writing new copy to match existing patterns.

---

## How to use this skill

When asked to write Arabic UI copy for this project:

1. Identify the **copy type** (button, error, loading, empty state, confirmation, onboarding, validation, label, marketing).
2. Apply the **formula** for that type from the section above.
3. Check the **vocabulary rules** for term preferences.
4. Check **hard rules** for invariants.
5. Compare your draft against 2–3 real samples of the same type from `references/samples.md`.
6. If it reads differently from the samples, adjust until it doesn't.
