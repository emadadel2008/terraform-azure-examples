
<h1 align="center">🌩️ Terraform Azure Examples 🌩️</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Terraform-Cloud%20Infrastructure-5c4ee5?style=for-the-badge&logo=terraform">
  <img src="https://img.shields.io/badge/Azure-Cloud%20Platform-007FFF?style=for-the-badge&logo=microsoftazure">
</p>

---

## 🎯 الهدف

مرحبًا بك في مستودع **أمثلة تيرافورم على Azure** 🎯.  
هنا هتلاقي سيناريوهات عملية ومنظمة لبناء ونشر موارد Azure باستخدام Terraform، مناسب للمبتدئين والمحترفين. الهدف هو تمكينك من كتابة البنية التحتية ككود (IaC) على Azure بطريقة بسيطة وفعالة.

---

## 🧱 الهيكل

```
terraform-azure-examples/
│
├── 00-prerequisites/
├── 01-resource-group/
├── 02-storage-account/
├── 03-virtual-network/
├── 04-virtual-machine/
├── 05-app-service/
├── 06-key-vault/
├── 07-sql-database/
├── 08-policy-assignment/
├── .devcontainer/            # GitHub Codespaces support
└── README.md
```

### تفاصيل كل مجلد:

1. **00-prerequisites/**  
   يحتوي هذا المجلد على تعليمات الإعداد والتثبيت لجميع الأدوات المطلوبة لتشغيل Terraform على Azure مثل **Azure CLI** و **Terraform CLI**. تأكد من أنك قد قمت بتسجيل الدخول إلى حساب Azure الخاص بك باستخدام:
   ```bash
   az login
   ```

2. **01-resource-group/**  
   مثال لإنشاء **Resource Group** في Azure باستخدام Terraform:
   - **الملفات**: `main.tf`  
   - **الوصف**: يحتوي هذا المجلد على مثال لإنشاء Resource Group جديد على Azure.

3. **02-storage-account/**  
   مثال لإنشاء **Storage Account** في Azure:
   - **الملفات**: `main.tf`  
   - **الوصف**: ستتعلم كيفية إعداد حساب تخزين في Azure باستخدام Terraform.

4. **03-virtual-network/**  
   مثال لإنشاء **Virtual Network (VNet)** مع **Subnets**:
   - **الملفات**: `main.tf`  
   - **الوصف**: مثال لإنشاء شبكة افتراضية (VNet) مع بعض **Subnets** في Azure.

5. **04-virtual-machine/**  
   مثال لإنشاء **Virtual Machine**:
   - **الملفات**: `main.tf`  
   - **الوصف**: هذا المثال يقوم بإنشاء **Virtual Machine** على Azure باستخدام **Linux** كنظام تشغيل.

6. **05-app-service/**  
   مثال لإنشاء **App Service**:
   - **الملفات**: `main.tf`  
   - **الوصف**: ستتعلم كيفية نشر تطبيق على Azure باستخدام **App Service**.

7. **06-key-vault/**  
   مثال لإنشاء **Key Vault**:
   - **الملفات**: `main.tf`  
   - **الوصف**: إنشاء **Key Vault** لتخزين الأسرار والمفاتيح بشكل آمن.

8. **07-sql-database/**  
   مثال لإنشاء **SQL Database**:
   - **الملفات**: `main.tf`  
   - **الوصف**: نشر **SQL Server** مع قاعدة بيانات باستخدام **Terraform**.

9. **08-policy-assignment/**  
   مثال لتطبيق **Policy Assignment**:
   - **الملفات**: `main.tf`  
   - **الوصف**: مثال لتطبيق سياسات Azure على اشتراك معين باستخدام Terraform.

---

## 🛠️ المتطلبات

- **Azure CLI**: لتسجيل الدخول إلى Azure.
- **Terraform CLI**: لإنشاء الموارد على Azure باستخدام كود Terraform.
- **Azure Subscription**: تأكد من أن لديك اشتراك في Azure.
- **GitHub Codespaces** (اختياري): جرب الأمثلة مباشرة في المتصفح دون الحاجة إلى تثبيت أي أدوات محليًا.

### إعداد CLI

```bash
az login
az account set --subscription "SUBSCRIPTION_ID"
terraform version
```

---

## 🖥️ التجربة السريعة (GitHub Codespaces)

💡 **جديد!** جرب الأمثلة مباشرة في المتصفح باستخدام GitHub Codespaces.

1. افتح الريبو في GitHub.
2. اضغط على **Code** → **Open with Codespaces** → **Create new codespace**.

بعد فتح **Codespaces**، يمكن تنفيذ أي مثال عن طريق الانتقال إلى المجلد المعني وتشغيل الأوامر التالية:

```bash
terraform init
terraform plan
terraform apply
```

---

## 📦 كيفية الاستخدام

### 1️⃣ الدخول على مجلد المثال

```bash
cd 02-storage-account
```

### 2️⃣ تهيئة Terraform

```bash
terraform init
```

### 3️⃣ تشغيل الخطة

```bash
terraform plan
```

### 4️⃣ تطبيق الكود

```bash
terraform apply
```

---

## 🙌 المساهمة

- ⭐ اعمل **Star** للريبو إذا استفدت.
- 📢 شارك الريبو مع الآخرين.
- ✍️ إذا كنت تريد إضافة مثال آخر، قدم **Pull Request**.

---

## 👨‍💻 من أنا

**عماد عادل** — مهندس حلول سحابية معتمد من مايكروسوفت ومدرب معتمد  
[LinkedIn](https://www.linkedin.com/in/emadadel) | [YouTube](https://youtube.com/@emadadel)

---

