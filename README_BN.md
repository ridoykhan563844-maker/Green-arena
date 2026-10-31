# GREEN ARENA — Android Starter Project

এটি একটি Flutter starter project। এতে Green theme, Home, Sports, free prediction demo, sample leaderboard ও guest profile আছে।

## গুরুত্বপূর্ণ সীমাবদ্ধতা
- এটি এখনো online-connected production app নয়।
- Login, cloud database, shared leaderboard, admin panel ও live updates এখনো যুক্ত হয়নি।
- ম্যাচগুলো sample/demo fixture; কোনো live sports data নয়।
- পয়েন্টের কোনো আর্থিক মূল্য নেই; deposit, withdrawal, cash-out বা real-money betting নেই।

## শুধু ফোন দিয়ে APK বানানোর পদ্ধতি

1. GitHub-এ একটি account খুলুন/লগইন করুন।
2. নতুন repository তৈরি করুন, নাম দিন `green-arena`।
3. ZIP ফাইলটি ফোনে Extract করুন।
4. Extract করা project-এর সব ফাইল GitHub repository-তে upload করুন। `.github` ফোল্ডারসহ upload করতে হবে।
5. GitHub repository-তে **Actions** ট্যাব খুলুন।
6. `Build Green Arena APK` workflow নির্বাচন করে **Run workflow** চাপুন।
7. Build সফল হলে workflow run-এর নিচে **Artifacts** থেকে `green-arena-android-apk` ডাউনলোড করুন।
8. ZIP artifact Extract করে `app-release.apk` ইনস্টল করুন। Android চাইলে browser/file manager-এর জন্য “Install unknown apps” অনুমতি দিন।

## পরবর্তী উন্নয়ন
প্রকাশের আগে backend/API, secure authentication, hosted PostgreSQL, server-side match simulation, privacy policy, terms, abuse controls এবং security testing যোগ করতে হবে। Public release-এর আগে স্থানীয় আইন ও app-store policy যাচাই করুন।
