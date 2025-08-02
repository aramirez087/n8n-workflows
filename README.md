# 🤖 N8N Automation Workflows

A collection of useful n8n workflows for automating everyday tasks and monitoring systems. Each workflow is production-ready and comes with detailed documentation.

## 📋 Available Workflows

### 💱 Exchange Rate Monitor
Monitor Costa Rican exchange rates from BCCR and get real-time notifications via Telegram when rates change.

**Features:**
- Automated rate checking every 5 minutes during business hours
- Telegram notifications for rate changes
- Redis storage for rate comparison
- Robust error handling and logging

[📖 View Documentation](./tipo-cambio/README.md)

## 🚀 Getting Started

1. **Prerequisites**
   - n8n instance (self-hosted or cloud)
   - Required services per workflow (Redis, Telegram bot, etc.)

2. **Import Workflow**
   - Download the `.json` file from the workflow folder
   - Import into your n8n instance
   - Configure credentials and settings

3. **Setup Credentials**
   - Follow the documentation for each workflow
   - Configure required API keys and connections

## 📁 Repository Structure

```
├── exchange-rate-monitor/
│   ├── README.md           # Detailed workflow documentation
│   ├── workflow.json       # n8n workflow file
│   └── preview.png         # Workflow visual preview
└── README.md              # This file
```

## 🤝 Contributing

Have a useful n8n workflow to share? Contributions are welcome!

1. Fork the repository
2. Create a new folder for your workflow
3. Include:
   - `workflow.json` - The n8n workflow export
   - `README.md` - Detailed documentation
   - `preview.png` - Screenshot of the workflow
4. Submit a pull request

## 📝 Workflow Documentation Template

Each workflow should include:
- Purpose and overview
- Architecture flow diagram
- Node-by-node configuration guide
- Credentials setup instructions
- Troubleshooting guide
- Maintenance recommendations

## 🛠️ Tech Stack

- **n8n** - Workflow automation platform
- **Various APIs** - Depending on workflow requirements
- **Storage Solutions** - Redis, databases, etc.
- **Notification Services** - Telegram, email, webhooks

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 💬 Support

- Open an issue for bugs or feature requests
- Check individual workflow documentation for specific troubleshooting
- Share your improvements and customizations

---

**Happy Automating!** 🎉