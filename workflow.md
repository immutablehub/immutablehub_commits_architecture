
---

##  Authentication

> To interact with the immutablehub network, you must first authenticate your session using your decentralized identity (Wallet Address).

```bash
ihub op login <walletaddress>
```

## Project Setup
> immutablehub integrates directly with standard Git workflows. Follow these steps to prepare your repository for the network.

> 1. Initialize Repository
  Initialize a new Git repository in your project root.

## Bash

 git init

> 2. Stage and Commit
Capture your current project state.

## Bash

  git add .
  git commit -m "Initial commit or update message"

  
> 3. Deployment
Push your local repository to the immutablehub network

## Bash
```bash
  ihub op push <reponame>
```
Push your local mcp server repository to the immutablehub network

## Bash
```bash
  ihub op push <mcpreponame> --mcp true
```
Push your local prompt  to the immutablehub network

## Bash
```bash
  ihub op push <projectname> --prompt  true
```


## Commits 
> immutablehub  utilizes git bundle system to ensure that your version history is preserved exactly as it exists locally.
> This includes all branches, tags, and the full historical log & the  bundle and the physical source files are pushed to the network

---
  
