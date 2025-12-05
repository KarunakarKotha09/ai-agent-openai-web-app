# .devcontainer directory

This `.devcontainer` directory contains the configuration for a [dev container](https://docs.github.com/codespaces/setting-up-your-project-for-codespaces/adding-a-dev-container-configuration/introduction-to-dev-containers) and isn't used by the sample application.

The dev container configuration lets you open the repository in a [GitHub Codespace](https://docs.github.com/codespaces/overview) or a dev container in Visual Studio Code. For your convenience, the dev container is configured with the following:

- [Azure Developer CLI](https://learn.microsoft.com/azure/developer/azure-developer-cli/overview) (so you can run `azd` commands directly)
- [Azure CLI](https://learn.microsoft.com/cli/azure/)
- [.NET 9.0 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)

## VS Code Extensions

The dev container includes the following VS Code extensions pre-installed:

- **Microsoft Foundry** (`AzureML.vscode-azure-ai-foundry`) - For AI agent development with the visual designer
- **C# Dev Kit** (`ms-dotnettools.csdevkit`) - For .NET development support
- **GitHub Copilot** (`GitHub.copilot`) - AI-powered code suggestions
- **Azure Tools** (`ms-vscode.vscode-node-azure-pack`) - Azure resource management

## AI Agent Development

This dev container supports the [Microsoft Foundry VS Code extension](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/07-build-agent-in-vs-code.html) workflow for building AI agents:

1. Open the repository in a GitHub Codespace or VS Code dev container
2. Sign in to Azure using the Microsoft Foundry extension
3. Create and configure AI agents using the visual designer
4. Add OpenAPI tools and MCP Server tools to your agents
5. Test agents in the integrated playground

For detailed instructions, see the main [README.md](../README.md#option-2-create-agent-via-microsoft-foundry-vs-code-extension).
