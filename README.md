# সহজ বাংলায় REST API

REST API বুঝতে হলে আমাদের সর্বপ্রথম বুঝতে হবে API কি এবং কেন ইউজ করা হয়। 
## API কি?  
ধরা যাক, আপনি ঢাকা থেকে কিশোরগঞ্জ ট্রেনের একটি টিকিট কাটতে চান। তাই আপনি ট্রেনের রিজার্ভেশন অ্যাপে ঢুকলেন। সেখানে আপনি স্টেশনের নাম, সময়, তারিখ, এবং ক্লাস নির্বাচন করে "সার্চ" বাটনে ক্লিক করলেন এবং আপনার দেওয়া ডেটার ভিত্তিতে টিকিটের ইনফরমেশন দেখালো।

এখন এখানে:
- **আপনি:** Client (ব্যবহারকারী)।
- **অ্যাপ:** আপনার Interface (ট্রেনের রিজার্ভেশন অ্যাপ)।
- **API:** মাধ্যম, যা ট্রেন কোম্পানির সার্ভার থেকে তথ্য নিয়ে আসে।
- **সার্ভার:** ডেটাবেস, যেখানে সমস্ত ট্রেনের শিডিউল, আসন সংখ্যা, এবং ভাড়ার তথ্য সংরক্ষিত থাকে।


## মূল বিষয়
API এর পূর্ণরুপ হলো **Application Programming Interface** যা ক্লায়েন্ট এবং সার্ভার (ডেটাবেস) এর মধ্যে যোগাযোগ করিয়ে দেওয়ার একটি মাধ্যম। এটি নিশ্চিত করে যে আপনি আপনার প্রয়োজনীয় তথ্য সহজে এবং দ্রুত পাচ্ছেন কিনা।

---
এখন আসা যাক REST API এর আদ্যোপান্তে
## REST API: কী এবং কেন?

ধরা যাক, আপনি এমন একটি রেস্তোরাঁতে গেছেন, যা অন্যান্য রেস্তোরাঁ থেকে আরও উন্নত এবং সুশৃঙ্খল। এখানে মেনু, অর্ডার এবং ডেলিভারির প্রতিটি ধাপ নির্দিষ্ট নিয়মের মধ্যে পরিচালিত হয়। ঠিক সেভাবেই, একটি API-কে যখন নির্দিষ্ট কিছু নিয়ম এবং নীতিমালার ভিত্তিতে সাজানো হয়, তখন ডাটা আদান প্রদান করতে সুবিধা হয় আর এমন একটি API স্ট্রাকচার হলো  **REST API** ।


### REST-এর পূর্ণরূপ
**Representational State Transfer**  
এটি ওয়েব-ভিত্তিক অ্যাপ্লিেশনের মধ্যে ডেটা আদান-প্রদানের সবচেয়ে জনপ্রিয় পদ্ধতিগুলোর একটি।

### REST API কী?
REST API হলো এমন একটি API, যা REST আর্কিটেকচারের নীতিমালা অনুসরণ করে। এর মাধ্যমে ক্লায়েন্ট এবং সার্ভারের মধ্যে সহজ এবং সুশৃঙ্খলভাবে ডেটা আদান-প্রদান সংগঠিত হয়।
