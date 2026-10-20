SPECTRIM — PHASE 1 VISUAL UPDATE

This package was built from the latest user-uploaded SpecTrim-main (1).zip.

Changes:
- Removed Staff sign in label from login.
- Unified white/charcoal/grey shell and responsive navigation.
- Embedded owner and sales views suppress their duplicate headers/navigation.
- Preserved the existing Supabase authentication and owner management scripts.
- Replaced broken owner and sales logo references with assets/spectrim-logo.webp.
- Mirrored the updated HTML and asset into Android WebView assets.
- No Supabase schema or RLS changes.

Deployment: Upload files from THIS ZIP to the GitHub repository root (not enclosing folder).
Back up current main branch first. Wait for GitHub Pages, hard-refresh and test four roles.
The login inactivity timeout and new management features are Phase 2, not implemented here.
This package has static code checks, not live authenticated Supabase test coverage.
