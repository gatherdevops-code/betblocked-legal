# BetBlocked Legal Documents

This directory contains the legal documents required for App Store submission:

## 📄 Files Created

1. **privacy_policy.html** - Complete privacy policy compliant with GDPR, CCPA, and Apple requirements
2. **terms_of_service.html** - Terms of service covering app usage, AI disclaimers, and liability
3. **contact_support.html** - Support page with multiple contact methods and crisis resources

## 🌐 Next Steps for Hosting

### Option 1: GitHub Pages (Recommended)
1. Create a new GitHub repository called "betblocked-legal"
2. Upload these HTML files
3. Enable GitHub Pages in repository settings
4. Your URLs will be: `https://yourusername.github.io/betblocked-legal/privacy_policy.html`

### Option 2: Netlify
1. Go to netlify.com
2. Drag and drop this folder
3. Get instant hosting with custom domain options

### Option 3: Firebase Hosting
1. Install Firebase CLI
2. Initialize hosting in this directory
3. Deploy with `firebase deploy`

## 📱 App Integration

Once hosted, update the URLs in `SettingsScreen.js`:

```javascript
const openPrivacyPolicy = () => {
  Linking.openURL('https://yourdomain.com/privacy_policy.html');
};

const openTermsOfService = () => {
  Linking.openURL('https://yourdomain.com/terms_of_service.html');
};

const openSupport = () => {
  Linking.openURL('https://yourdomain.com/contact_support.html');
};
```

## ✅ Apple Compliance

These documents include:
- ✅ Privacy policy with data collection details
- ✅ Terms of service with AI disclaimers
- ✅ Contact information for support
- ✅ Crisis support resources
- ✅ Data rights and deletion procedures
- ✅ Subscription and billing terms

## 🔄 Updates Needed

Before going live, customize these fields:
- Replace `[Your Jurisdiction]` with your actual jurisdiction
- Replace `[Your Business Address]` with your actual address
- Set up the email addresses (support@betblocked.app, etc.)
- Update any specific legal requirements for your location
