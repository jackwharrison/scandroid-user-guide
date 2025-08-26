# Scandroid for Financial Service Providers (FSPs)

Scandroid is a lightweight tool designed to help Financial Service Providers (FSPs) validate and approve payments in **Cash and Voucher Assistance (CVA) programmes**, even in places with little or no internet connectivity.  

Each person registered in the programme is given a **QR code** by Red Cross staff. When you scan this QR code with Scandroid, key details are displayed (such as a photo, date of birth, or village). You can use these details to confirm the person’s identity by asking simple security questions.  

If the details match, you **approve the payment**. If they do not match, you **reject the payment**.  

Because Scandroid works offline, you can continue validating payments without internet access. All you need to do is **sync once** (when online) to get the latest information. Your decisions (approve or reject) are stored on the device, and when you are back online you can **push them to the 121 Platform** to finalise the payments.  

Scandroid is designed to be:
- **Reliable in low-connectivity environments**  
- **Easy to use in the field**  
- **Clear and secure** for payment validation  

# Logging in to Scandroid

When you first open Scandroid, you will see the login screen:

<img width="486" height="379" alt="image" src="https://github.com/user-attachments/assets/73aefb8f-bbb0-420b-bdaa-1f976841f4a0" />


To log in:

1. Enter the **Username** provided to you by Red Cross staff.  
2. Enter the **Password** provided to you by Red Cross staff.  
3. Click **Submit** to access the system.  

If you do not have login details, contact the Red Cross team member responsible for your programme.

# Syncing Records

After logging in, you will see the **Sync Offline Records** screen:

<img width="614" height="379" alt="image" src="https://github.com/user-attachments/assets/a218115a-55d1-4c41-bc9e-dd63d3fe5ea2" />

This page prepares the system so you can validate beneficiaries **offline**.  

### Step 1. Sync Latest Records (Online)
- Click this button while you are **connected to the internet**.  
- It will download the latest list of beneficiaries and their details from the Red Cross system (121 Platform).  

### Step 2. Import Offline Cache (Online)
- If you have received an offline cache file (for example, from Red Cross staff), use this option to upload it.  
- This ensures your device has the correct beneficiary data for offline validation.  

### Step 3. Scan QR Codes (Offline)
- Once Steps 1 and 2 are complete, you are ready to work **offline**.  
- Click this button to open the scanning page.  
- From here, you can scan beneficiary QR codes and carry out the validation process.  

⚠️ **Important:** Always complete Steps 1 and 2 while online before moving to Step 3. This makes sure you have the most recent information available.

# Scanning QR Codes

When you are ready to validate a beneficiary, open the scanning page and press **Start camera**:

<img width="757" height="352" alt="image" src="https://github.com/user-attachments/assets/31d29ae7-9b77-47ee-ad3e-6940765f0d1f" />

Hold the QR code provided by the Red Cross in front of the camera.  

⚠️ **Important:** This is a **special Scandroid QR code scanner**.  
- It is configured to read **beneficiary codes created by the Red Cross system**.  
- Your regular phone camera or other QR scanner apps will **not work**.  

Once the QR code is recognised, Scandroid will display the beneficiary’s details (such as photo, date of birth, and village). You can then confirm their identity by asking the relevant questions.

# Beneficiary Information

After scanning a QR code, the **Beneficiary Information** page will appear:

<img width="870" height="736" alt="image" src="https://github.com/user-attachments/assets/600a17b1-0b2a-4ce1-b4e6-8a131a640dbc" />

This page shows the details configured by the Red Cross staff for validation.  
These may include:  
- **Photo** of the beneficiary  
- **Name**  
- **Date of birth**  
- **Village or location**  
- Other details chosen by the Red Cross  

Use these details to confirm the person’s identity by asking simple security questions (e.g. “What is your village?” or “When were you born?”).  

### Making a decision
At the bottom of the page, you have two options:  
- ✅ **Payment Approved** – choose this if the details match and you are confident the person is the correct beneficiary.  
- ❌ **Payment Rejected** – choose this if the details do not match or you are not confident in the person’s identity.  

Your decision will be saved **offline** on the device. When you next connect to the internet, you will need to **sync Scandroid** to push these decisions back to the 121 Platform.

# Submitting a Decision

After you approve or reject a payment, you will see a confirmation screen:

<img width="479" height="382" alt="image" src="https://github.com/user-attachments/assets/8abfd4eb-a273-411f-bef3-34adfaeb12d1" />

This screen confirms that your decision has been saved **offline**.  

- The message shows how many **payments are ready to push to 121** once you reconnect to the internet.  
- You can choose to:
  - **Scan next beneficiary** – continue with the next QR code.  
  - **Go to homepage** – return to the Sync Offline Records page.  

⚠️ **Important:** Your decisions are not sent to the 121 Platform immediately. They are stored securely on your device and will only be pushed once you are back online and perform a sync.

# Generating Decisions to send to 121

Once you have finished scanning beneficiaries, you need to **send your approval and rejection decisions back to the 121 Platform**.  

On the homepage, select **Step 4. Generate Payments to Send to 121**:

<img width="577" height="256" alt="image" src="https://github.com/user-attachments/assets/1d342d1f-2873-401f-8786-9c708805048d" />

- The screen shows how many **payments are ready to submit**.  
- Click **Generate CSV** to prepare the file.  

### Important notes
- The CSV contains the decisions you made (approve/reject).  
- All sensitive beneficiary information is **encrypted** — no personal details are stored on your device.  
- When you are back online, this file will be securely pushed to the 121 Platform by the Red Cross system.  

This ensures that all payment validations you carried out offline are properly recorded in the central system.

# Sending Payments to 121

After generating the CSV, the last step is to **send your decisions back to the 121 Platform**.

<img width="577" height="234" alt="image" src="https://github.com/user-attachments/assets/e23cda5d-54b5-4fb8-86ce-86e89de79eab" />


### How it works
- If payments are ready, the screen will show:  
  ✅ *"CSV ready with X records"*  
- Press **Send payments** to upload the encrypted CSV file.  
- Once successful, you will see:  
  ✅ *"Payments submitted successfully!"*  

### If no payments are ready
- If you try to generate a CSV without approving or rejecting any beneficiaries, you will see:  
  ⚠️ *"No payments to export."*  
- In this case, you do not need to send anything.  

---

✅ **Summary**:  
- Always generate the CSV when you are back online.  
- Press **Send payments** to push your approvals/rejections securely to the 121 Platform.  
- No personal data is shared — only the encrypted validation results.

---

## Status and Logging Out

At the top of the screen you will see:

<img width="298" height="124" alt="image" src="https://github.com/user-attachments/assets/993134a5-b7da-43b2-bffd-90db2dfea44d" />

- **Online / Offline indicator** – shows whether your device is currently connected to the internet.  
  - *Online* = you can sync and send payments.  
  - *Offline* = you can still scan and validate beneficiaries, but syncing will not work until you reconnect.  
- **Language selector** – choose your preferred language for the interface.  
- **Logout button** – always log out at the end of your session to keep the system secure.  

