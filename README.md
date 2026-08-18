# EmmyTech Desk Admin

Static internal dashboard for the Emmy Technology Foldable Workspace Desk.

## GitHub Pages hosting

1. Create a GitHub repository named `emmytech-desk-admin`.
2. Push `index.html`, `README.md`, and `.nojekyll` to `main`.
3. In GitHub open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then save.

The URL will normally be:

`https://<github-username>.github.io/emmytech-desk-admin/`

## Security

The page contains only the Supabase publishable key. Customer data is returned only after a valid temporary admin token is issued by the protected admin RPCs. No Supabase secret/service-role key is stored in this repository.
