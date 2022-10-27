### Table of Contents
- [Table of Contents](#table-of-contents)
- [Concepts Section](#concepts-section)
- [CI\CD and Git](#ci-cd-and-git)
- [Terraform Cloud](#terraform-cloud)
- [Download and install](#download-and-install)
- [Recommend VS Code Extensions](#recommend-vs-code-extensions)
- [Testing Tools](#testing-tools)
- [Additional Tools](#additional-tools)

### Concepts Section

-	[What is Terraform?](https://www.terraform.io/intro/index.html)
-	[What is the Azure provider?](https://aka.ms/azterraform)
-	[Terraform Azure Tutorial](https://aka.ms/terraformgs)
- [Terraform - Types and Syntax](https://blog.devgenius.io/terraform-types-and-syntax-aa7b90ffff0e)
- [Terraform Init - Command Overview with Quick Usage Examples](https://faun.pub/terraform-init-command-overview-with-quick-usage-examples-752a5719c317)
- [Choosing Between Count and For-Each](https://nedinthecloud.com/2022/01/27/choosing-between-count-and-for-each/)
- [Using the Moved Block in Terraform 1.1](https://nedinthecloud.com/2021/12/14/using-the-moved-block-in-terraform-1-1/)
- [Terraform Apply? When External Change Happens.](https://nedinthecloud.com/2021/12/23/terraform-apply-when-external-change-happens/)
- [Terraform Cheat Sheet](https://itnext.io/terraform-cheat-sheet-3f7c5c55cfbc)
- [Terraform related articles index (Jack Roper)](https://jackwesleyroper.medium.com/terraform-related-articles-index-52fab8f11a0b)

### CI CD and Git
-	[Azure Pipeline Key Concepts](https://docs.microsoft.com/en-us/azure/devops/pipelines/get-started/key-pipelines-concepts?view=azure-devops)
-	[Azure Repos - Please focus on Git and not TFVC.](https://docs.microsoft.com/en-us/azure/devops/repos/get-started/what-is-repos?view=azure-devops)
-	[Azure Artifacts – Please focus on Build Artifacts.](https://docs.microsoft.com/en-us/azure/devops/pipelines/artifacts/artifacts-overview?view=azure-devops&tabs=nuget)
- [GitHub Actions with Terraform](https://nedinthecloud.com/2021/12/08/github-actions-with-terraform/)

### Terraform Cloud
- [Migrating State Data Off Terraform Cloud](https://nedinthecloud.com/2022/03/03/migrating-state-data-off-terraform-cloud/)

### GitHub and Azure Devops
- [Hosted Runners/Azure Devops Agents Images](https://github.com/actions/runner)
- [How to create Runners and/or Agents based on hosted Runners/Agents](https://github.com/actions/runner-images/blob/main/docs/create-image-and-azure-resources.md)

### Download and install

-	[Terraform](https://aka.ms/terraformnow)
-	[Git](https://aka.ms/gitnow)
-	[Azure CLI](https://aka.ms/azclinow)
-	[Power Shell Core](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell?view=powershell-7.1)
-	[Visual Studio Code](https://aka.ms/vscodenow)
-	[Windows Terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=en-us&gl=US)
- [Scott Hanselman’s Ultimate PowerShell Prompt](https://aka.ms/ultimateprompt)
- [Azure DevOps Pipelines Terraform Tasks](https://marketplace.visualstudio.com/items?itemName=charleszipp.azure-pipelines-tasks-terraform)

### Recommend VS Code Extensions
-	[Azure Pipelines - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-azure-devops.azure-pipelines)
-	[Azure Terraform - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azureterraform)
-	[HashiCorp Terraform - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=HashiCorp.terraform)
-	[Indent-Rainbow - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
-	[PowerShell - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell)
-	[Trailing Spaces - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)
-	[Azure Account - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account)
-	[VSCode-icons - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
-	[Git History - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
-	[GitLens — Git supercharged - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

### Testing Tools
- [TFLint](https://github.com/terraform-linters/tflint) - Terraform linter focused on possible errors, best practices, etc
- [terraform-compliance](https://terraform-compliance.com/) - Lightweight, security and compliance focused test framework against terraform to enable negative testing capability for your infrastructure-as-code
- [Terratest](https://github.com/gruntwork-io/terratest) - A Go library that makes it easier to write automated tests for your infrastructure code. It provides a variety of helper functions and patterns for common infrastructure testing tasks
- [Kitchen-Terraform](https://github.com/newcontext-oss/kitchen-terraform>) - Set of Test Kitchen plugins which enable a system to use Test Kitchen to converge a Terraform configuration and verify the resulting Terraform state with InSpec controls
- [tfsec](https://github.com/aquasecurity/tfsec) - tfsec uses static analysis of your terraform templates to spot potential security issues.

### Additional Tools
- [TerraCognita](https://github.com/cycloidio/terracognita) - Read from your existing cloud providers and generate IaC in Terraform
- [InfraMap](https://github.com/cycloidio/inframap) - Reads .tfstate or HCL to generate a graph specific for each provider
- [TerraCost](https://github.com/cycloidio/terracost) - Cloud cost estimation for Terraform in the CLI
- [Blast-Radius](https://github.com/28mm/blast-radius) - Tool for reasoning about Terraform dependency graphs with interactive visualizations
- [Terragrunt](https://github.com/gruntwork-io/terragrunt) - Thin wrapper for Terraform that provides extra tools for keeping your Terraform configurations DRY, working with multiple Terraform modules, and managing remote state
- [terraform docs](https://terraform-docs.io) - Generate Terraform modules documentation in various formats.
- [tfswitcher for Windows](https://github.com/jpmicrosoft/tfswitcher) - Windows was missing a Terraform version switching tool. I wrote some PowerShell functions that can be run via the PowerShell Profile that get the job done.
