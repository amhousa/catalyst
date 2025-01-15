<a href="https://catalyst.dev" target="_blank" rel="noopener noreferrer">
  <img src="https://storage.googleapis.com/bigcommerce-developers/images/catalyst_readme_banner.png" alt="تصویر بنر Catalyst for Composable Commerce" title="Catalyst">
</a>

<br />
<br />

<div align="center">

[![مجوز MIT](https://img.shields.io/github/license/bigcommerce/catalyst)](LICENSE.md)
[![گزارش Lighthouse](https://github.com/bigcommerce/catalyst/actions/workflows/lighthouse.yml/badge.svg)](https://github.com/bigcommerce/catalyst/actions/workflows/lighthouse.yml) [![Lint, Typecheck, gql.tada](https://github.com/bigcommerce/catalyst/actions/workflows/basic.yml/badge.svg)](https://github.com/bigcommerce/catalyst/actions/workflows/basic.yml)

</div>
<div dir="rtl">

**Catalyst** یک چارچوب ترکیبی و کاملاً قابل سفارشی‌سازی برای تجارت بی‌سر (Headless Commerce) در پلتفرم [BigCommerce](https://www.bigcommerce.com/) است. Catalyst با استفاده از [Next.js](https://nextjs.org/) ساخته شده است، از کامپوننت‌های فروشگاهی [React](https://react.dev/) استفاده می‌کند و بر پایه [GraphQL Storefront API](https://developer.bigcommerce.com/docs/storefront/graphql) طراحی شده است.

با انتخاب Catalyst، شما می‌توانید در چند ثانیه یک فروشگاه کاملاً کاربردی راه‌اندازی کنید و زمان خود را برای اتصال APIها یا ساخت کامپوننت‌های بهینه‌شده برای SEO، دسترسی‌پذیری و عملکرد که احتمالاً قبلاً بارها نوشته‌اید، صرف نکنید. در عوض، می‌توانید مستقیماً به ساخت برند خود و ایجاد سفارشی‌سازی‌های لازم بپردازید.

</div>
![-----------------------------------------------------](https://storage.googleapis.com/bigcommerce-developers/images/catalyst_readme_hr.png)

<p align="center">
 <a href="https://www.catalyst.dev">🚀 catalyst.dev</a> •
 <a href="https://developer.bigcommerce.com/community">🤗 انجمن توسعه‌دهندگان BigCommerce</a> •
 <a href="https://github.com/bigcommerce/catalyst/discussions">💬 بحث‌های گیت‌هاب</a> •
 <a href="/docs">💡 مستندات موجود در این مخزن</a>
</p>

![-----------------------------------------------------](https://storage.googleapis.com/bigcommerce-developers/images/catalyst_readme_hr.png)

## استقرار روی Vercel

ساده‌ترین روش برای استقرار فروشگاه Catalyst، استفاده از [پلتفرم Vercel](https://vercel.com/new) است که توسط سازندگان Next.js ارائه شده است.

مستندات استقرار Next.js را در [اینجا](https://nextjs.org/docs/deployment) مطالعه کنید.

<div align="left">
  <a href="https://vercel.com/new/clone?repository-url=https://github.com/bigcommerce/catalyst&root-directory=core&project-name=my-catalyst-storefront&repository-name=my-catalyst-storefront&integration-ids=oac_nsrwzogJLEFglVwt2060kB0y&external-id=catalyst&demo-title=BigCommerce+Catalyst+with+Vercel&demo-description=Create+a+BigCommerce+Catalyst+Storefront+and+Deploy+to+Vercel&demo-url=catalyst-demo.site&demo-image=https://storage.googleapis.com/s.mkswft.com/RmlsZTozODgzZmY3Yy1hNmVlLTQ1MGUtYjRkMS1mMjEyNzgxNjk5MTY%3D/Social-image-Catalyst.png"><img src="https://vercel.com/button" alt="استقرار با Vercel"/></a>
</div>

## شروع سریع

برای ایجاد یک پروژه جدید به صورت تعاملی، دستور زیر را اجرا کنید:

```bash
npm create @bigcommerce/catalyst@latest
```

سپس با درخواست‌های زیر روبرو خواهید شد:

```console
? What would you like to call your project?  my-faster-storefront
? Which would you like?
❯ Link Catalyst to a BigCommerce Store
  Use sample data

? Would you like to create a new channel? y

? What would you like to name the new channel? My Faster Storefront

Success! Created 'my-faster-storefront' at '/Users/first.last/Documents/GitHub/my-faster-storefront'
```

مراحل بعدی:

```bash
cd my-faster-storefront && npm run dev
```

اطلاعات بیشتر درباره Catalyst را در [catalyst.dev](https://catalyst.dev) بیابید.

## منابع

- [مستندات Catalyst](https://catalyst.dev/docs/)
- [Playground API گراف‌کیوال فروشگاه](https://developer.bigcommerce.com/graphql-storefront/playground)
- [Explorer API گراف‌کیوال فروشگاه](https://developer.bigcommerce.com/graphql-storefront/explorer)
- [مستندات توسعه‌دهندگان BigCommerce](https://developer.bigcommerce.com/docs/build)

![-----------------------------------------------------](https://storage.googleapis.com/bigcommerce-developers/images/catalyst_readme_hr.png)

> [!IMPORTANT]
> اگر تنها قصد دارید یک فروشگاه بسازید، از [CLI](#quickstart) شروع کنید که برنامه Next.js را در مسیر [/core](/core/) نصب می‌کند.  
> اگر می‌خواهید در توسعه Catalyst مشارکت کنید یا یک فورک از Catalyst ایجاد کنید، می‌توانید از [مستندات این مونو‌ریپو](https://catalyst.dev/docs/monorepo) برای شروع استفاده کنید.
