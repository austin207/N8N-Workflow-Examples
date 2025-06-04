# N8N Workflow Examples

This repository contains a collection of n8n workflows organized by different categories. These workflows demonstrate various automation scenarios and integrations using n8n.

## Prerequisites

- An n8n instance (self-hosted or cloud)
- Required API keys and credentials for specific services (mentioned in each workflow)
- Basic understanding of n8n workflow concepts

## How to Use These Workflows

1. Open your n8n instance
2. Click on "Workflows" in the left sidebar
3. Click the "+" button to create a new workflow
4. Click on the three dots menu (⋮) in the top right
5. Select "Import from File"
6. Choose the JSON file you want to import
7. The workflow will be imported with all its nodes and configurations

## Workflow Categories

### 1. Basics
- `airtable.json` - Basic Airtable integration
- `connect-sheets.json` - Google Sheets connection example
- `airtable-to-disk.json` - Export Airtable data to disk

### 2. Automation with LLMs
- `airtable-to-mail.json` - Send Airtable data via email
- `sentiment-analysis.json` - Analyze text sentiment

### 3. AI Agents and RAG
- `sponsor-reply.json` - Automated sponsor response system
- `email-summary-agent.json` - Email summarization agent
- `easy-mail-automation.json` - Simple email automation
- `send-mails-pinecone.json` - Send emails with Pinecone integration
- `mail-agent-pinecone.json` - Email agent with Pinecone
- `mails-to-pinecone.json` - Store emails in Pinecone
- `rag-bot.json` - RAG-based chatbot
- `load-data-pinecone.json` - Load data into Pinecone

### 4. Prompt Engineering
- Contains documentation and examples for prompt engineering

### 5. Cloud-based Integration (WhatsApp and Telegram)
- `sub-workflow-mails.json` - Email sub-workflow
- `sub-calendar-agent.json` - Calendar management agent
- `telegram3.json` - Advanced Telegram bot
- `telegram2.json` - Intermediate Telegram bot
- `telegram1-sub-workflow-search.json` - Telegram search functionality
- `subworkflow-contact-agent.json` - Contact management agent
- `sub-workflow-x-posts.json` - X (Twitter) post management
- `telegram1.json` - Basic Telegram bot
- `whatsapp-test-agent.json` - WhatsApp integration test

### 6. Webhooks and Debugging
- `error-workflow-trigger.json` - Error handling workflow
- `telegram-webhook.json` - Telegram webhook integration
- `stock-infos-flowise-n8n-sheets-agents.json` - Stock information to sheets
- `webhook-flowise-stock-data-sheets.json` - Stock data webhook to sheets

### 7. Advanced RAG and Website Integration
- `goldsmith-rag-app.json` - RAG application example
- `goldsmith-to-pinecone.json` - Data export to Pinecone

### 8. HTML to Markdown
- `scrape-html-to-markdown.json` - Convert HTML to Markdown

## Important Notes

1. **API Keys**: Most workflows require API keys or credentials. Make sure to:
   - Replace placeholder API keys with your own
   - Set up necessary environment variables
   - Configure authentication for each service

2. **Customization**:
   - Adjust node parameters according to your needs
   - Modify webhook URLs to match your environment
   - Update file paths and storage locations

3. **Testing**:
   - Test workflows in a development environment first
   - Verify all connections and credentials
   - Check error handling and edge cases

## Common Requirements

- Airtable API key
- Google Sheets API credentials
- Telegram Bot Token
- WhatsApp Business API access
- Pinecone API key
- OpenAI API key (for AI-related workflows)

## Support

For issues or questions:
1. Check the n8n documentation
2. Review the workflow comments and descriptions
3. Test each node individually
4. Verify API quotas and limits

## Contributing

Feel free to:
- Submit improvements
- Report issues
- Share your use cases
- Add new workflows

## License

This collection is provided as-is under the MIT License. 