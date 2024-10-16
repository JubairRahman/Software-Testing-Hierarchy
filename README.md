# 🧪 Software Testing Hierarchy 

Software testing is a structured process that helps ensure the quality and reliability of software applications. Here’s a simplified hierarchy to guide you through the different testing types and methodologies used in the software development lifecycle.

---

## 🚀 **1. Unit Testing**

![Unit Testing Badge](https://img.shields.io/badge/Unit_Testing-EF5350?style=for-the-badge)

**Techniques:**
- 🏗️ **Structural Techniques**: 
  - Statement Testing
  - Condition Testing
  - Branch Testing
  - Path Testing
- 🛠️ **Functional Techniques**
- ⚠️ **Error-Based Techniques**

**Testing Methods:**
- 🔳 White Box Testing
- ⚫ Black Box Testing
- 🟨 Gray Box Testing

[Learn more about Unit Testing](./unittesting.md)

---

## 🔄 **2. Integration Testing**

![Integration Testing Badge](https://img.shields.io/badge/Integration_Testing-42A5F5?style=for-the-badge)

**Approaches:**
- 🔷 **Big Bang Approach**
- 🔀 **Incremental Approach**:
  - Top-down Integration
  - Bottom-up Integration
  - Mixed/Sandwich Integration

**Other Testing Types:**
- ⚡ **Adhoc Testing**
- ♻️ **Regression Testing**
- 🔄 **Retesting**
- 🧹 **Sanity Testing**
- 💨 **Smoke Testing**
- 🔧 **Parallel Testing**
- 🏁 **Benchmark Testing**
- 🔍 **End-to-End Testing**
- ⏳ **Reliability Testing**

[Learn more about Integration Testing](./integrationtesting.md)

---

## 🏗️ **3. System Testing**

![System Testing Badge](https://img.shields.io/badge/System_Testing-26A69A?style=for-the-badge)

**Types of Testing:**
- ⚙️ **Functional Testing**
- 🧩 **Non-Functional Testing**:
  - 🎨 **User Interface Testing**
  - 🧱 **Object Properties Testing**
  - 🎯 **Error Guessing Testing**
  - 🗂️ **Input Domain Testing**
  - 📊 **Database Testing**
  - 🔢 **Calculation Testing**
  - 🔗 **Links & URLs Testing**

[Learn more about System Testing](./systemtesting.md)

---

## 🎯 **4. Acceptance Testing**

![Acceptance Testing Badge](https://img.shields.io/badge/Acceptance_Testing-7E57C2?style=for-the-badge)

**Phases:**
- 🛠️ **Alpha Testing**
- 🔬 **Beta Testing**

**Non-Functional Testing Areas:**
- 🚦 **Load Testing**
- 💥 **Stress Testing**
- 🕐 **Soak Testing**
- 🌐 **Accessibility Testing**
- 📈 **Scalability Testing**

[Learn more about Acceptance Testing](./acceptancetesting.md)

---

## 🛡️ **Additional Focus Areas**

### 🔐 **Security Testing**
![Security Testing Badge](https://img.shields.io/badge/Security_Testing-F44336?style=for-the-badge)

- 🔑 **Authentication**
- 📝 **Authorization/Permission**
- 🍪 **Cookies Testing**
- 🔐 **Session Testing**
- 🔑 **Encryption/Decryption**
- 🛡️ **Penetration (Pen) Testing**

---

### 🚀 **Performance Testing**
![Performance Testing Badge](https://img.shields.io/badge/Performance_Testing-FFCA28?style=for-the-badge)

- 🧑‍💻 **Usability Testing**
- 💾 **Memory Leakage Testing**
- 💽 **Volume Testing**
- 🖥️ **Compatibility Testing**

  [Learn more about Acceptance Testing](./performancetesting.md)


---

### ⚙️ **Other Testing**
![Other Testing Badge](https://img.shields.io/badge/Other_Testing-9C27B0?style=for-the-badge)

- 🔧 **Configuration Testing**
- 🛠️ **Recovery Testing**
- 📦 **Installation Testing**
- ✔️ **Compliance Testing**
- 📑 **Documentation Testing**
- 🌐 **Interoperability Testing**

  [Learn more about Acceptance Testing](./othertesting.md)


---
# ![Repo Maps](https://img.shields.io/badge/Repo%20Maps-4285F4?logo=googlemaps&logoColor=fff&style=for-the-badge)
```bash

├── README.md             # Main overview of the repository
├── unittesting.md        # Unit testing section
│   ├── 🏗️ Structural Techniques:
│   │   ├── Statement Testing
│   │   ├── Condition Testing
│   │   ├── Branch Testing
│   │   └── Path Testing
│   ├── 🛠️ Functional Techniques
│   └── ⚠️ Error-Based Techniques
│       └── ...
│
├── integrationtesting.md  # Integration testing section
│   ├── 🔷 Big Bang Approach
│   ├── 🔀 Incremental Approach:
│   │   ├── Top-down Integration
│   │   ├── Bottom-up Integration
│   │   └── Mixed/Sandwich Integration
│   └── ⚡ Other Testing Types:
│       ├── Adhoc Testing
│       ├── Regression Testing
│       ├── Retesting
│       ├── Sanity Testing
│       ├── Smoke Testing
│       ├── Parallel Testing
│       ├── Benchmark Testing
│       ├── End-to-End Testing
│       └── Reliability Testing
│
├── systemtesting.md       # System testing section
│   ├── ⚙️ Functional Testing
│   └── 🧩 Non-Functional Testing:
│       ├── 🎨 User Interface Testing
│       ├── 🧱 Object Properties Testing
│       ├── 🎯 Error Guessing Testing
│       ├── 🗂️ Input Domain Testing
│       ├── 📊 Database Testing
│       ├── 🔢 Calculation Testing
│       └── 🔗 Links & URLs Testing
│
├── acceptancetesting.md    # Acceptance testing section
│   ├── 🛠️ Alpha Testing
│   ├── 🔬 Beta Testing
│   └── 🚦 Non-Functional Testing Areas:
│       ├── Load Testing
│       ├── Stress Testing
│       ├── Soak Testing
│       ├── Accessibility Testing
│       └── Scalability Testing
│
├── testingmethods.md       # Optional: A file for testing methods
│   ├── 🔳 White Box Testing
│   ├── ⚫ Black Box Testing
│   └── 🟨 Gray Box Testing
│
└── additionalfocusareas.md  # Additional focus areas
    ├── 🛡️ Security Testing
    │   ├── 🔑 Authentication
    │   ├── 📝 Authorization/Permission
    │   ├── 🍪 Cookies Testing
    │   ├── 🔐 Session Testing
    │   ├── 🔑 Encryption/Decryption
    │   └── 🛡️ Penetration (Pen) Testing
    │
    ├── 🚀 Performance Testing
    │   ├── 🧑‍💻 Usability Testing
    │   ├── 💾 Memory Leakage Testing
    │   ├── 💽 Volume Testing
    │   └── 🖥️ Compatibility Testing
    │
    └── ⚙️ Other Testing
        ├── 🔧 Configuration Testing
        ├── 🛠️ Recovery Testing
        ├── 📦 Installation Testing
        ├── ✔️ Compliance Testing
        ├── 📑 Documentation Testing
        └── 🌐 Interoperability Testing
```
This hierarchy helps beginners understand the wide array of testing techniques and methods used in software development, ensuring comprehensive coverage of both functional and non-functional aspects of a system.

---

### 📌 **Resources**:

- [Contribute to this repository](https://github.com/JubairRahman/Software-Testing-Hierarchy)
