# FREE WINDOWS SERVER 2019 RDP

গিটহাব দিয়ে ভার্চুয়াল রিমোট কম্পিউটার (৭জিবি র‍্যাম, ডুয়াল কোর প্রসেসর, ২৫৫জিবি এসএসডি) তৈরি করুন বিনামূল্যে।

যা যা লাগবেঃ
মোবাইল/কম্পিউটার/ল্যাপটপ
রিমোট ডেস্কটপ কানেকশন বা আরডিপি প্রোগ্রাম বা অ্যাপস
গিটহাব একাউন্ট
NGROK একাউন্ট
NGROK এর অথেনটিকেশন টোকেন

নির্দেশনা অনুসরণ করুনঃ
+ শুরু করতে ফর্ক (Fork) বাটনে ক্লিক করুন (মোবাইলে করতে ডেস্কটপ মোড নির্বাচন করুন)
+ NGROK_AUTH_TOKEN পেতে এই ওয়েবসাইটে https://dashboard.ngrok.com ভিজিট করুন
+ এই রিপোজিটরিতে, সেটিংসে যান -> সিক্রেটস -> নিউ রিপোজিটরি সিক্রেটস এ ক্লিক করুন
+ নাম (Name): NGROK_AUTH_TOKEN
+ ভ্যালু (Value): https://dashboard.ngrok.com/auth/your-authtoken copy and paste authtoken in the value
+ "Add Secret" এ ক্লিক করুন
+ অ্যাকশনে যান (যদি আপনি এই সতর্কবার্তা "I understand..." দেখতে পান, "Yes, Ok" ক্লিক করুন) -> FreeRDP -> Run Workflow
+ ওয়েবসাইটটি রিফ্রেশ করুন - এরপর FreeRDP > build এ যান
+ রিমোট কম্পিউটারে এক্সেস করার জন্য ইউজারনেম ও পাসওয়ার্ড পেতে "RDP INFO LOGIN" এর ডাউন এরোতে ক্লিক করুন আর আইপি এড্রেস পেতে এই ওয়েবসাইটে যান https://dashboard.ngrok.com/endpoints/status

ব্যাস! তৈরি হয়ে গেল রিমোট কম্পিউটার। আপনি আরামসে যা খুশি কাজ করতে পারবেন! (কোড সম্পাদন, ব্রাউজিং, আপলোড-ডাউনলোড, স্পিডটেস্ট সহ আরো অনেক কিছু)

সতর্কতাঃ এই পদ্ধতিটি শুধুমাত্র শিক্ষামূলক উদ্দেশ্যে ব্যবহার করা যাবে, কোন অসদুপায় অবলম্বনের জন্য নয়! ক্রিপ্টোমাইনিং করা বা মালওয়্যার/ভাইরাসযুক্ত সফটওয়্যার ব্যবহার করা নিষিদ্ধ, অন্যথায় গিটহাব কর্তৃপক্ষ আপনার একাউন্ট বা এই রিপোজিটরি ব্যান হয়ে যাওয়ার আশঙ্কা হতে পারে।

<br>সর্বোচ্চ সময়কালঃ ৬ ঘণ্টা (এর বেশি ব্যবহার করতে পারবেন না, স্বয়ংক্রিয়ভাবে বন্ধ হয়ে যাবে তবে আবার নতুন করে নিয়ম অনুসরণ করে চালু করতে হবে, দিনে সর্বোচ্চ ১-২বার অ্যাকশন চালু করা ভালো।) </br>
অপারেটিং সিস্টেমঃ উইন্ডোজ সার্ভার ২০১৯ - ডেটাসেন্টার এডিশন

Forked from https://github.com/FDCI1337/RDP
Translated by NiDawgBD
