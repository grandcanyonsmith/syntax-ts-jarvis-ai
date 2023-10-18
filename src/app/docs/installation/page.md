---
title: Installation
nextjs:
  metadata:
    title: Installation
    description: Learn how to install and set up Jarvis AI.
---

Get started with Jarvis AI by following our step-by-step installation guide. Let's get your AI assistant up and running.

---

## System Requirements

Before installing Jarvis AI, ensure your system meets the following requirements:

### Node.js

Jarvis AI runs on Node.js. Make sure you have the latest stable version installed on your system.

### npm

npm is the package manager for Node.js and is used to install Jarvis AI. It comes bundled with Node.js, so if you have Node.js installed, you should have npm as well.

---

## Installation

Follow these steps to install Jarvis AI on your system:

```js
npm install @jarvisai/jarvis
```

This command installs Jarvis AI and its dependencies.

### Configuration

After installing Jarvis AI, you need to configure it to suit your needs.

```js
// jarvis.config.js
export default {
  strategy: 'predictive',
  engine: {
    cpus: 12,
    backups: ['./storage/jarvis.wtf'],
  },
}
```

This configuration file sets the strategy to 'predictive' and specifies the number of CPUs to use and the backup location.

---

## Verifying the Installation

To verify that Jarvis AI has been installed correctly, run the following command:

```js
jarvis --version
```

This command should display the installed version of Jarvis AI.

---

## Troubleshooting

If you encounter any issues during the installation, check the following:

### Node.js and npm versions

Ensure you have the latest stable versions of Node.js and npm. Outdated versions may cause compatibility issues.

### System resources

Ensure your system has enough resources (CPU, memory) to run Jarvis AI. If your system is low on resources, consider upgrading your hardware or adjusting the Jarvis AI configuration.

---

## Next Steps

After installing and configuring Jarvis AI, you're ready to start using your new AI assistant. Check out our [Getting Started Guide](/) for a quick introduction to Jarvis AI.