মাসিক হিসাব Android অ্যাপ

এই প্রজেক্টে আয়/খরচ যোগ, সম্পাদনা, মুছে ফেলা, মাসিক সারাংশ, CSV ডাউনলোড এবং JSON ব্যাকআপ আছে।

APK তৈরি করতে:
1. GitHub-এ নতুন repository তৈরি করুন।
2. এই ZIP-এর ভেতরের সব ফাইল repository-তে আপলোড করুন।
3. GitHub repository-এর Actions ট্যাবে যান।
4. “Build Monthly Hisab APK” workflow নির্বাচন করে Run workflow চাপুন।
5. কাজ শেষ হলে workflow run-এর Artifacts থেকে monthly-hisab-debug-apk.zip ডাউনলোড করুন।
6. ZIP extract করে app-debug.apk Android ফোনে পাঠিয়ে ইনস্টল করুন। ফোনে প্রয়োজন হলে “Install unknown apps” অনুমতি দিন।

নোট: এটি debug APK। ব্যক্তিগত ব্যবহারের জন্য। হিসাব ফোনের অ্যাপের লোকাল ব্রাউজার স্টোরেজে থাকে। ফোনের অ্যাপ ডেটা মুছে ফেললে হিসাব হারাতে পারে; নিয়মিত JSON ব্যাকআপ রাখুন।
