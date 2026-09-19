ONLINE URL VERSION — SETUP

এই version-এ Node.js/Acode build করার দরকার নেই। শুধু এই folder-এর files HTTPS static hosting-এ upload করুন।

সবচেয়ে সহজ:
1. GitHub Pages / Cloudflare Pages / Netlify / অন্য HTTPS static hosting ব্যবহার করুন।
2. index.html, sw.js, manifest.webmanifest একই folder-এ রাখুন।
3. পাওয়া HTTPS address মোবাইলে খুলুন।
4. Internet ON রেখে একটি Hindi voice model Download করুন।
5. Generate করে পরীক্ষা করুন।
6. Browser menu থেকে Add to Home Screen/Install করুন।
7. এরপর Internet OFF করে ব্যবহার করুন।

গুরুত্বপূর্ণ:
- TTS library প্রথমবার CDN থেকে JavaScript নেয়; তাই প্রথমবার online থাকা দরকার।
- Voice model browser-এর local storage/OPFS-এ cache হয়।
- Browser data/site storage clear করলে model আবার download করতে হবে।
- তিনটি Hindi model আলাদা করে download করলে প্রায় 190 MB-এর মতো storage লাগতে পারে।
- এই version voice cloning নয়; এটি offline neural Hindi TTS।
- Bengali voice এই build-এ যোগ করা হয়নি; compatible Bengali model যাচাই করে আলাদা voice option যোগ করতে হবে।
