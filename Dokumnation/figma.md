# 🌍 EcoBuddy - دليل التصميم الكامل للـ Figma Prototype

## 📐 الإعدادات الأساسية

### حجم الشاشات
- **Frame Size:** 375 × 812 (iPhone X/11/12)
- **Corner Radius للـ Mobile Container:** 24px
- **Background:** Gradient من #f0fdf4 لـ #ccfbf1

---

## 🎨 نظام الألوان (Color Palette)

### الألوان الأساسية
```
Primary Green: #16a34a (Green-600)
Secondary Green: #059669 (Emerald-600)
Light Green: #dcfce7 (Green-100)
Background: #f0fdf4 (Green-50)

Accent Colors:
- Blue: #3b82f6
- Purple: #a855f7
- Cyan: #06b6d4
- Yellow: #eab308
- Orange: #f97316
- Red: #ef4444

Neutral Colors:
- White: #ffffff
- Gray-50: #f9fafb
- Gray-100: #f3f4f6
- Gray-200: #e5e7eb
- Gray-400: #9ca3af
- Gray-600: #4b5563
- Gray-900: #111827
- Black-50% opacity: rgba(0,0,0,0.5)
```

### Gradients
```
Header Gradient: Linear من #16a34a إلى #059669 (90°)
Background Gradient: Linear من #f0fdf4 إلى #ccfbf1 (135°)
Chart Gradient: Linear من #16a34a إلى #34d399 (180°)
Gold Gradient: Linear من #f59e0b إلى #f97316 (90°)
```

---

## 📝 Typography (الخطوط)

```
Headings:
- H1: 24px, Bold
- H2: 20px, Bold
- H3: 18px, Semi-bold

Body Text:
- Regular: 16px, Regular
- Small: 14px, Regular
- Tiny: 12px, Regular

Special:
- Large Numbers: 32-40px, Bold
- Stats Numbers: 28px, Bold
- Points: 24px, Bold
```

**الخط المستخدم:** System Font (SF Pro للـ iOS / Roboto للـ Android)

---

## 📱 الشاشات الأربعة

---

# 🏠 الشاشة الأولى: HOME

## المكونات من فوق لتحت:

### 1. Status Bar (الشريط العلوي)
- **الأبعاد:** 375 × 44
- **Background:** Gradient (#16a34a → #059669)
- **اللون:** أبيض
- **المحتوى:**
  - النص "9:41" على اليسار
  - أيقونات البطارية والإشارة على اليمين

---

### 2. Header Section (الهيدر)
- **الأبعاد:** 375 × 200
- **Background:** نفس gradient الـ Status Bar
- **Corner Radius Bottom:** 24px
- **Padding:** 24px من كل جانب

**المحتوى:**

**أ) الترحيب والصورة الشخصية**
- **النص "Hi, Ahmed! 🌍"** - 24px Bold أبيض
- **النص "Let's save the planet together"** - 14px Regular لون #dcfce7
- **دائرة الصورة الشخصية:** 48 × 48
  - Background: أبيض بـ opacity 20%
  - في داخلها emoji 👤 حجم 24px
  - Position: أعلى اليمين

**ب) بطاقة النقاط (Points Card)**
- **الأبعاد:** 327 × 88 (full width minus padding)
- **Background:** أبيض بـ opacity 10% + Blur effect
- **Border:** 1px أبيض بـ opacity 20%
- **Corner Radius:** 16px
- **Padding:** 16px

**محتوى البطاقة:**
- النص "Your Eco Points" - 12px لون #dcfce7
- الرقم "2,456" - 32px Bold أبيض
- على اليمين: شريحة صغيرة
  - Background: أبيض opacity 20%
  - Corner Radius: 20px (pill shape)
  - Padding: 8px 16px
  - أيقونة TrendingDown (16×16)
  - النص "-156 kg CO₂" - 12px

---

### 3. Today's Impact Card (بطاقة التأثير اليومي)
- **Position:** تحت الهيدر بـ -16px (overlapping)
- **الأبعاد:** 327 × 140
- **Background:** أبيض
- **Corner Radius:** 16px
- **Shadow:** 0px 4px 12px rgba(0,0,0,0.08)
- **Padding:** 20px

