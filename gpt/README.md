# **QSS GPT — Configuration Guide**

This directory contains files required to configure **QSS GPT** in the ChatGPT GPT Builder.

## **Files**

* `bootstrap_instructions.md` — paste into the **Instructions** field
* `instructions.md` — upload into **Knowledge**
* Additional QSS `.md` files — upload into **Knowledge** (excluding version/author files)

## **GPT Builder Configuration**

### **Name**

`Question Space Builder`

### **Description**

```
TODO: add description
```

### **Instructions**

Paste the full content of `bootstrap_instructions.md`.

### **Conversation Starters**

Use short entries such as:

* TODO: add starters

### **Knowledge**

Upload:

* `instructions.md`
* All QSS model markdown files from [src](../src/)
  (Do not upload version and licensing, or author files.)

### **Model**

Select **GPT-5.1** (or latest available).

### **Capabilities**

All **OFF**:

* Web Search
* Canvas
* Image Generation
* Code Interpreter & Data Analysis

### **Actions**

None.
