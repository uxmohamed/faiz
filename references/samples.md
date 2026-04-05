# Faiz — Arabic UX Copy Samples

Ground-truth examples extracted from the codebase. Organized by copy type.
When writing new copy, match the tone, length, and structure of these samples.

---

## Buttons and CTAs

Single-action labels. Always start with the verb. 1–3 words max.

| Arabic | Context |
|---|---|
| التالي | Step progression |
| تخطي | Skip optional step |
| إلغاء | Cancel action |
| حفظ | Save |
| حذف | Delete |
| تعديل | Edit |
| إغلاق | Close |
| تأكيد | Confirm |
| الرجوع | Go back |
| اشترك الآن | Subscribe CTA |
| اشترك مقابل {price} | Subscribe with price |
| ابدأ تجربة مجانية لمدة 7 أيام | Free trial CTA |
| حمّل | Download |
| حمّل التطبيق | Download app |
| شارك | Share |
| شاهد الان | Watch now |
| ابدأ | Start |
| سجّل برقم جوّالك | Register with phone |
| سجّل بحسابك في ثمانية | Register with Thmanyah account |
| إعادة المحاولة | Retry |
| إعادة الارسال | Resend |
| حفظ التغييرات | Save changes |
| حذف حسابي | Delete my account |
| إبقاء الحساب | Keep account |
| حذف البطاقة | Delete card |
| إضافة بطاقة | Add card |
| إضافة البطاقة | Add the card |
| تفعيل الاشتراك | Activate subscription |
| إلغاء الاشتراك | Cancel subscription |
| محاولة الدفع مرة أخرى | Retry payment |
| تأكيد الرمز | Confirm code |
| حفظ الجهاز | Save device |
| إضافة جهاز | Add device |
| تغيير النادي المفضل | Change favorite club |
| تغيير خطة الاشتراك | Change subscription plan |
| الترقيـة للخطة السنويــة | Upgrade to yearly plan |
| غيّر إلى الاشتراك الشهري | Switch to monthly |
| تمام | Acknowledge / OK |
| نعم، هذا هو حسابي | Confirm identity |
| هذا ليس حسابي | Deny identity |
| عُد إلى الصفحة الرئيسية | Return to home |
| اشترك من جديد برقم آخر | Re-subscribe with different number |
| نساعدك؟ | Help CTA |
| عندك سؤال؟ اسألنا. | FAQ prompt |
| شاهد على تطبيق ثمانيـــة | Watch on Thmanyah app |

---

## Loading and processing states

Always follows the pattern: **جاري + مصدر + ...**

| Arabic | Context |
|---|---|
| جاري الارسال... | Sending OTP / form |
| جاري التحقق... | Verifying OTP / identity |
| جاري الحفظ... | Saving profile / device |
| جاري المعالجة... | Processing payment |
| جاري الحذف... | Deleting card |
| جاري التعيين... | Setting default card |
| جاري الإضافة... | Adding card |
| جاري التحديث... | Updating subscription |
| جاري الاسترجاع... | Recovering account |
| جاري التحميل... | Loading content |
| جاري تحميل المزيد... | Loading more (infinite scroll) |
| جار تهيئة الجهاز... | Initializing device |
| سيتم تحويلك الآن... | Redirecting |
| سيتم تحويلك لصفحة الدفع... | Redirecting to payment |

---

## Success messages

Always starts with **تم + مصدر** or **تمت + مصدر**.

| Arabic | Context |
|---|---|
| تم تسجيل الدخول بنجاح! | Login success |
| تم تحديث الملف الشخصي | Profile updated |
| تم إرسال رمز التحقق إلى بريدك الإلكتروني | OTP sent to email |
| تم إرسال رمز التحقق إلى رقم هاتفك | OTP sent to phone |
| تم إرسال رمز التحقق مرة أخرى | OTP resent |
| تم إضافة البطاقة بنجاح | Card added |
| تم تعيين البطاقة كافتراضية | Card set as default |
| تم حذف البطاقة | Card deleted |
| تم تحميل الصورة بنجاح! | Image downloaded |
| تمت معالجة الدفع بنجاح | Payment processed |
| تمت عملية الشراء بنجاح! | Purchase complete |
| تم الترقية إلى الباقة السنوية بنجاح | Upgraded to yearly |
| تم التغيير إلى الباقة الشهرية بنجاح | Downgraded to monthly |
| تم إعادة إرسال رمز التحقق | Verification code resent |
| تم استعادة الاتصال | Connection restored |

