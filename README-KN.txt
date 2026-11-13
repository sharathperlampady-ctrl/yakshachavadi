ಯಕ್ಷ ಚಾವಡಿ — GitHub Pages + Supabase ಆವೃತ್ತಿ

1. ಈ ಎಲ್ಲಾ ಫೈಲ್‌ಗಳನ್ನು GitHub repository ಯ ಮೂಲ (root) ಭಾಗಕ್ಕೆ ಅಪ್‌ಲೋಡ್ ಮಾಡಿ.
2. Supabase ನಲ್ಲಿ ಹೊಸ project ರಚಿಸಿ. SQL Editor ನಲ್ಲಿ supabase-setup.sql ನ ಸಂಪೂರ್ಣ SQL ಅನ್ನು Run ಮಾಡಿ.
3. Supabase Authentication ನಲ್ಲಿ ನಿಮ್ಮ admin email/password ಬಳಕೆದಾರರನ್ನು ರಚಿಸಿ.
4. Project Settings > API ಯ Project URL ಮತ್ತು anon/public key ಅನ್ನು supabase-config.js ನಲ್ಲಿ ಹಾಕಿ.
5. GitHub repository Settings > Pages > Deploy from a branch > main > /(root) ಆಯ್ಕೆಮಾಡಿ Save ಮಾಡಿ.
6. ಕೆಲವು ನಿಮಿಷಗಳ ನಂತರ https://YOUR-USERNAME.github.io/yaksha-chaavadi/ ತೆರೆಯಿರಿ.

ಭದ್ರತೆ: supabase-config.js ನಲ್ಲಿ anon/public key ಮಾತ್ರ ಬಳಸಿ. service_role key ಅನ್ನು ವೆಬ್‌ಸೈಟ್‌ಗೆ ಎಂದಿಗೂ ಸೇರಿಸಬೇಡಿ.
ಗಮನಿಸಿ: ಪ್ರಸ್ತುತ ಸಾರ್ವಜನಿಕರು ಸಲ್ಲಿಸಿದ ಕಾರ್ಯಕ್ರಮ pending ಆಗಿರುತ್ತದೆ; authenticated admin ಮಾತ್ರ ಪ್ರಕಟಿಸಬಹುದು. ಮೊದಲ ಆವೃತ್ತಿಯಲ್ಲಿ poster upload ಬದಲಿಗೆ poster URL ಬಳಸಲಾಗಿದೆ.