**المحتوى:**
- عنوان "Today's Impact" - 12px لون #4b5563

**3 دوائر في صف واحد:**

**دائرة 1 (CO₂):**
- دائرة 48×48، Background: #dcfce7
- أيقونة Leaf بلون #16a34a (24×24)
- تحتها رقم "12.5" - 18px Bold
- تحته "kg CO₂" - 10px لون #6b7280

**دائرة 2 (Water):**
- دائرة 48×48، Background: #dbeafe
- أيقونة Droplet بلون #3b82f6 (24×24)
- تحتها رقم "45" - 18px Bold
- تحته "L Water" - 10px لون #6b7280

**دائرة 3 (Waste):**
- دائرة 48×48، Background: #f3e8ff
- أيقونة Recycle بلون #a855f7 (24×24)
- تحتها رقم "3.2" - 18px Bold
- تحته "kg Waste" - 10px لون #6b7280

---

### 4. Quick Actions (الإجراءات السريعة)
- **Spacing من الأعلى:** 24px
- **Padding الجوانب:** 24px

**عنوان "Quick Actions"** - 18px Semi-bold

**Grid: 2 Columns × 2 Rows** مع Gap: 12px

**كل بطاقة:**
- **الأبعاد:** 159 × 120
- **Background:** أبيض
- **Border:** 1px #f3f4f6
- **Corner Radius:** 16px
- **Shadow (on hover):** 0px 8px 16px rgba(0,0,0,0.1)
- **Padding:** 16px

**محتوى كل بطاقة:**
- دائرة ملونة 48×48 في الأعلى
- أيقونة بيضاء 24×24
- النص 14px Regular (Recycled / Saved Water / etc)
- النص "+10 points" - 12px لون #16a34a

**الألوان:**
1. Recycled: #3b82f6
2. Saved Water: #06b6d4
3. Saved Energy: #eab308
4. Plant Based: #16a34a

---

### 5. Recent Achievements (الإنجازات)
- **Spacing من الأعلى:** 24px
- **Padding الجوانب:** 24px

**عنوان "Recent Achievements"** - 18px Semi-bold

**3 بطاقات في Column:**

**كل بطاقة:**
- **الأبعاد:** 327 × 80
- **Background:** أبيض
- **Border:** 1px #f3f4f6
- **Corner Radius:** 16px
- **Padding:** 16px
- **Spacing بين البطاقات:** 12px

