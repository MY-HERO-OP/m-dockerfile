# Labani Stream Extractor

এই রিপোজিটরি `labani/stream:latest` Docker ইমেজ থেকে ফাইলগুলো এক্সট্র্যাক্ট করে GitHub Actions এর মাধ্যমে আর্টিফ্যাক্ট হিসেবে সংরক্ষণ করে।

## ব্যবহারের ধাপসমূহ

1. GitHub এ রিপোজিটরি ক্লোন করুন বা ফর্ক করুন।
2. রিপোজিটরির Actions ট্যাবে গিয়ে `Extract Docker Image` ওয়ার্কফ্লো চালু করুন।
3. ওয়ার্কফ্লো সম্পন্ন হলে, আর্টিফ্যাক্টস সেকশনে `extracted-stream` নামে একটি `.zip` ফাইল পাবেন।
4. সেই `.zip` ফাইল ডাউনলোড করে প্রয়োজনীয় ফাইলগুলো ব্যবহার করুন।

## নোট

- `.env` ফাইল বা অন্যান্য সংবেদনশীল তথ্য `.gitignore` এ রাখা হয়েছে যাতে সেগুলো গিটে আপলোড না হয়।
