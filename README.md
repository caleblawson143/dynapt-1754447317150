# Dynapt 1754447317150

This website was automatically generated and deployed using the Web Optimizer tool.

## 🚀 Live Website

The website is automatically deployed to Azure Container Apps via GitHub Actions.

## 🏗️ Architecture

- **Frontend**: Generated using AI-powered optimization
- **Hosting**: Azure Container Apps
- **CI/CD**: GitHub Actions
- **Domain**: Auto-generated Azure domain

## 📁 Project Structure

```
.
├── .github/workflows/    # GitHub Actions workflows
├── src/                  # Source code (if applicable)
├── public/              # Static assets (if applicable)
├── package.json         # Dependencies (if applicable)
└── README.md           # This file
```

## 🔄 Deployment

The website is automatically deployed when changes are pushed to the main branch:

1. GitHub Actions triggers on push/PR
2. Builds the application (if needed)
3. Deploys to Azure Container Apps
4. Provides deployment URL

### 🔐 Required Secrets

To enable Azure deployment, add these secrets to your repository:
- AZURE_CLIENT_ID: Azure service principal client ID
- AZURE_TENANT_ID: Azure tenant ID
- AZURE_SUBSCRIPTION_ID: Azure subscription ID

You can create these in the Azure portal or use the Azure CLI:

```bash
az ad sp create-for-rbac --name "github-actions-deploy" --role contributor --scopes /subscriptions/YOUR_SUBSCRIPTION_ID/resourceGroups/Hosted-Websites --sdk-auth
```

## 🛠️ Local Development

If this is a Node.js application:

```bash
npm install
npm run dev
```

For static websites, simply open the HTML files in a web browser.

## 📝 Generated with Web Optimizer

This website was created using advanced AI analysis and optimization techniques to ensure:

- ⚡ Optimal performance
- 🎨 Modern design
- 📱 Mobile responsiveness
- ♿ Accessibility compliance
- 🔍 SEO optimization

---

*Generated on 8/5/2025 by Web Optimizer*
