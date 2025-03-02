# DevOps Daily Oh-My-Posh Theme

## Installation

- Prerequisite: Install [Oh-My-Posh - For Linux](https://ohmyposh.dev/docs/installation/linux) here
- Install [Nerd Font](https://www.nerdfonts.com/font-downloads), I am using `FiraCode Nerd Font`. Make sure to set this font to your terminal, else you will see `?` like logo.
- Copy the theme configuration YAML into your local terminal, suggested to put into `../bin/oh-my-posh/custom/themes/devops-daily.omp.yaml`.
- Add command below into `.zshrc`. Change `--config` path refer to your local theme configuration YAML.

```bash
eval "$(oh-my-posh init zsh --config '../oh-my-posh/custom/themes/devops-daily.omp.yaml')"
```

## Features

- SSH Session
- Git & Remote Info
- Execution Time
- Date & Time
- Directory Path
- DevOps Workspace Tooltips (Require CLI)
  - AWS CLI with Terraform / OpenTofu
  - Azure CLI with Terraform / OpenTofu
  - GCP CLI with Terraform / OpenTofu
  - Kubernetes
    - kubectl
    - kubectx
    - helm

## Sample Output

- Git
    ![Git](./readme_assets/git.png "Git")
- Kubernetes ToolTips
    ![Kubernetes ToolTips](./readme_assets/kubernetes.png "Kubernetes Tooltips")
- Kubernetes ToolTips
    ![AWS](./readme_assets/aws.png "AWS")
- Kubernetes ToolTips
    ![Azure](./readme_assets/azure.png "Azure")
