# Hiero - One Subscription for Everything AI

Hiero is an innovative platform that provides a unified subscription service for AI applications, offering usage-based billing and seamless integration for both users and AI businesses.

## 🌟 Features

### For Users
- Single subscription access to multiple AI applications
- Usage-based billing - only pay for what you use
- Seamless switching between AI platforms
- Simplified billing and management
- One-click access to various AI services

### For AI Businesses
- Streamlined payment processing
- Faster checkout experience compared to traditional processors
- Paid initial free trials for customers
- Access to a growing user cohort
- Usage-based revenue model
- Simplified integration process

## 🚀 Getting Started

### For Developers

1. Install the Hiero UI package:
```bash
npm i hiero-ui --save
```

2. Import and implement the checkout button:
```jsx
import { HieroCheckoutButton } from "@hiero/ui";

<HieroCheckoutButton
    appName="your-app-name"
    redirectUrl="https://your-app.com/success"
    email="user@example.com" // Optional
/>
```

### Authentication

All API requests require two keys:
```http
X-Developer-API-Key: YOUR_DEVELOPER_API_KEY
X-User-Connection-Key: USER_CONNECTION_KEY
```

## 📚 Documentation

- [Authentication Guide](/docs/authentication)
- [Express Checkout Integration](/docs/checkout)
- [User FAQ](/blog/user-faq)
- [Business FAQ](/blog/business-faq)

## 💡 Use Cases

- AI Startups looking to monetize their services
- Businesses seeking multiple AI solutions
- Developers building AI-powered applications
- Users wanting simplified access to multiple AI tools

## 🔒 Security

Hiero prioritizes security in all aspects:
- Secure API authentication
- Safe handling of connection keys
- Protected user data
- Encrypted transactions

## 🤝 Contributing

We welcome contributions! Please read our contributing guidelines before submitting pull requests.

## 📄 License

[License details to be added]

## 📞 Support

For support inquiries:
- Visit our [FAQ section](/blog/user-faq)
- Contact our support team
- Join our developer community

## 🔗 Links

- [Website](https://hiero.gl)
- [Documentation](https://hiero.gl/docs)
- [Blog](https://hiero.gl/blog)

---

Built with ❤️ by the Hiero team
