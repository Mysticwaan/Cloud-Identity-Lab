# ☁️ Cloud Identity Lab: Microsoft Entra ID (Azure Active Directory)

This project explores Microsoft **Entra ID** (formerly **Azure Active Directory**) to understand modern cloud-based identity management. It focuses on creating users, groups, configuring authentication settings, and integrating cloud applications.

---

## 🧭 Overview

Microsoft Entra ID is a cloud-based identity and access management (IAM) service used to manage users and access to applications, both in the cloud and on-premises.

In this project, I:

- Set up a free Microsoft Entra ID tenant via the Azure portal
- Managed users and groups
- Explored app registration and SSO
- Configured basic conditional access policies
- Practiced role-based access control (RBAC)

---

## ✅ What I Did

### 🆓 Set Up an Entra ID Tenant

- Created a [free Azure account](https://azure.microsoft.com/free)
- Accessed the **Microsoft Entra admin center** at [entra.microsoft.com](https://entra.microsoft.com)
- Created a new **Microsoft Entra ID tenant**

### 👤 Managed Users and Groups

- Created cloud-only users in the Entra ID tenant
- Created security groups for access management
- Assigned users to groups manually

### 🔐 Configured Authentication Settings

- Enabled **Multi-Factor Authentication (MFA)** for selected users
- Reviewed **sign-in logs** and conditional access insights

### 🧩 Registered Applications

- Registered a demo app in **App registrations**
- Configured **redirect URIs** and generated a **client secret**
- Granted user/group access to the app via **Enterprise Applications**

### ⚙️ Set Up Conditional Access (Basic)

- Created policies requiring MFA for admin roles
- Set up a policy to block sign-ins from unsupported countries
- Tested policy behavior with sign-in logs

### 🧾 RBAC and Admin Roles

- Assigned the **User Administrator** role to a test user
- Explored differences between tenant-wide roles and app-specific permissions

---

## 🧠 Lessons Learned

- Microsoft Entra ID uses a different trust model than on-prem Active Directory
- Conditional Access is a powerful way to enforce security at scale
- App registration is essential for OAuth2/OpenID Connect integrations
- Entra ID’s logs provide valuable insights into sign-in risks and patterns

---

## 📸 Screenshots

> _Insert screenshots of the Entra portal: users page, group assignments, MFA settings, and app registration tabs._

---

## 🔧 Next Steps

- Integrate with a third-party app like Google Workspace or Salesforce
- Sync users from an on-prem Active Directory using **Azure AD Connect**
- Explore **Identity Protection** and **Privileged Identity Management (PIM)**
- Build a basic web app that uses Microsoft identity platform for authentication

---

## 📚 Resources

- [Microsoft Entra Documentation](https://learn.microsoft.com/entra/)
- [Microsoft Learn - Identity Modules](https://learn.microsoft.com/en-us/training/paths/secure-azure-identity/)
- [Microsoft Graph API](https://learn.microsoft.com/en-us/graph/overview)
