## Readme
# Oil Blockchain Asset Listing Guide

This guide explains how to add a new token logo to the `oil` blockchain asset list.

## 📁 Directory Structure

To add a new token, you must create a directory with the token’s contract address and include its logo inside.

## ✅ Steps to Follow

### 1. Navigate to the Assets Folder

Go to the following directory in the repository:
blockchains/oil/assets/


### 2. Create a Folder Named After the Token Contract Address

- Inside the `assets` directory, create a **new folder**.
- The folder name must be the **token’s contract address**, written in **lowercase**.

📌 **Example:**
blockchains/oil/assets/0xabc123def4567890abcdef1234567890abcdef12/



> ⚠️ Be sure the contract address is correct and fully lowercased.

### 3. Add the Token Logo

- Inside the newly created folder, add the token's logo file.
- The image **must** be named: logo.png
- Image requirements:
  - Format: **PNG**
  - Size: **256x256 pixels** (recommended)
  - Background: **Transparent** (preferred)

📂 **Final structure should look like this:**
blockchains/oil/assets/0xabc123def4567890abcdef1234567890abcdef12/
└── logo.png

---

## 🛠️ Additional Notes

- Only one `logo.png` file should be inside each contract address folder.
- Do not include additional files such as metadata, JSON, or other images unless specifically requested.
- Ensure the image is optimized and not too large in file size (preferably under 100KB).

## 📬 Submitting a Pull Request

Once your folder and logo are correctly added, commit your changes and submit a pull request. Make sure your PR includes only relevant files in the correct location.

---

Thank you for contributing to the Oil blockchain asset registry!



