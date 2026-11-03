# Recipe Genie desktop connector

Standalone connector for ChatGPT desktop on Windows 11 and macOS 14 or later. Recipe Genie cookbook access requires an active invited account.

Download installers from [Releases](https://github.com/johansigfrids/recipe-genie-desktop-releases/releases). Downloading a published release does not require a GitHub account.

The first family builds are unsigned by a trusted publisher and unnotarized. Follow the operating system approval flow only for a download you intended to install; do not disable system security globally. Instructions and dependency notices are inside each ZIP.

Extract the ZIP and open the app. Choose Install/Update, restart ChatGPT, then install/update Recipe Genie in your personal Plugins marketplace. Select it in a local Work chat and ask to connect your account. No Node, Go, Git, npm, separate CLI or background service is required.

Updates retain your login. Rerun a newer installer, restart ChatGPT and verify the version. Retained releases and the installer Rollback action support reverting. Remove clears this local connector and login; use Disconnect at [Recipe Genie connections](https://recipegenie.ai/connect) to revoke server access. Your recipes remain in your cookbook.

This repository contains distribution metadata and binary releases only. Source and build workflows are maintained privately. Published release assets are immutable.
