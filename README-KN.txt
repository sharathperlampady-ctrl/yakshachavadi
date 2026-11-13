ಯಕ್ಷ ಚಾವಡಿ — GitHub Pages + Supabase

1. ಈ ಫೋಲ್ಡರ್‌ನಲ್ಲಿರುವ ಎಲ್ಲಾ ಫೈಲ್‌ಗಳನ್ನು GitHub repository yakshachavadi ಯ root ಗೆ upload ಮಾಡಿ; ಹಳೆಯ ಫೈಲ್‌ಗಳನ್ನು replace ಮಾಡಿ.
2. supabase-config.js ನಲ್ಲಿ ನಿಮ್ಮ Project URL ಮತ್ತು Publishable key ಈಗಾಗಲೇ ತುಂಬಿಸಲಾಗಿದೆ. Secret key ಅನ್ನು ಎಂದಿಗೂ ಇಲ್ಲಿ ಹಾಕಬೇಡಿ.
3. Supabase > Authentication > Users ನಲ್ಲಿ ನಿಮ್ಮದೇ admin email ಬಳಸಿ user ರಚಿಸಿ (ಅಥವಾ invite ಮಾಡಿ). Public signups ಅನ್ನು ನಂತರ disable ಮಾಡಿ.
4. ಈ ZIPನ supabase-setup.sql ಅನ್ನು ತೆರೆಯಿರಿ. ನಿಮ್ಮ Admin UID ಈಗಾಗಲೇ ಸೇರಿಸಲಾಗಿದೆ. SQL Editorನಲ್ಲಿ ಸಂಪೂರ್ಣ SQL ಅನ್ನು Run ಮಾಡಿ.
5. GitHub Pages: Settings > Pages > Deploy from a branch > main > /(root).
6. Website: https://sharathperlampady-ctrl.github.io/yakshachavadi/
7. Admin page: https://sharathperlampady-ctrl.github.io/yakshachavadi/admin.html

ಭದ್ರತೆ: Publishable key browser ನಲ್ಲಿ ಇರಬಹುದು; ಅದು RLS ಜೊತೆಯಲ್ಲೇ ಸುರಕ್ಷಿತ. Secret/service_role key ಅನ್ನು ಎಂದಿಗೂ GitHubಗೆ upload ಮಾಡಬೇಡಿ. Admin ಅನುಮತಿ admin_users allowlist ಮೂಲಕ ನಿಯಂತ್ರಿತವಾಗಿದೆ.
ಈ ಆವೃತ್ತಿಯಲ್ಲಿ ಪೋಸ್ಟರ್ upload ಇಲ್ಲ; poster URL ಮಾತ್ರ ಸ್ವೀಕರಿಸುತ್ತದೆ.
