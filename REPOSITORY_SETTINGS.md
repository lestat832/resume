# GitHub Repository Settings Guide

## Repository Configuration

### Basic Information
- **Repository Name:** `resume`
- **Description:** "Professional resume of Marc Geraldez - Product Leader with 10+ years experience in digital media, edtech, and entertainment. Specialized in AI-driven features, data experimentation, and revenue growth."
- **Website:** https://[your-username].github.io/resume/ (will be available after GitHub Pages setup)
- **Visibility:** ✅ Public

### Topics
Add these topics for better discoverability:
- `resume`
- `cv`
- `portfolio`
- `product-management`
- `digital-media`
- `edtech`
- `ai-products`
- `entertainment`
- `revenue-growth`
- `product-leader`

### Features to Configure

#### GitHub Pages
1. Go to Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main`
4. Folder: `/` (root)
5. Save the settings
6. Your resume will be available at: `https://[your-username].github.io/resume/resume-web/`

#### Repository Features
- **Issues:** ❌ Disable (unless you want feedback)
- **Wiki:** ❌ Disable
- **Projects:** ❌ Disable
- **Discussions:** ❌ Disable
- **Allow forking:** ⚪ Optional

#### Profile Settings
- **Pin to profile:** ✅ Yes (Go to your profile and pin this repository)

### Social Preview
Consider adding a custom social preview image:
1. Create a 1280×640px image showcasing your resume
2. Upload via Settings → General → Social preview

### Branch Protection (Optional)
If you want to protect your main branch:
1. Settings → Branches → Add rule
2. Branch name pattern: `main`
3. Enable: Restrict who can push to matching branches

## Post-Setup Checklist
- [ ] Repository created and configured
- [ ] Description and topics added
- [ ] GitHub Pages enabled
- [ ] Repository pinned to profile
- [ ] Custom domain configured (optional)
- [ ] Social preview image added (optional)

## Custom Domain (Optional)
If you have a custom domain:
1. Add a `CNAME` file to `/resume-web/` with your domain
2. Configure DNS settings with your domain provider
3. Enable HTTPS in GitHub Pages settings