# Nawah Token Presale Page

صفحة السك الأولي (Presale) لتوكن **Nawah Token (NWTK)**.

## كيفية الاستخدام
1. قم برفع المجلد `nawah-presale` على GitHub Repository.
2. اذهب إلى `Settings > Pages` وقم بتفعيل GitHub Pages على الفرع `main` أو `gh-pages`.
3. افتح الرابط الناتج في المتصفح.
4. قبل الشراء، قم بتعديل `PRESALE_CONTRACT_ADDRESS` إلى عنوان عقد السك على Testnet أو Mainnet.
5. لتجربة BUSD/USDT يجب تنفيذ الموافقة (`approve`) على العقد قبل الدفع.

# Project Diagrams

هذا المجلد يحتوي على الرسوم التوضيحية الخاصة بمشروع **نواة**.  
جميع الرسوم متوفرة بصيغة **SVG** (يمكن عرضها مباشرة من GitHub أو تحريرها ببرامج مثل Inkscape).  

---

## 1. CI/CD Flow
- المسار الكامل: `docs/diagrams/ci-cd.svg`
- يوضح مراحل التكامل المستمر (CI) والنشر المستمر (CD) باستخدام GitHub Actions و Docker.

## 2. Tokenomics
- المسار الكامل: `docs/diagrams/tokenomics.svg`
- يوضح اقتصاديات الرمز (NFT / Token Flow) للمشروع.

## 3. Smart Contracts
- المسار الكامل: `docs/diagrams/contracts.svg`
- يوضح مكونات العقود الذكية وآلية تفاعلها مع النظام.

## 4. User Flow
- المسار الكامل: `docs/diagrams/user-flow.svg`
- يوضح رحلة المستخدم من التسجيل إلى التفاعل مع المنصة.

---

## طريقة الاستخدام
لإضافة رسم في أي صفحة `README.md` أو وثائق:

```markdown
![CI/CD Flow](docs/diagrams/ci-cd.svg)

