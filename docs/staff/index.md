# Scandroid for Red Cross Staff

Scandroid is a tool to support **offline beneficiary validation** in Cash and Voucher Assistance (CVA) programmes.  
As Red Cross staff, your role is to configure and prepare the system so that Financial Service Providers (FSPs) can use it in the field.

Your main responsibilities include:

- **Registering beneficiaries** in the 121 Platform.  
- **Issuing QR codes** to each beneficiary.  
- **Configuring Scandroid** to:  
  - Decide which details are shown to FSPs (e.g. photo, date of birth, village).  
  - Connect to the correct **Kobo registration form**.  
  - Link to the correct **121 programme**.  
  - Select the correct **121 payment**.  

Scandroid is designed to be:
- **Flexible** – you choose what details are displayed for validation.  
- **Secure** – sensitive data is encrypted, and FSPs only see what is needed for identity confirmation.  
- **Practical** – works well in low-connectivity environments.

---

## Logging in as Red Cross Staff

When you open Scandroid in staff mode, you will see the login screen:

<img width="450" height="379" alt="image" src="https://github.com/user-attachments/assets/584d8dd6-25ee-4a0a-a249-d523bbe1ebb1" />

To log in:

1. Enter the **Username** provided to you.  
2. Enter the **Password** provided to you.  
3. Click **Submit** to access the staff dashboard.  

If you do not have staff login details, contact your system administrator.

---

## Staff Dashboard

After logging in, Red Cross staff will see the **Staff Dashboard**.  

<img width="432" height="379" alt="image" src="https://github.com/user-attachments/assets/205f23c6-afdf-4eee-b8e6-4ac3dca07890" />

From here you can access two main configuration areas:

- **System Configuration**  
  Set up the connection to the correct Kobo registration form, 121 programme, and 121 payment.  
  This ensures Scandroid is working with the right data and payment cycle.  

- **Display Configuration**  
  Choose which beneficiary details will appear to Financial Service Providers (FSPs) when they scan a QR code.  
  For example, you may configure it to show the beneficiary’s photo, date of birth, and village.  

These two steps must be completed before FSPs can begin scanning and validating payments.

---

## System Configuration

The **System Configuration** page is where you connect Scandroid to the correct Kobo form and 121 programme.  
This ensures that FSPs see the right beneficiaries and validate the correct payments.

<img width="1860" height="690" alt="image" src="https://github.com/user-attachments/assets/3954a261-15a8-46f3-bf5b-443c06a6fd54" />

### Kobo Information

- **Kobo Token** – enter the API token provided for your Kobo account.  
- **Kobo Asset ID** – enter the asset ID of the Kobo registration form used for this programme.  

### 121 Information

- **121 URL, Username, Password** – details for connecting to the 121 Platform.  
- **121 Program ID** – the programme number in 121 you want to use.  
- **Payment ID** – the specific payment cycle within that programme (e.g. *Payment 8*).  
- **Field to Match for Payment** – the unique field (such as `phoneNumber`) that links beneficiaries between Kobo and 121.  

### Encryption Settings

- **Encryption Key** – required to decrypt encrypted beneficiary fields (e.g. names, phone numbers, photos).  
- ⚠️ If this is incorrect, offline validation will not work. Only enter the correct key provided to you.  

---

When all fields are filled, click **Save**.  

Scandroid will now be connected to the right Kobo form and 121 programme.

---

## Display Configuration

The **Display Configuration** page controls which beneficiary details will appear to Financial Service Providers (FSPs) when they scan a QR code.  
This ensures FSPs have the right information to confirm identity, without exposing unnecessary details.

<img width="1877" height="823" alt="image" src="https://github.com/user-attachments/assets/a18b62c4-96a0-4f7d-8ff2-9179d6ce438d" />

### Adding and Configuring Fields
- **Field Key (from Kobo)** – enter the exact field name from the Kobo registration form (e.g. `fullName`, `phoneNumber`).  
- **Labels** – provide labels for each language used in your programme (e.g. English, French, Arabic).  
- **Use for Matching Payments** – select which field (such as `phoneNumber`) will be used to match records with payments from the 121 Platform.  
- **Remove** – click **X** if you want to remove a field from display.  

### Photo Field Configuration
- Tick **Enable photo field display** if you want a beneficiary photo shown to FSPs.  
- Enter the correct **Field Key** from Kobo (e.g. `photo`).  
- Provide labels in each language your programme supports.  

### Saving Your Configuration
Once you have finished adding and labelling the fields, click **Save**.  
From this point onward, these are the details that FSPs will see during validation.