---

## Error and validation messages

### Generic errors

Pattern: **حدث خطأ أثناء [المصدر]** or **فشل في [المصدر]**

| Arabic | Context |
|---|---|
| حدث خطأ | Generic error (short) |
| حدث خطأ ما | Generic error |
| حدث خطأ غير متوقع | Unexpected error |
| حدث خطأ غير متوقع. حاول مرة أخرى. | Unexpected + retry |
| حدث خطأ غير متوقع، يرجى المحاولة مرة أخرى | Unexpected + polite retry |
| حدث خطأ ما. يرجى المحاولة مرة أخرى لاحقاً | Generic + later retry |
| حدث خطأ أثناء تسجيل الدخول | Login error |
| حدث خطأ أثناء إرسال رمز التحقق. حاول مرة أخرى. | OTP send error |
| حدث خطأ أثناء التحقق من الرمز. يرجى المحاولة مرة أخرى. | OTP verify error |
| حدث خطأ أثناء تحديث الملف الشخصي | Profile update error |
| حدث خطأ أثناء تحميل الأندية | Club loading error |
| حدث خطأ أثناء تحميل الصورة | Image download error |
| حدث خطأ أثناء إنشاء الصورة | Image creation error |
| حدث خطأ أثناء إتمام الدفع | Payment completion error |
| حدث خطأ أثناء إتمام عملية الشراء | Purchase error |
| حدث خطأ أثناء التحميل | Loading error |
| حدث خطأ أثناء إرسال البريد. يرجى المحاولة مرة أخرى. | Email send error |
| حدث خطأ أثناء إرسال الرسالة. يرجى المحاولة مرة أخرى. | SMS send error |
| حدث خطأ أثناء إعادة الإرسال. يرجى المحاولة مرة أخرى. | Resend error |
| حدث خطأ أثناء التحقق. يرجى المحاولة مرة أخرى. | Verification error |
| حدث خطأ اثناء التشغيل | Playback error |
| فشل في الدفع | Payment failed |
| فشل في معالجة البطاقة | Card processing failed |
| فشل في إتمام الدفع | Payment completion failed |
| فشل في تعيين البطاقة كافتراضية | Set default card failed |
| فشل في حذف البطاقة | Delete card failed |
| فشل في تحديث قائمة البطاقات | Refresh cards failed |
| فشل في إرسال رمز التحقق | Send OTP failed |
| فشل في إعادة إرسال الرمز | Resend OTP failed |
| فشل في التحقق من رقم الجوال | Phone lookup failed |
| فشل في تغيير الباقة | Plan change failed |
| فشل في تهيئة معلومات الجهاز | Device init failed |
| فشل في تحميل المزيد من البيانات | Load more failed |
| فشل الدفع | Payment failed (short) |
| عملية الدفع فشلت، حاول مرة أخرى | Payment failed + retry |

### Auth-specific errors

| Arabic | Context |
|---|---|
| رمز التفعيل غير صحيح، أعد كتابته لا هنت | Wrong OTP (colloquial) |
| انتهت صلاحية هذا الرمز، أرسل آخرًا لا هنت | Expired OTP (colloquial) |
| هذا البريد الإلكتروني مستخدم بالفعل | Email taken |
| هذا الرقم مستخدم بالفعل. يرجى تجربة رقم آخر | Phone taken |
| حسابك مسجل الدخول على جهاز آخر | Logged in elsewhere |
| هذا الحساب غير موجود | Account not found |
| تجاوزت حد المحاولات، حاول مجددًا بعد 15 دقيقة | Rate limited |
| لقد سجلت الدخول على أجهزة كثيرة جداً | Too many devices |
| لا يوجد جلسة تسجيل الدخول | No session |

### Social auth errors