**محتوى:**
- Emoji كبير 32px على اليسار (🔥 / 🌟 / 🌳)
- اسم الإنجاز 14px Semi-bold
- Progress bar:
  - Background: #f3f4f6
  - Height: 8px
  - Corner Radius: 4px
  - Fill: Gradient (#16a34a → #34d399)
  - Width حسب النسبة (100% / 75% / 60%)
- النسبة المئوية 12px لون #6b7280 على اليمين

---

### 6. Bottom Navigation (التنقل السفلي)
- **الأبعاد:** 375 × 80
- **Background:** أبيض
- **Border Top:** 1px #e5e7eb
- **Position:** Fixed في الأسفل

**4 أزرار في صف:**

**كل زر:**
- **الأبعاد:** ~90 × 60
- Column layout (أيقونة فوق النص)
- **الأيقونة:** 24×24
- **النص:** 10px

**الحالات:**
- **Active:** لون #16a34a + scale 1.05
- **Inactive:** لون #9ca3af

**الأيقونات:**
1. Leaf - "Home"
2. Activity - "Activities"
3. BarChart3 - "Stats"
4. Users - "Community"

---

# ⚡ الشاشة الثانية: ACTIVITIES

## المكونات:

### 1. Status Bar
نفس الشاشة الأولى

### 2. Header (بسيط)
- **Background:** أبيض مع gradient خفيف
- **Padding:** 24px

**المحتوى:**
- "My Activities" - 24px Bold
- "Track your eco-friendly actions" - 14px لون #6b7280

---

### 3. Weekly Summary Card
- **الأبعاد:** 327 × 120
- **Background:** Gradient (#16a34a → #059669)
- **Corner Radius:** 16px
- **Padding:** 20px
- **Margin:** 24px من الجوانب

**المحتوى:**
- أيقونة Calendar + "This Week" في الأعلى (14px أبيض)
- أيقونة Leaf كبيرة شفافة في الخلفية
- الرقم "85 Points" - 32px Bold أبيض
- "Keep up the great work! 🌟" - 14px لون #dcfce7

---

### 4. Filter Buttons (أزرار الفلتر)
- **Horizontal Scroll**
- **Padding:** 24px من الجوانب
- **Gap:** 8px

**كل زر:**
- **Padding:** 8px 16px
- **Background:** أبيض
- **Border:** 1px #e5e7eb
- **Corner Radius:** 20px (pill)
- **Font:** 14px Regular
- **Hover:** Border #16a34a + Text #16a34a

**الأزرار:**
All, Transport, Food, Recycling, Water, Energy

---

### 5. Activities List (قائمة الأنشطة)
**Vertical Scroll**

**كل بطاقة:**
- **الأبعاد:** 327 × 100
- **Background:** أبيض
- **Border:** 1px #f3f4f6
- **Corner Radius:** 16px
- **Shadow (hover):** 0px 8px 16px rgba(0,0,0,0.1)
- **Padding:** 16px
- **Spacing:** 12px

**Layout:**
- أيقونة ملونة 48×48 على اليسار (Corner Radius: 12px)
  - الألوان: #3b82f6, #16a34a, #a855f7, #06b6d4, #eab308, #f97316
  - أيقونة بيضاء 24×24 بداخلها
- العنوان 16px Semi-bold
- الوقت 14px لون #6b7280
- 2 Badges في صف:
  - Badge 1: Background #dcfce7, Text #15803d (Impact)
  - Badge 2: Background #fef3c7, Text #b45309 (Points)
  - Padding: 4px 8px
  - Corner Radius: 12px
  - Font: 10px

**الأنشطة:**
1. "Used public transport" - Bus icon (#3b82f6) - "-2.5 kg CO₂" - "+20 pts"
2. "Plant-based meal" - Utensils icon (#16a34a) - "-1.8 kg CO₂" - "+15 pts"
3. "Recycled plastics" - Recycle icon (#a855f7) - "-0.8 kg waste" - "+10 pts"
4. "Shorter shower" - Droplet icon (#06b6d4) - "-25 L water" - "+8 pts"
5. "Used LED bulbs" - Zap icon (#eab308) - "-0.5 kWh" - "+12 pts"
6. "Reusable bag" - ShoppingBag icon (#f97316) - "-0.3 kg plastic" - "+5 pts"

---

### 6. Floating Add Button
- **الأبعاد:** 56 × 56
- **Background:** #16a34a
- **Corner Radius:** 28px (دائرة)
- **Shadow:** 0px 8px 24px rgba(22,163,74,0.4)
- **Position:** Fixed, Bottom Right
- **Distance:** 16px من اليمين، 96px من الأسفل (فوق الـ nav)
- **Icon:** Plus (24×24) أبيض

**Hover State:**
- Background: #15803d
- Scale: 1.1

---

### 7. Log Activity Modal (النافذة المنبثقة)

**يظهر من الأسفل عند الضغط على زر +**

- **الأبعاد:** 375 × 500
- **Background:** أبيض
- **Corner Radius Top:** 24px
- **Position:** Bottom of screen
- **Animation:** Slide up

**المحتوى:**

**Header:**
- "Log Activity" - 20px Bold
- زر X في دائرة (#f3f4f6) على اليمين

**النص:**
"Choose your eco-friendly action:" - 14px لون #6b7280

**Grid: 2 × 3 للأنشطة**
- Gap: 12px
- Padding: 24px

**كل بطاقة activity:**
- **الأبعاد:** 159 × 130
- **Background:** أبيض
- **Border:** 2px #e5e7eb
- **Corner Radius:** 16px
- **Padding:** 16px

**Selected State:**
- Border: 2px #16a34a
- Background: #f0fdf4

**المحتوى:**
- دائرة ملونة 48×48
- أيقونة بيضاء 24×24
- اسم النشاط 14px
- "+XX pts" 12px لون #16a34a

**Impact Preview Box:**
- **Background:** #f0fdf4
- **Corner Radius:** 16px
- **Padding:** 16px
- النص "Your Impact:" - 12px لون #6b7280
- Impact و Points في صف - 18px

**زر Log Activity:**
- **Width:** Full
- **Height:** 48px
- **Background:** #16a34a
- **Corner Radius:** 16px
- **Text:** أبيض 16px Semi-bold

---

# 📊 الشاشة الثالثة: STATS

## المكونات:

### 1 & 2. Status Bar & Header
نفس شاشة Activities

### 3. Overall Impact Card
- **الأبعاد:** 327 × 180
- **Background:** Gradient (#16a34a → #059669)
- **Corner Radius:** 16px
- **Padding:** 24px

**المحتوى:**
- أيقونة TrendingDown + "This Month" (14px)
- الرقم الكبير "2,456" - 40px Bold أبيض
- "Total Eco Points Earned" - 14px لون #dcfce7
- خط فاصل: 1px أبيض opacity 20%
- "Monthly Goal: 3000" و "82%" في صف - 14px
- Progress bar:
  - Height: 8px
  - Background: أبيض opacity 20%
  - Fill: أبيض بعرض 82%
  - Corner Radius: 4px

---

### 4. Weekly Chart (الرسم البياني)
- **Container:** 327 × 220
- **Background:** أبيض
- **Border:** 1px #f3f4f6
- **Corner Radius:** 16px
- **Padding:** 20px

**العنوان:** "Weekly Activity" - 18px Semi-bold

**Chart Area:**
- **الأبعاد:** 287 × 140
- **7 Bars** (Mon-Sun)

**كل Bar:**
- **Width:** ~36px
- **Gap:** 4px
- **Background:** Gradient (#16a34a → #34d399)
- **Corner Radius Top:** 8px
- **Heights مختلفة:**
  - Mon: 60%
  - Tue: 82%
  - Wed: 50%
  - Thu: 94%
  - Fri: 73%
  - Sat: 64%
  - Sun: 100%

**Labels تحت:**
- Mon, Tue, Wed, Thu, Fri, Sat, Sun
- 12px لون #6b7280

---

### 5. Monthly Impact Grid
**العنوان:** "Monthly Impact" - 18px Semi-bold

**Grid: 2 × 2**
- Gap: 12px

**كل بطاقة:**
- **الأبعاد:** 159 × 120
- **Background:** أبيض
- **Border:** 1px #f3f4f6
- **Corner Radius:** 16px
- **Padding:** 16px

**المحتوى:**
- مربع ملون 40×40، Corner Radius: 12px
- الرقم + الوحدة - 24px Bold + 14px Regular لون #6b7280
- الوصف - 12px لون #6b7280

**البطاقات:**
1. #16a34a - "156 kg" - "CO₂ Reduced"
2. #3b82f6 - "890 L" - "Water Saved"
3. #a855f7 - "42 kg" - "Waste Reduced"
4. #059669 - "12 trees" - "Trees Planted"

---

### 6. Milestones
**العنوان:** "Milestones" - 18px Semi-bold

**4 بطاقات في Column:**

**كل بطاقة:**
- **الأبعاد:** 327 × 72
- **Corner Radius:** 16px
- **Padding:** 16px
- **Spacing:** 12px

**Completed State:**
- Background: #f0fdf4
- Border: 1px #bbf7d0

**Incomplete State:**
- Background: أبيض
- Border: 1px #e5e7eb

**المحتوى:**
- Emoji 32px على اليسار
- اسم الـ milestone 16px
- Checkmark في دائرة خضراء على اليمين (للـ completed فقط)
  - دائرة 24×24، Background #16a34a
  - ✓ أبيض

**الـ Milestones:**
1. 🔥 "1 Month Streak" - Completed
2. ⭐ "1000 Points" - Completed
3. 🎯 "50 Activities" - Completed
4. 🏆 "Top 10% Users" - Incomplete

---

# 👥 الشاشة الرابعة: COMMUNITY

## المكونات:

### 1 & 2. Status Bar & Header
نفس السابق

### 3. Your Rank Card
- **الأبعاد:** 327 × 120
- **Background:** Gradient (#f59e0b → #f97316)
- **Corner Radius:** 16px
- **Padding:** 20px

**المحتوى:**
- دائرة صورة 48×48 + اسم المستخدم
- "Your Global Rank" - 12px لون #fef3c7
- "#4" - 24px Bold أبيض
- أيقونة Trophy كبيرة شفافة في الخلفية
- أيقونة TrendingUp + "Up 2 places this week!" - 14px

---

### 4. Active Challenges
**العنوان + زر "View All"**

**3 بطاقات:**

**كل بطاقة:**
- **الأبعاد:** 327 × 110
- **Background:** أبيض
- **Border:** 1px #f3f4f6
- **Corner Radius:** 16px
- **Padding:** 16px

**المحتوى:**
- العنوان 16px Semi-bold
- أيقونة Users + عدد المشاركين - 14px لون #6b7280
- "X days left" - 14px
- النقاط "+500" في الركن الأيمن - 14px #16a34a
- Progress bar في الأسفل:
  - "Progress" و النسبة - 10px
  - Bar نفس التصميم السابق

**التحديات:**
1. "Plastic-Free Week" - 234 participants - 3 days - 500 pts - 65%
2. "Zero Waste Challenge" - 189 participants - 5 days - 300 pts - 40%
3. "Plant 100 Trees" - 567 participants - 10 days - 1000 pts - 78%

---

### 5. Leaderboard
**العنوان + "This Week"**

**Container:**
- **Background:** أبيض
- **Border:** 1px #f3f4f6
- **Corner Radius:** 16px
- **Overflow:** hidden

**5 صفوف:**

**كل صف:**
- **Height:** 72px
- **Padding:** 16px
- **Border Bottom:** 1px #f3f4f6 (ما عدا الأخير)

**الصف الخاص بالمستخدم:**
- Background: #f0fdf4

**المحتوى:**
- الترتيب أو Medal (🥇🥈🥉) - 18px
- دائرة Avatar 40×40، Background #f3f4f6
- Emoji 20px
- الاسم 16px
- النقاط - 14px لون #6b7280
- أيقونة TrendingUp خضراء (إذا موجودة)

**القائمة:**
1. 🥇 🌟 "Sarah Green" - 3,842 pts ↑
2. 🥈 🌿 "Mike Eco" - 3,621 pts ↑
3. 🥉 🌍 "Emma Earth" - 3,489 pts ↓
4. #4 👤 "You (Ahmed)" - 2,456 pts ↑ (highlighted)
5. #5 🌲 "John Nature" - 2,234 pts ↑

---

### 6. Community Feed
**العنوان:** "Community Feed"

**2 بطاقات منشورات:**

**كل بطاقة:**
- **الأبعاد:** 327 × 140
- **Background:** أبيض
- **Border:** 1px #f3f4f6
- **Corner Radius:** 16px
- **Padding:** 16px
- **Spacing:** 16px

**المحتوى:**

**Header:**
- دائرة Avatar 40×40
- اسم المستخدم 14px Semi-bold
- الوقت 12px لون #6b7280

**Post Content:**
- النص 14px لون #374151

**Footer (3 أزرار):**
- Heart + عدد الإعجابات
- MessageCircle + عدد التعليقات
- Share2

**الأزرار:**
- لون #6b7280
- Hover: أحمر / أزرق / أخضر
- Font: 14px

**المنشورات:**
1. Sarah Green - 2h ago - "Just completed my first month of using reusable bags!..." - 45 ❤️ 12 💬
2. Mike Eco - 5h ago - "Switched to a plant-based diet this week..." - 67 ❤️ 23 💬

---

### 7. Bottom Navigation
نفس جميع الشاشات

---

## 🔗 الـ Prototyping (الربط والتفاعلات)

### الانتقالات بين الشاشات:

**من أي شاشة:**
1. زر "Home" في الـ Nav → شاشة Home
2. زر "Activities" → شاشة Activities
3. زر "Stats" → شاشة Stats
4. زر "Community" → شاشة Community

**Animation:**
- Type: **Dissolve** أو **Smart Animate**
- Duration: **300ms**
- Easing: **Ease Out**

---

### التفاعلات الخاصة:

**في شاشة Activities:**
1. الضغط على زر + (الدائرة الخضراء)
   - Action: **Open Overlay**
   - Target: Log Activity Modal
   - Animation: **Move In** (من الأسفل)
   - Duration: **400ms**

2. الضغط على X في الـ Modal
   - Action: **Close Overlay**
   - Animation: **Move Out** (للأسفل)

3. الضغط على أي Activity Type في الـ Modal
   - Action: **Change to** Selected State
   - Animation: **Smart Animate** - 200ms

4. الضغط على "Log Activity"
   - Action: **Close Overlay**
   - ثم **Navigate to** Activities Screen (محدّثة)

---

### Hover States (للعرض التوضيحي):

**البطاقات:**
- Scale: **1.02**
- Shadow: **0px 12px 24px rgba(0,0,0,0.12)**
- Transition: **200ms**

**الأزرار:**
- Opacity: **0.9**
- أو تغيير اللون للـ Darker shade

**Navigation Buttons:**
- Scale: **1.05** (للـ Active)
- Opacity: **0.6** للـ Inactive

---

## ✅ خطوات التنفيذ في Figma

### المرحلة 1: الإعداد
1. افتح Figma وأنشئ ملف جديد
2. اعمل 4 Frames بحجم **375 × 812**
3. سمّيهم: Home, Activities, Stats, Community
4. اعمل Frame للـ Modal بحجم **375 × 500**

### المرحلة 2: نظام الألوان
1. اعمل Color Styles لكل الألوان المذكورة
2. اعمل Gradient Styles
3. احفظهم في Library

### المرحلة 3: المكونات
1. صمم Status Bar كـ Component
2. صمم Bottom Nav كـ Component (مع Variants للـ Active/Inactive)
3. صمم Activity Card كـ Component
4. صمم Achievement Card كـ Component

### المرحلة 4: التصميم
1. ابدأ بشاشة Home واتبع التفاصيل أعلاه
2. استخدم Auto Layout لكل شيء
3. كرر للشاشات الأخرى

### المرحلة 5: Prototyping
1. اختار Frame Home
2. في الـ Prototype Panel على اليمين
3. اسحب من زر "Activities" في الـ Nav
4. وصّلها بـ Frame Activities
5. اختار Animation: Dissolve
6. كرر لكل الأزرار

### المرحلة 6: Modal
1. اعمل Overlay للـ Modal
2. وصّل زر + بالـ Modal
3. اختار "Open Overlay"
4. Position: **Manual**
5. Close when clicking outside: **نعم**

---

## 🎯 نصائح مهمة:

### Auto Layout
استخدم Auto Layout في كل مكان:
- **Padding:** لضبط المسافات الداخلية
- **Gap:** للمسافات بين العناصر
- **Fill container:** للعناصر اللي تملأ العرض

### Components & Variants
- اعمل Components للعناصر المتكررة
- استخدم Variants للحالات المختلفة (Active/Inactive)

### Constraints
- اضبط Constraints لكل العناصر
- معظم العناصر: **Left & Top**
- Bottom Nav: **Left & Bottom**

### Effects
- Shadow للبطاقات: **Y: 4px, Blur: 12px, Color: #000000 8%**
- Shadow للأزرار: **Y: 8px, Blur: 24px, Color: مطابق للون الزر 30%**

---

## 📥 Assets المطلوبة

### الأيقونات (من Lucide أو Feather):
- Leaf, Activity, BarChart3, Users
- TrendingDown, TrendingUp, Trophy, Award
- Recycle, Droplet, Zap, Bus, Utensils, ShoppingBag
- Calendar, Target, Heart, MessageCircle, Share2
- Plus, X, ChevronRight

### Emojis:
- 🌍 🔥 🌟 🌳 🎯 🏆
- 🥇 🥈 🥉
- 👤 🌿

---

## 🚀 جاهز للبدء!

الآن عندك كل حاجة تحتاجها لعمل الـ Prototype في Figma!

**نصيحة أخيرة:** ابدأ بشاشة واحدة الأول (Home)، وخذ وقتك في ضبط التفاصيل، بعدين انسخها وعدّل عليها للشاشات التانية.

**لو احتجت مساعدة في أي جزء معين، قولي وأنا هنا! 🎨**
