# GitHub Repository Upload Instructions

## Repository Information

**Target Repository:** https://github.com/seanebones-lang/scanner-by-NextEleven-documents

## Files to Upload

Upload all files from the `docs/` directory to the root of the GitHub repository:

### Required Documents

1. **README.md** - Main repository documentation
2. **PRIVACY_POLICY.md** - Privacy policy
3. **TERMS_OF_SERVICE.md** - Terms of service
4. **EULA.md** - End User License Agreement
5. **LEGAL.md** - Legal information and disclaimers
6. **SUBSCRIPTION_DETAILS.md** - Subscription information
7. **SUPPORT.md** - Support policy
8. **FAQ.md** - Frequently asked questions
9. **ONBOARDING_TROUBLESHOOTING.md** - Onboarding and troubleshooting guide

## Upload Steps

### Option 1: Using GitHub Web Interface

1. Navigate to https://github.com/seanebones-lang/scanner-by-NextEleven-documents
2. Click "Add file" → "Upload files"
3. Drag and drop all files from the `docs/` directory
4. Add commit message: "Add all legal and support documentation"
5. Click "Commit changes"

### Option 2: Using Git Command Line

```bash
# Clone the repository (if not already cloned)
git clone https://github.com/seanebones-lang/scanner-by-NextEleven-documents.git
cd scanner-by-NextEleven-documents

# Copy all files from docs/ directory
cp /path/to/receipt/docs/*.md .

# Add all files
git add *.md

# Commit
git commit -m "Add all legal and support documentation for Scanner App by NextEleven"

# Push to repository
git push origin main
```

## Verification Checklist

After uploading, verify:

- [ ] All 9 documents are present in the repository
- [ ] README.md is in the root directory
- [ ] All markdown files are properly formatted
- [ ] Links in the app point to the correct GitHub URLs
- [ ] All documents have the correct email: info@mothership-ai.com
- [ ] All documents have been updated to January 2025

## App Configuration

The app is already configured to link to these documents via:

- **Constants.swift** - Contains all GitHub URLs pointing to this repository
- **SettingsView.swift** - Displays links in the Settings menu
- **UpgradedPaywallView.swift** - Displays links in the Subscription tab

All URLs use the format:
```
https://github.com/seanebones-lang/scanner-by-NextEleven-documents/blob/main/[FILENAME].md
```

## File Structure in Repository

```
scanner-by-NextEleven-documents/
├── README.md
├── PRIVACY_POLICY.md
├── TERMS_OF_SERVICE.md
├── EULA.md
├── LEGAL.md
├── SUBSCRIPTION_DETAILS.md
├── SUPPORT.md
├── FAQ.md
└── ONBOARDING_TROUBLESHOOTING.md
```

## Notes

- All documents are in Markdown format (.md)
- Documents are optimized for GitHub's markdown renderer
- All links in the app will automatically work once files are uploaded
- Documents can be updated directly in GitHub or via Git

---

**Last Updated:** January 2025

