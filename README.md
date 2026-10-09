# Family Finance — iPhone PWA (demo)

Aceasta este o versiune **demonstrativă** a interfeței HTML existente, ambalată ca PWA. Nu este aplicație iOS nativă. Unele acțiuni sunt simulate, iar datele introduse nu sunt încă sincronizate/persistate ca într-un produs real. Nu introduce date financiare sensibile.

## Publicare gratuită de pe iPhone (GitHub Pages)
1. Creează un repository **public** nou pe github.com (de exemplu `family-finance-demo`). Atenție: toate fișierele încărcate într-un repo public sunt vizibile oricui.
2. În repository apasă **Add file → Upload files** și încarcă separat toate fișierele din acest folder, la rădăcina repository-ului (nu ZIP-ul). Interfața mobilă GitHub poate necesita „Request Desktop Website” în Safari.
3. În **Settings → Pages → Build and deployment**, alege **Deploy from a branch**, branch `main`, folder `/ (root)`, apoi Save.
4. După publicare, deschide adresa HTTPS indicată de GitHub Pages (de obicei `https://USERNAME.github.io/REPO/`) în **Safari**.
5. Safari → Share → **Add to Home Screen** → Add.

GitHub Pages este hosting static; nu configurează automat Supabase sau un AI real. Pentru date private/conturi și sincronizare avem nevoie de backend și reguli de acces.

## Feedback
`feedback.html` este un prototip local. Propunerile rămân în localStorage; nu există backend, voturi comune sau abonamente reale. Pentru lansare: Supabase Auth + tabele feedback/feedback_votes/reward_grants, RLS, moderare, prevenirea abuzurilor și acordare Premium doar de administrator.