| Arabic | Context |
|---|---|
| تسجيل الدخول بقوقل غير متاح حالياً. يرجى تحديث الصفحة والمحاولة مرة أخرى | Google unavailable |
| تسجيل الدخول بآبل غير متاح حالياً. يرجى تحديث الصفحة والمحاولة مرة أخرى | Apple unavailable |
| تم إلغاء تسجيل الدخول بقوقل. يرجى المحاولة مرة أخرى | Google cancelled |
| تم إلغاء تسجيل الدخول بآبل. يرجى المحاولة مرة أخرى | Apple cancelled |
| فشل تسجيل الدخول بقوقل. يرجى المحاولة مرة أخرى أو استخدام طريقة أخرى | Google failed |
| فشل تسجيل الدخول بآبل. يرجى المحاولة مرة أخرى أو استخدام طريقة أخرى | Apple failed |

### Validation messages

Pattern: **[الحقل] + [المشكلة]**

| Arabic | Context |
|---|---|
| رقم الهاتف مطلوب | Phone required |
| يرجى إدخال رقم هاتف صحيح | Invalid phone |
| البريد الإلكتروني غير صالح | Invalid email |
| رقم البطاقة مطلوب | Card number required |
| رقم البطاقة قصير جداً | Card number too short |
| رقم البطاقة طويل جداً | Card number too long |
| رقم البطاقة غير صحيح | Card number invalid |
| يجب أن يحتوي على أرقام فقط | Digits only |
| تاريخ الانتهاء مطلوب | Expiry required |
| صيغة التاريخ غير صحيحة (MM/YY) | Invalid date format |
| البطاقة منتهية الصلاحية | Card expired |
| رمز الأمان مطلوب | CVC required |
| رمز الأمان غير صالح | CVC invalid |
| اسم حامل البطاقة مطلوب | Cardholder name required |
| يجب أن يحتوي الاسم على كلمتين على الأقل | Name needs two words |
| الاسم الأول مطلوب | First name required |
| الاسم الأول طويل جدا | First name too long |
| اسم العائلة مطلوب | Last name required |
| الرمز يجب أن يكون 6 أرقام | OTP must be 6 digits |
| يرجى اختيار نوع الجهاز | Select device type |
| يرجى إدخال اسم الجهاز | Enter device name |
| اسم الجهاز طويل جداً | Device name too long |
| يرجى اختيار فريق واسم للقميص | Select team and jersey name |
| يرجى اختيار طريقة الدفع | Select payment method |
| يرجى التحقق من بيانات البطاقة | Check card data |

### Network errors

| Arabic | Context |
|---|---|
| خطأ في الاتصال | Connection error (short) |
| خطأ في الاتصال - يرجى التحقق من الإنترنت | Connection + check internet |
| لا يوجد اتصال بالإنترنت | Offline |
| اتصال ضعيف | Poor connection |

---

## Empty states and no-data

| Arabic | Context |
|---|---|
| لا توجد بيانات متاحة حالياً | No data available |
| لم نجد نتائج | No results found |
| لم نعثر على نتائج تطابق "{query}" | No results for query |
| لم يتم العثور على نتائج. | No country results |
| الصفحة التي تبحث عنها غير موجودة. | 404 page |
| المعذرة هذا المحتوى ليس متوفرًا قي موقعك الجغرافي | Geo-blocked |
| البث المباشر غير متوفر على المتصفح في الجوال. | Live not on mobile browser |

---

## Confirmation dialogs

Title pattern: **متأكد من [الفعل]؟**

### Delete card
- **Title**: متأكد من حذف البطاقة؟
- **Body**: هل أنت متأكد من حذف هذه البطاقة؟ لا يمكن التراجع عن هذا الإجراء.
- **Cancel**: إلغاء
- **Confirm**: حذف البطاقة

### Cancel subscription
- **Title**: متأكد من إلغاء الاشتراك؟
- **Body**: ستفقد وصولك اللا محدود لمحتوى ثمانية، وكافة الميزات الحصرية في تطبيق ثمانية وتطبيق راديو ثمانية.
- **Cancel**: الرجوع
- **Confirm**: إلغاء الإشتراك

### Delete account
- **Title**: هل ستقرر أن تحذف حسابك بلا رجعة؟
- **Body**: هذا الإجراء، في حال استكملته، سيؤدي إلى حذف بياناتك الشخصية، وكل ما تابعاته أو فضّلته أو حمّلته، وسيمحو كل تعليقاتك وإعجاباتك...
- **Cancel**: إبقاء الحساب
- **Confirm**: حذف حسابي

