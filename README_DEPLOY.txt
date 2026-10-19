SpecTrim repair package — 19 October 2026

Upload the CONTENTS of this folder to the ROOT of the existing GitHub repository (not a nested package folder). Replace index.html, owner.html, classic.html, assets/, and app/ as needed. Keep .github workflows already in the repo.

index.html = unified Supabase login and role routing.
owner.html = preserved existing owner administration code with white styling.
classic.html = preserved previous vehicle matching application.
Group and branch views = lightweight live Supabase data overviews; not replacements for any missing legacy management functionality.

IMPORTANT: The previous repository ZIP contained only a standalone visual homepage at its root; the functional owner.html was nested. The working historic group/branch dashboards were NOT present in this upload. Those cannot be restored from this ZIP alone.

Security: Supabase RLS policies must enforce dealer/branch access. UI restrictions are not a substitute. Live login, invites, stock, and RLS cannot be validated without access to the live Supabase environment and role accounts.

Android: this ZIP includes updated app/src/main/assets/index.html and owner.html; rebuild APK to see changes.
