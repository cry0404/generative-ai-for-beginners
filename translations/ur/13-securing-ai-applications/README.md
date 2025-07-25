<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "f3cac698e9eea47dd563633bd82daf8c",
  "translation_date": "2025-07-09T15:13:13+00:00",
  "source_file": "13-securing-ai-applications/README.md",
  "language_code": "ur"
}
-->
# آپ کی جنریٹو AI ایپلیکیشنز کی حفاظت

[![آپ کی جنریٹو AI ایپلیکیشنز کی حفاظت](../../../translated_images/13-lesson-banner.14103e36b4bbf17398b64ed2b0531f6f2c6549e7f7342f797c40bcae5a11862e.ur.png)](https://aka.ms/gen-ai-lesson13-gh?WT.mc_id=academic-105485-koreyst)

## تعارف

اس سبق میں شامل ہیں:

- AI سسٹمز کے تناظر میں سیکیورٹی۔
- AI سسٹمز کے عام خطرات اور خطرات۔
- AI سسٹمز کی حفاظت کے طریقے اور غور و فکر۔

## سیکھنے کے مقاصد

اس سبق کو مکمل کرنے کے بعد، آپ کو سمجھ حاصل ہوگی:

- AI سسٹمز کو لاحق خطرات اور خطرات۔
- AI سسٹمز کی حفاظت کے عام طریقے اور عملی اقدامات۔
- سیکیورٹی ٹیسٹنگ کے نفاذ سے غیر متوقع نتائج اور صارف کے اعتماد کے زوال کو کیسے روکا جا سکتا ہے۔

## جنریٹو AI کے تناظر میں سیکیورٹی کا کیا مطلب ہے؟

چونکہ مصنوعی ذہانت (AI) اور مشین لرننگ (ML) ٹیکنالوجیز ہماری زندگیوں کو بڑھتی ہوئی حد تک تشکیل دے رہی ہیں، اس لیے نہ صرف صارف کے ڈیٹا بلکہ خود AI سسٹمز کی حفاظت بھی ضروری ہے۔ AI/ML کو ان صنعتوں میں اعلیٰ قدر کے فیصلوں کی حمایت کے لیے بڑھتی ہوئی حد تک استعمال کیا جا رہا ہے جہاں غلط فیصلہ سنگین نتائج کا باعث بن سکتا ہے۔

یہاں چند اہم نکات ہیں جن پر غور کرنا چاہیے:

- **AI/ML کا اثر**: AI/ML روزمرہ زندگی پر گہرا اثر رکھتے ہیں اور اسی لیے ان کی حفاظت ضروری ہو گئی ہے۔
- **سیکیورٹی کے چیلنجز**: AI/ML کے اس اثر کو مناسب توجہ کی ضرورت ہے تاکہ AI پر مبنی مصنوعات کو ماہر حملوں سے محفوظ رکھا جا سکے، چاہے وہ ٹرولز ہوں یا منظم گروہ۔
- **حکمت عملی کے مسائل**: ٹیکنالوجی کی صنعت کو طویل مدتی صارف کی حفاظت اور ڈیٹا کی سیکیورٹی کو یقینی بنانے کے لیے حکمت عملی کے چیلنجز کو فعال طور پر حل کرنا چاہیے۔

مزید برآں، مشین لرننگ ماڈلز عام طور پر نقصان دہ ان پٹ اور معمولی غیر معمولی ڈیٹا میں فرق کرنے سے قاصر ہوتے ہیں۔ تربیتی ڈیٹا کا ایک بڑا حصہ غیر منظم، غیر معتدل، عوامی ڈیٹا سیٹس سے حاصل ہوتا ہے، جو تیسرے فریق کی شراکت کے لیے کھلے ہوتے ہیں۔ حملہ آوروں کو ڈیٹا سیٹس کو نقصان پہنچانے کی ضرورت نہیں جب وہ ان میں حصہ ڈال سکتے ہیں۔ وقت کے ساتھ، کم اعتماد والا نقصان دہ ڈیٹا اعلیٰ اعتماد والا قابلِ اعتماد ڈیٹا بن جاتا ہے، اگر ڈیٹا کی ساخت/فارمیٹنگ درست رہے۔

اسی لیے یہ بہت ضروری ہے کہ آپ اپنے ماڈلز کے فیصلے کرنے کے لیے استعمال ہونے والے ڈیٹا اسٹورز کی سالمیت اور حفاظت کو یقینی بنائیں۔

## AI کے خطرات اور خطرات کو سمجھنا

AI اور متعلقہ سسٹمز کے حوالے سے، ڈیٹا پوائزننگ آج کا سب سے بڑا سیکیورٹی خطرہ ہے۔ ڈیٹا پوائزننگ اس وقت ہوتی ہے جب کوئی شخص جان بوجھ کر AI کی تربیت کے لیے استعمال ہونے والی معلومات کو تبدیل کرتا ہے، جس سے AI غلطیاں کرتا ہے۔ یہ اس لیے ہے کیونکہ معیاری شناخت اور تخفیف کے طریقے موجود نہیں ہیں، اور ہم تربیت کے لیے غیر معتبر یا غیر منظم عوامی ڈیٹا سیٹس پر انحصار کرتے ہیں۔ ڈیٹا کی سالمیت کو برقرار رکھنے اور تربیتی عمل کو خراب ہونے سے روکنے کے لیے، اپنے ڈیٹا کی اصل اور سلسلہ وار تاریخ کو ٹریک کرنا ضروری ہے۔ ورنہ، پرانا محاورہ "گندگی اندر، گندگی باہر" درست ثابت ہوتا ہے، جس سے ماڈل کی کارکردگی متاثر ہوتی ہے۔

یہاں کچھ مثالیں ہیں کہ ڈیٹا پوائزننگ آپ کے ماڈلز کو کیسے متاثر کر سکتی ہے:

1. **لیبل فلپنگ**: بائنری درجہ بندی کے کام میں، ایک مخالف چھوٹے تربیتی ڈیٹا کے حصے کے لیبلز جان بوجھ کر تبدیل کر دیتا ہے۔ مثال کے طور پر، معمولی نمونوں کو نقصان دہ کے طور پر لیبل کیا جاتا ہے، جس سے ماڈل غلط تعلقات سیکھتا ہے۔\
   **مثال**: ایک اسپیم فلٹر جائز ای میلز کو اسپیم کے طور پر غلط شناخت کرتا ہے کیونکہ لیبلز میں چالاکی کی گئی ہے۔
2. **فیچر پوائزننگ**: ایک حملہ آور تربیتی ڈیٹا میں فیچرز کو معمولی طور پر تبدیل کرتا ہے تاکہ تعصب پیدا کرے یا ماڈل کو گمراہ کرے۔\
   **مثال**: مصنوعات کی تفصیلات میں غیر متعلقہ کلیدی الفاظ شامل کرنا تاکہ سفارشاتی نظام کو متاثر کیا جا سکے۔
3. **ڈیٹا انجیکشن**: تربیتی سیٹ میں نقصان دہ ڈیٹا داخل کرنا تاکہ ماڈل کے رویے کو متاثر کیا جا سکے۔\
   **مثال**: جعلی صارف کے جائزے شامل کرنا تاکہ جذباتی تجزیے کے نتائج کو بگاڑا جا سکے۔
4. **بیک ڈور حملے**: ایک مخالف تربیتی ڈیٹا میں ایک پوشیدہ پیٹرن (بیک ڈور) داخل کرتا ہے۔ ماڈل اس پیٹرن کو پہچاننا سیکھتا ہے اور جب یہ فعال ہوتا ہے تو نقصان دہ رویہ اختیار کرتا ہے۔\
   **مثال**: چہرہ شناختی نظام جو بیک ڈور والی تصاویر سے تربیت یافتہ ہو اور مخصوص شخص کو غلط شناخت کرے۔

MITRE Corporation نے [ATLAS (Adversarial Threat Landscape for Artificial-Intelligence Systems)](https://atlas.mitre.org/?WT.mc_id=academic-105485-koreyst) تیار کیا ہے، جو AI سسٹمز پر حقیقی دنیا کے حملوں میں مخالفین کی حکمت عملیوں اور تکنیکوں کا ایک علم کا ذخیرہ ہے۔

> AI سے لیس سسٹمز میں کمزوریوں کی تعداد بڑھ رہی ہے، کیونکہ AI کے شامل ہونے سے موجودہ سسٹمز کی حملے کی سطح روایتی سائبر حملوں سے بڑھ جاتی ہے۔ ہم نے ATLAS تیار کیا ہے تاکہ ان منفرد اور بدلتی ہوئی کمزوریوں کے بارے میں آگاہی بڑھائی جا سکے، کیونکہ عالمی برادری مختلف سسٹمز میں AI کو بڑھتی ہوئی حد تک شامل کر رہی ہے۔ ATLAS کو MITRE ATT&CK® فریم ورک کی طرز پر ماڈل کیا گیا ہے اور اس کی حکمت عملی، تکنیکیں، اور طریقہ کار (TTPs) ATT&CK میں موجود طریقوں کے ساتھ تکمیلی ہیں۔

جیسے MITRE ATT&CK® فریم ورک روایتی سائبر سیکیورٹی میں جدید خطرات کی نقل کے منصوبہ بندی کے لیے وسیع پیمانے پر استعمال ہوتا ہے، ATLAS ایک آسانی سے تلاش ہونے والا TTPs کا مجموعہ فراہم کرتا ہے جو ابھرتے ہوئے حملوں کے خلاف دفاع کی بہتر سمجھ اور تیاری میں مدد دیتا ہے۔

مزید برآں، Open Web Application Security Project (OWASP) نے LLMs استعمال کرنے والی ایپلیکیشنز میں پائی جانے والی سب سے اہم کمزوریوں کی "[Top 10 list](https://llmtop10.com/?WT.mc_id=academic-105485-koreyst)" تیار کی ہے۔ اس فہرست میں مذکورہ بالا ڈیٹا پوائزننگ کے خطرات کے علاوہ درج ذیل خطرات کو بھی اجاگر کیا گیا ہے:

- **Prompt Injection**: ایک تکنیک جس میں حملہ آور Large Language Model (LLM) کو باریک بینی سے تیار کردہ ان پٹ کے ذریعے قابو پاتے ہیں، جس سے ماڈل اپنی متوقع کارکردگی سے ہٹ کر کام کرتا ہے۔
- **سپلائی چین کی کمزوریاں**: وہ اجزاء اور سافٹ ویئر جو LLM کی ایپلیکیشنز میں استعمال ہوتے ہیں، جیسے Python ماڈیولز یا بیرونی ڈیٹا سیٹس، خود بھی متاثر ہو سکتے ہیں جس سے غیر متوقع نتائج، تعصبات، اور بنیادی انفراسٹرکچر میں کمزوریاں پیدا ہو سکتی ہیں۔
- **زیادہ انحصار**: LLMs غلطی کر سکتے ہیں اور اکثر "ہیلوسینیٹ" کرتے ہیں، یعنی غلط یا غیر محفوظ نتائج فراہم کرتے ہیں۔ کئی دستاویزی حالات میں، لوگوں نے ان نتائج کو بلا سوال قبول کیا جس کے باعث غیر متوقع منفی نتائج سامنے آئے۔

Microsoft Cloud Advocate Rod Trent نے ایک مفت ای بک [Must Learn AI Security](https://github.com/rod-trent/OpenAISecurity/tree/main/Must_Learn/Book_Version?WT.mc_id=academic-105485-koreyst) لکھی ہے، جو ان اور دیگر ابھرتے ہوئے AI خطرات میں گہرائی سے غوطہ لگاتی ہے اور ان حالات سے نمٹنے کے لیے وسیع رہنمائی فراہم کرتی ہے۔

## AI سسٹمز اور LLMs کے لیے سیکیورٹی ٹیسٹنگ

مصنوعی ذہانت (AI) مختلف شعبوں اور صنعتوں کو تبدیل کر رہی ہے، معاشرے کے لیے نئی ممکنات اور فوائد پیش کر رہی ہے۔ تاہم، AI کے ساتھ اہم چیلنجز اور خطرات بھی ہیں، جیسے ڈیٹا کی پرائیویسی، تعصب، وضاحت کی کمی، اور ممکنہ غلط استعمال۔ اس لیے یہ ضروری ہے کہ AI سسٹمز محفوظ اور ذمہ دار ہوں، یعنی وہ اخلاقی اور قانونی معیارات کی پابندی کریں اور صارفین اور اسٹیک ہولڈرز کے لیے قابل اعتماد ہوں۔

سیکیورٹی ٹیسٹنگ AI سسٹم یا LLM کی سیکیورٹی کا جائزہ لینے کا عمل ہے، جس میں ان کی کمزوریوں کی شناخت اور استحصال شامل ہے۔ یہ کام ڈویلپرز، صارفین، یا تیسرے فریق کے آڈیٹرز کر سکتے ہیں، ٹیسٹنگ کے مقصد اور دائرہ کار کے مطابق۔ AI سسٹمز اور LLMs کے لیے سب سے عام سیکیورٹی ٹیسٹنگ کے طریقے درج ذیل ہیں:

- **ڈیٹا کی صفائی**: یہ عمل تربیتی ڈیٹا یا AI سسٹم یا LLM کے ان پٹ سے حساس یا نجی معلومات کو ہٹانے یا گمنام بنانے کا ہے۔ ڈیٹا کی صفائی ڈیٹا لیکیج اور نقصان دہ تبدیلیوں کو روکنے میں مدد دیتی ہے کیونکہ یہ خفیہ یا ذاتی ڈیٹا کے انکشاف کو کم کرتی ہے۔
- **مخالفانہ ٹیسٹنگ**: یہ عمل AI سسٹم یا LLM کے ان پٹ یا آؤٹ پٹ پر مخالفانہ مثالیں پیدا کرنے اور لاگو کرنے کا ہے تاکہ اس کی مضبوطی اور مزاحمت کو جانچا جا سکے۔ مخالفانہ ٹیسٹنگ AI سسٹم یا LLM کی کمزوریوں اور خامیوں کی نشاندہی اور تخفیف میں مدد دیتی ہے جو حملہ آور استحصال کر سکتے ہیں۔
- **ماڈل کی تصدیق**: یہ عمل AI سسٹم یا LLM کے ماڈل پیرامیٹرز یا فن تعمیر کی درستگی اور مکمل ہونے کی تصدیق کا ہے۔ ماڈل کی تصدیق ماڈل کی حفاظت اور تصدیق کو یقینی بنا کر ماڈل چوری کو روکنے میں مدد دیتی ہے۔
- **آؤٹ پٹ کی توثیق**: یہ عمل AI سسٹم یا LLM کے آؤٹ پٹ کے معیار اور قابلِ اعتماد ہونے کی جانچ کا ہے۔ آؤٹ پٹ کی توثیق نقصان دہ تبدیلیوں کی نشاندہی اور اصلاح میں مدد دیتی ہے تاکہ آؤٹ پٹ مستقل اور درست ہو۔

OpenAI، جو AI سسٹمز میں ایک رہنما ہے، نے اپنی ریڈ ٹیمنگ نیٹ ورک انیشیٹو کے تحت _سیفٹی ایویلیوایشنز_ کا ایک سلسلہ قائم کیا ہے، جس کا مقصد AI سسٹمز کے آؤٹ پٹ کی جانچ کرنا اور AI کی حفاظت میں تعاون کرنا ہے۔

> ایویلیوایشنز سادہ سوال و جواب کے ٹیسٹ سے لے کر پیچیدہ سمولیشنز تک ہو سکتی ہیں۔ یہاں OpenAI کی جانب سے AI رویوں کی مختلف زاویوں سے جانچ کے لیے تیار کردہ چند نمونہ ایویلیوایشنز دی گئی ہیں:

#### قائل کرنا

- [MakeMeSay](https://github.com/openai/evals/tree/main/evals/elsuite/make_me_say/readme.md?WT.mc_id=academic-105485-koreyst): ایک AI سسٹم دوسرے AI سسٹم کو خفیہ لفظ کہنے پر کتنا مؤثر طریقے سے قائل کر سکتا ہے؟
- [MakeMePay](https://github.com/openai/evals/tree/main/evals/elsuite/make_me_pay/readme.md?WT.mc_id=academic-105485-koreyst): ایک AI سسٹم دوسرے AI سسٹم کو پیسے دینے پر کتنا قائل کر سکتا ہے؟
- [Ballot Proposal](https://github.com/openai/evals/tree/main/evals/elsuite/ballots/readme.md?WT.mc_id=academic-105485-koreyst): ایک AI سسٹم دوسرے AI سسٹم کی سیاسی تجویز کی حمایت پر کتنا اثر انداز ہو سکتا ہے؟

#### سٹیگانوگرافی (چھپی ہوئی پیغام رسانی)

- [Steganography](https://github.com/openai/evals/tree/main/evals/elsuite/steganography/readme.md?WT.mc_id=academic-105485-koreyst): ایک AI سسٹم دوسرے AI سسٹم کو پکڑے بغیر خفیہ پیغامات کتنی اچھی طرح بھیج سکتا ہے؟
- [Text Compression](https://github.com/openai/evals/tree/main/evals/elsuite/text_compression/readme.md?WT.mc_id=academic-105485-koreyst): ایک AI سسٹم پیغامات کو کمپریس اور ڈی کمپریس کتنی مؤثر طریقے سے کر سکتا ہے تاکہ خفیہ پیغامات چھپائے جا سکیں؟
- [Schelling Point](https://github.com/openai/evals/blob/main/evals/elsuite/schelling_point/README.md?WT.mc_id=academic-105485-koreyst): ایک AI سسٹم دوسرے AI سسٹم کے ساتھ بغیر براہِ راست رابطے کے کتنی اچھی ہم آہنگی کر سکتا ہے؟

### AI سیکیورٹی

یہ ضروری ہے کہ ہم AI سسٹمز کو نقصان دہ حملوں، غلط استعمال، یا غیر ارادی نتائج سے بچانے کی کوشش کریں۔ اس میں AI سسٹمز کی حفاظت، قابلِ اعتماد، اور اعتماد کے قابل بنانے کے اقدامات شامل ہیں، جیسے:

- AI ماڈلز کی تربیت اور چلانے کے لیے استعمال ہونے والے ڈیٹا اور الگورتھمز کی حفاظت
- AI سسٹمز تک غیر مجاز رسائی، تبدیلی، یا تخریب کاری کو روکنا
- AI سسٹمز میں تعصب، امتیاز، یا اخلاقی مسائل کی شناخت اور تخفیف
- AI کے فیصلوں اور اقدامات کی جوابدہی، شفافیت، اور وضاحت کو یقینی بنانا
- AI سسٹمز کے مقاصد اور اقدار کو انسانوں اور معاشرے کے ساتھ ہم آہنگ کرنا

AI سیکیورٹی AI سسٹمز اور ڈیٹا کی سالمیت، دستیابی، اور رازداری کو یقینی بنانے کے لیے اہم ہے۔ AI سیکیورٹی کے کچھ چیلنجز اور مواقع یہ ہیں:

- موقع: سائبر سیکیورٹی حکمت عملیوں میں AI کو شامل کرنا کیونکہ یہ خطرات کی شناخت اور ردعمل کے اوقات کو بہتر بنانے میں اہم کردار ادا کر سکتا ہے۔ AI سائبر حملوں جیسے فشنگ، مالویئر، یا رینسم ویئر کی شناخت اور تخفیف کو خودکار اور بڑھا سکتا ہے۔
- چیلنج: AI کو مخالفین بھی پیچیدہ حملے کرنے کے لیے استعمال کر سکتے ہیں، جیسے جعلی یا گمراہ کن مواد تیار کرنا، صارفین کی نقل کرنا، یا AI سسٹمز کی کمزوریوں کا استحصال کرنا۔ اس لیے AI ڈویلپرز پر یہ ذمہ داری عائد ہوتی ہے کہ وہ ایسے سسٹمز ڈیزائن کریں جو غلط استعمال کے خلاف مضبوط اور مزاحم ہوں۔

### ڈیٹا کی حفاظت

LLMs اس ڈیٹا کی پرائیویسی اور سیکیورٹی کے لیے خطرات پیدا کر سکتے ہیں جو وہ استعمال کرتے ہیں۔ مثال کے طور پر، LLMs ممکنہ طور پر اپنے تربیتی ڈیٹا سے حساس معلومات یاد رکھ سکتے ہیں اور لیک کر سکتے ہیں، جیسے ذاتی نام، پتے، پاس ورڈز، یا کریڈٹ کارڈ نمبر۔ انہیں نقصان دہ عناصر بھی قابو پا سکتے ہیں جو ان کی کمزوریوں یا تعصبات کا فائدہ اٹھانا چاہتے ہیں۔ اس لیے ان خطرات سے آگاہ ہونا اور LLMs کے ساتھ استعمال ہونے والے ڈیٹا کی حفاظت کے لیے مناسب اقدامات کرنا ضروری ہے۔ آپ LLMs کے ساتھ استعمال ہونے والے ڈیٹا کی حفاظت کے لیے درج ذیل اقدامات کر سکتے ہیں:

- **LLMs کے ساتھ شیئر کیے جانے والے ڈیٹا کی مقدار اور قسم کو محدود کرنا**: صرف وہی ڈیٹا شیئر کریں جو ضروری اور متعلقہ ہو، اور حساس، خفیہ، یا ذاتی ڈیٹا شیئر کرنے سے گریز کریں۔ صارفین کو چاہیے کہ وہ LLMs کے ساتھ شیئر کیے جانے والے ڈیٹا کو گمنام یا انکرپٹ کریں، جیسے شناختی معلومات کو ہٹانا یا چھپانا، یا محفوظ مواصلاتی چینلز استعمال کرنا۔
- **LLMs کے تیار کردہ ڈیٹا کی تصدیق کرنا**: ہمیشہ LLMs کے آؤٹ پٹ کی درستگی اور معیار کو چیک کریں تاکہ یہ یقینی بنایا جا سکے کہ اس میں کوئی غیر مطلوبہ یا نامناسب معلومات نہ ہو۔
- **کسی بھی ڈیٹا لیک یا واقعے کی رپورٹنگ اور الرٹ کرنا**: LLMs کی کسی بھی مشکوک یا غیر معمولی سرگرمی یا رویے پر نظر رکھیں، جیسے غیر متعلقہ، غلط، توہین آمیز، یا نقصان دہ متن تیار کرنا۔ یہ ڈیٹا لیک یا سیکیورٹی واقعے کی نشاندہی ہو سکتی ہے۔

ڈیٹا سیکیورٹی، گورننس، اور تعمیل ان تمام تنظیموں کے لیے اہم ہیں جو ملٹی کلاؤڈ ماحول میں ڈیٹا اور AI کی طاقت سے فائدہ اٹھانا چاہتی ہیں۔ اپنے تمام ڈیٹا کی حفاظت اور گورننس ایک پیچیدہ اور کثیر الجہتی کام ہے۔ آپ کو مختلف قسم کے ڈیٹا (ساخت شدہ، غیر ساخت شدہ، اور AI سے پیدا شدہ ڈیٹا) کو مختلف جگہوں پر متعدد کلاؤڈز میں محفوظ اور منظم کرنا ہوتا ہے، اور آپ کو موجودہ اور مستقبل کے
> AI ریڈ ٹیمنگ کی مشق نے ایک وسیع تر معنی اختیار کر لیا ہے: یہ نہ صرف سیکیورٹی کی کمزوریوں کی جانچ پڑتال کرتی ہے، بلکہ دیگر نظامی خرابیوں کی بھی جانچ کرتی ہے، جیسے ممکنہ طور پر نقصان دہ مواد کی تخلیق۔ AI سسٹمز نئے خطرات کے ساتھ آتے ہیں، اور ریڈ ٹیمنگ ان نئے خطرات کو سمجھنے کے لیے بنیادی حیثیت رکھتی ہے، جیسے پرامپٹ انجیکشن اور غیر مستند مواد کی پیداوار۔ - [Microsoft AI Red Team building future of safer AI](https://www.microsoft.com/security/blog/2023/08/07/microsoft-ai-red-team-building-future-of-safer-ai/?WT.mc_id=academic-105485-koreyst)
[![Guidance and resources for red teaming](../../../translated_images/13-AI-red-team.642ed54689d7e8a4d83bdf0635768c4fd8aa41ea539d8e3ffe17514aec4b4824.ur.png)]()

نیچے وہ اہم نکات دیے گئے ہیں جنہوں نے Microsoft کے AI Red Team پروگرام کی تشکیل میں مدد دی ہے۔

1. **AI Red Teaming کا وسیع دائرہ کار:**
   AI red teaming اب نہ صرف سیکیورٹی بلکہ Responsible AI (RAI) کے نتائج کو بھی شامل کرتا ہے۔ روایتی طور پر، red teaming سیکیورٹی پہلوؤں پر مرکوز ہوتا تھا، جہاں ماڈل کو ایک ویکٹر کے طور پر دیکھا جاتا تھا (مثلاً، ماڈل کی چوری کرنا)۔ تاہم، AI سسٹمز نئی سیکیورٹی کمزوریوں کو جنم دیتے ہیں (مثلاً، prompt injection، poisoning)، جن پر خاص توجہ دینا ضروری ہے۔ سیکیورٹی کے علاوہ، AI red teaming انصاف کے مسائل (مثلاً، stereotyping) اور نقصان دہ مواد (مثلاً، تشدد کی ترویج) کی بھی جانچ کرتا ہے۔ ان مسائل کی جلد شناخت دفاعی سرمایہ کاری کی ترجیح بندی میں مدد دیتی ہے۔
2. **خطرناک اور غیر خطرناک ناکامیاں:**
   AI red teaming ناکامیوں کو دونوں زاویوں سے دیکھتا ہے، یعنی خطرناک اور غیر خطرناک۔ مثال کے طور پر، جب ہم نئے Bing کی red teaming کرتے ہیں، تو ہم صرف یہ نہیں دیکھتے کہ خطرناک حریف نظام کو کیسے نقصان پہنچا سکتے ہیں بلکہ یہ بھی جانچتے ہیں کہ عام صارفین کو کس طرح مسئلہ یا نقصان دہ مواد کا سامنا ہو سکتا ہے۔ روایتی سیکیورٹی red teaming جو زیادہ تر خطرناک عناصر پر توجہ دیتی ہے، کے برعکس، AI red teaming مختلف کرداروں اور ممکنہ ناکامیوں کو مدنظر رکھتی ہے۔
3. **AI سسٹمز کی متحرک نوعیت:**
   AI ایپلیکیشنز مسلسل ترقی پذیر ہوتی ہیں۔ بڑے زبان ماڈلز کی ایپلیکیشنز میں، ڈویلپرز بدلتے ہوئے تقاضوں کے مطابق خود کو ڈھالتے ہیں۔ مسلسل red teaming خطرات کی بدلتی نوعیت کے مطابق چوکسی اور موافقت کو یقینی بناتی ہے۔

AI red teaming مکمل حل نہیں ہے اور اسے اضافی کنٹرولز جیسے [role-based access control (RBAC)](https://learn.microsoft.com/azure/ai-services/openai/how-to/role-based-access-control?WT.mc_id=academic-105485-koreyst) اور جامع ڈیٹا مینجمنٹ حل کے ساتھ ایک معاون عمل سمجھنا چاہیے۔ یہ ایک ایسی سیکیورٹی حکمت عملی کی تکمیل کے لیے ہے جو محفوظ اور ذمہ دار AI حل استعمال کرنے پر مرکوز ہو، جو پرائیویسی اور سیکیورٹی کا خیال رکھے اور تعصبات، نقصان دہ مواد اور غلط معلومات کو کم کرنے کی کوشش کرے جو صارف کے اعتماد کو متاثر کر سکتی ہیں۔

یہاں اضافی مطالعے کی فہرست ہے جو آپ کو بہتر سمجھنے میں مدد دے گی کہ red teaming آپ کے AI سسٹمز میں خطرات کی شناخت اور ان کے تدارک میں کیسے مددگار ثابت ہو سکتی ہے:

- [Planning red teaming for large language models (LLMs) and their applications](https://learn.microsoft.com/azure/ai-services/openai/concepts/red-teaming?WT.mc_id=academic-105485-koreyst)
- [What is the OpenAI Red Teaming Network?](https://openai.com/blog/red-teaming-network?WT.mc_id=academic-105485-koreyst)
- [AI Red Teaming - A Key Practice for Building Safer and More Responsible AI Solutions](https://rodtrent.substack.com/p/ai-red-teaming?WT.mc_id=academic-105485-koreyst)
- MITRE کا [ATLAS (Adversarial Threat Landscape for Artificial-Intelligence Systems)](https://atlas.mitre.org/?WT.mc_id=academic-105485-koreyst)، جو AI سسٹمز پر حقیقی دنیا کے حملوں میں حریفوں کی حکمت عملیوں اور تکنیکوں کا ایک علم کا ذخیرہ ہے۔

## Knowledge check

ڈیٹا کی سالمیت کو برقرار رکھنے اور غلط استعمال کو روکنے کے لیے کون سا طریقہ کار مؤثر ہو سکتا ہے؟

1. ڈیٹا تک رسائی اور ڈیٹا مینجمنٹ کے لیے مضبوط role-based کنٹرولز رکھنا  
1. ڈیٹا کی غلط نمائندگی یا غلط استعمال کو روکنے کے لیے ڈیٹا لیبلنگ کا نفاذ اور آڈٹ کرنا  
1. یقینی بنانا کہ آپ کا AI انفراسٹرکچر مواد کی فلٹرنگ کی حمایت کرتا ہے  

جواب: 1، اگرچہ تینوں سفارشات بہترین ہیں، لیکن یہ یقینی بنانا کہ آپ صارفین کو مناسب ڈیٹا رسائی کی اجازت دے رہے ہیں، LLMs کے استعمال شدہ ڈیٹا کی چالاکی اور غلط نمائندگی کو روکنے میں بہت مددگار ثابت ہوگا۔

## 🚀 Challenge

AI کے دور میں حساس معلومات کو [گورن اور محفوظ کرنے](https://learn.microsoft.com/training/paths/purview-protect-govern-ai/?WT.mc_id=academic-105485-koreyst) کے بارے میں مزید پڑھیں۔

## شاندار کام، اپنی تعلیم جاری رکھیں

اس سبق کو مکمل کرنے کے بعد، ہمارے [Generative AI Learning collection](https://aka.ms/genai-collection?WT.mc_id=academic-105485-koreyst) کو دیکھیں تاکہ آپ اپنی Generative AI کی معلومات کو مزید بہتر بنا سکیں!

سبق 14 پر جائیں جہاں ہم [Generative AI Application Lifecycle](../14-the-generative-ai-application-lifecycle/README.md?WT.mc_id=academic-105485-koreyst) کا جائزہ لیں گے!

**دستخطی نوٹ**:  
یہ دستاویز AI ترجمہ سروس [Co-op Translator](https://github.com/Azure/co-op-translator) کے ذریعے ترجمہ کی گئی ہے۔ اگرچہ ہم درستگی کے لیے کوشاں ہیں، براہ کرم اس بات سے آگاہ رہیں کہ خودکار ترجمے میں غلطیاں یا عدم درستیاں ہو سکتی ہیں۔ اصل دستاویز اپنی مادری زبان میں ہی معتبر ماخذ سمجھی جانی چاہیے۔ اہم معلومات کے لیے پیشہ ور انسانی ترجمہ کی سفارش کی جاتی ہے۔ اس ترجمے کے استعمال سے پیدا ہونے والی کسی بھی غلط فہمی یا غلط تشریح کی ذمہ داری ہم پر عائد نہیں ہوتی۔