### Already subscribed
- **Title**: أنت مشترك بالفعل!
- **Body**: لديك اشتراك سابق على هذا الحساب، وكل المزايا الحصرية على تطبيق وموقع ثمانية وتطبيق راديو ثمانية متاحة لك. استمتع!
- **Button**: تمام

### Pending plan change
- **Title**: لا يمكنك تغيير اشتراكك الآن
- **Button**: تمام

---

## Onboarding and conversational prompts

| Arabic | Context |
|---|---|
| أيش رقم جوّالك؟ | Phone input title |
| أيش تشجّع؟ | Club selection |
| اسم الكريم؟ | Name input |
| شاركنا بريدك المفضّل | Email input (general) |
| أيش بريدك المسجّل في ثمانية؟ | Email input (Thmanyah) |
| قميصك جاهز! | Jersey confirmation |
| ركلة البداية،\nلتجربة بلا مثيل! | Method selection hero |
| الدوري السعودي وجميع بطولات الكرة السعودية\nحصريًا، وبجودة بث غير مسبوقة. | Method selection subtitle |
| سجل دخولك | Login title |
| سجّـل دخولك أو أنشئ حساب جديد | Auth step title |
| أرسلنا رمز التفعيل إلى رقمك: | OTP sent to phone |
| أرسلنا رمز التحقق إلى بريدك: | OTP sent to email |
| صلاحية رمز التفعيل: | OTP validity label |
| هل هذا حسابك؟ | Account mismatch |
| بإنشائك الحساب فإنك توافق على | Terms consent |
| اكتب الرمز الظاهر على شاشة التلفاز لربط هذا الجهاز بالشاشة، واتبع التعليمات لا هنت | Device pairing |
| نحتاج إلى التحقق من هويتك لنؤكد حذف حسابك | Delete verification |
| أسمح بأن تصلني رسائل تسويقية من ثمانية | Marketing consent |

---

## Labels and navigation

| Arabic | Context |
|---|---|
| الرئيسيــة | Home nav |
| رياضــة | Sports nav |
| برامج | Programs nav |
| مقالات | Articles nav |
| الإعدادات | Settings |
| إدارة الملف الشخصي | Profile management |
| إدارة الاشتراكات | Subscription management |
| العودة للرئيسية | Back to home |
| وسيلة الدفع | Payment method |
| سجل المدفوعات | Payment history |
| الأجهزة المتصلة | Connected devices |
| ابحث... | Search placeholder |
| ابدأ البحث | Start search |
| للمشتركين فقط | Subscribers only |
| مباشر | Live badge |
| قادمة | Upcoming badge |
| منتهي | Ended badge |
| نهاية البث | Broadcast ended |
| نهاية المباراة | Match ended |
| الشوط الأول | First half |
| الشوط الثاني | Second half |
| الوقت الإضافي | Extra time |
| العودة للبث المباشر | Return to live |

---

## Marketing and long-form (select examples)

### Subscription description
> تابع أقوى البطولات المحلية بالإضافة إلى أعمال ثمانية الحصرية والبث المباشر.

### Hero
> التجربة الأمثل لمتابعة\nالكرة السعوديـة!

### Benefits
> أقصى جودة مشاهدة،\n بـ 50 إطار في الثانية

### FAQ style
> Q: كيف أستفيد من التجربة المجانية لاشتراك ثمانية؟
> A: كل المشتركين الجدد مؤهلين لتجربة مزايا اشتراك ثمانية مجانًا لمدة 14 يوم. التجربة المجانية تتطلب منك فقط تسجيل الدخول، وإدخال بيانات طريقة الدفع...

### Provider-managed subscription
> أنت مشترك عن طريق متجر تطبيقات أبل. لتتمكن من إدارة اشتراكك، توجه إلى صفحة الاشتراكات في متجر التطبيقات App Store / Play Store. ولو احتجت أي مساعدة، راسلنا على ask@thmanyah.com.

### Metadata
> حصريًّا على ثمانية شاهد دوري روشن السعودي وكأس السوبر السعودي وكأس الملك ودوري يلو مجانًا، مع مكتبة متنوعة من برامج البودكاست والوثائقيات في كافة الاهتمامات.
