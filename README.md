# 🛡️ Mediar Bitdefender Exception Workflow

Automate the process of adding **Mediar** to **Bitdefender Antivirus** exceptions to prevent false-positive deletions during installation.

## <img src="https://upload.wikimedia.org/wikipedia/commons/0/09/YouTube_full-color_icon_%282017%29.svg" width="30" height="22"> Proof Of Workflow 
> [![Watch the workflow in action](https://img.youtube.com/vi/R8gSaeEPBoE/0.jpg)](https://www.youtube.com/watch?v=R8gSaeEPBoE)

---

## 🚀 Overview
Some users experience issues where Bitdefender automatically flags and removes the Mediar application. This workflow automates the configuration of security exceptions to ensure a smooth installation experience.

---

## 🛠️ Prerequisites
* ⚠️ **Requirement:** This workflow is **only** applicable for users who have Bitdefender installed.
* Ensure you have [Mediar](https://app.mediar.ai/) installed or are in the process of setting it up.

---

## 📝 Workflow Setup
1.  **Launch Mediar:** Open your [Mediar](https://app.mediar.ai/) application.
2.  **Initialize:** Create a **'New'** workflow.
3.  **Record & Prompt:** Use the integrated *Record+Prompt AI* feature in the chat to define the steps for navigating Bitdefender settings.
4.  **Refine:** Adjust and test the steps to ensure reliable execution across different system states.

---

## ⚙️ Configuration Steps
To prevent Bitdefender from deleting Mediar, the workflow must automate:
1.  **Navigate** to Bitdefender's Advanced Settings.
2.  Locate **Manual Exceptions**.
3.  **Add** the following to the exclusion list:
    * 📂 Mediar Program Files Folder.
    * ⚙️ Executable: `terminator.exe`
    * ⚙️ Executable: `mediar.exe`

---

## 👨‍💻 Contribution Guidelines
Before starting, follow these steps to ensure a coordinated effort:

* 🔍 **Check Status:** Review existing comments to ensure no one else is currently working on this issue.
* 💬 **Claim Task:** Comment `/attempt` to signal that you are starting work.
* 🎥 **Demonstrate:** Your submission **must** include a screen recording showing the workflow operating end-to-end.
* 🧪 **Verification:** We will perform rigorous testing on VMs and various machine configurations to ensure cross-device compatibility.

---

## 📌 Submission Checklist
- [x] Workflow created in Mediar.
- [x] Exception logic tested for `terminator` and `mediar`.
- [x] End-to-end screen recording attached.
- [x] Task claimed via `/attempt`.

---
*Built for seamless security and automation.*
