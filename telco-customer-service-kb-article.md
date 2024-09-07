### **Internal Knowledge Base: eSIM Reset on iPhone 14**

#### **Purpose**:  
Guide agents through the process of helping customers reset or reconfigure their eSIM on an iPhone 14. This procedure is useful in cases where the eSIM is malfunctioning, a customer is switching to a new network, or they are experiencing issues with mobile plan activation.

---

### **Scenario 1: Customer is Switching to a New Carrier**

1. **Verify Customer Account Information:**
   - Confirm the customer’s identity by verifying the account holder’s name, phone number, and security questions.
   - Check that the customer's account is eligible for an eSIM reset (i.e., the account is active, and there are no outstanding issues such as unpaid bills).

2. **Instruct the Customer to Remove Existing eSIM:**
   - Ask the customer to navigate to:
     - **Settings** > **Cellular**
     - Tap on the **eSIM** that needs to be removed.
     - Select **Remove Cellular Plan**.
   - Confirm that the eSIM has been successfully removed before proceeding.

3. **Ensure Activation of the New eSIM (For Fictitious Telco Network):**
   - Verify that the customer has the new eSIM QR code or activation details (PIN or activation URL).
   - Instruct the customer to:
     - Go to **Settings** > **Cellular** > **Add eSIM**.
     - Select the appropriate option to scan the QR code or enter the activation details manually.
   - Confirm successful activation by checking that the network is connected and service is functioning as expected (call, text, and data).

4. **Troubleshooting (if activation fails):**
   - Confirm the QR code or activation details with the backend provisioning system.
   - Reset the customer’s network settings:  
     - **Settings** > **General** > **Reset** > **Reset Network Settings**.  
     - This will remove all saved Wi-Fi passwords and reset network configurations but will not affect other data.

---

### **Scenario 2: Customer is Having Issues with eSIM Activation**

1. **Verify SIM Status:**
   - Check in the internal system (e.g., CRM or billing system) to ensure that the eSIM profile is active and properly assigned to the customer's account.
   - Confirm with the provisioning system that the eSIM status is "ready for activation" or "active."

2. **Customer Actions (iPhone 14):**
   - Instruct the customer to go to:
     - **Settings** > **Cellular** > **Add eSIM**.
   - If they have an activation code, ask them to select **Enter Details Manually** and enter the required eSIM information (provided via SMS, email, or customer portal).
   
3. **Verify Connection:**
   - Once activated, instruct the customer to check the network status:
     - Open **Settings** > **Cellular** and verify that the correct cellular plan is listed.
     - If there are issues with connectivity (e.g., no signal, data not working), advise them to enable **Airplane Mode** for 30 seconds and then disable it.

4. **Escalation Path:**
   - If issues persist (e.g., the eSIM is stuck in activation or the profile isn’t working), escalate the case to Tier 2 support with the following details:
     - Customer account number.
     - Error message on the device (if any).
     - IMEI and eSIM EID numbers (found in **Settings** > **General** > **About**).
     - Timestamp of the activation attempt.

---

### **Scenario 3: Resetting eSIM on iPhone 14 for Troubleshooting Purposes**

1. **Customer Device Reset Instructions:**
   - If the customer is facing persistent network issues, instruct them to reset the eSIM configuration by following these steps:
     - **Settings** > **General** > **Reset** > **Reset Network Settings**.
     - After the reset, ask them to re-add the eSIM via **Settings** > **Cellular** > **Add eSIM**.

2. **Re-provisioning the eSIM:**
   - In case of a provisioning error, confirm that the customer’s device IMEI and EID are correctly registered in the provisioning system.
   - Instruct the customer to either scan the new eSIM QR code or manually input the details.

3. **eSIM Profile Refresh (Back-End):**
   - In some cases, an eSIM profile refresh may be required in the carrier’s provisioning system. Use the internal tool to refresh the customer’s eSIM profile:
     - Enter the customer’s account number.
     - Select **Refresh eSIM Profile** and confirm.
   - Inform the customer to restart the iPhone 14 after the refresh.

4. **Final Confirmation:**
   - Verify that the customer’s device is now showing the network carrier in the status bar and that calls, texts, and data services are functioning normally.

---

### **Scenario 4: Customer Wants to Transfer eSIM from Old iPhone to iPhone 14**

1. **Ensure eSIM Profile is Deactivated on Old Device:**
   - Ask the customer to remove the eSIM from their old device:
     - **Settings** > **Cellular** > Select eSIM > **Remove Cellular Plan**.

2. **Activate eSIM on iPhone 14:**
   - Go to **Settings** > **Cellular** > **Add eSIM**.
   - Scan the QR code or enter the new activation details.
   - Ensure that the network is functional by testing a call or sending a text message.

---

### **Common Errors and Solutions**

- **Error: "eSIM Activation Failed"**
  - Solution: Check backend system for provisioning errors. Have the customer reset their network settings and retry the activation.

- **Error: "No Service After eSIM Activation"**
  - Solution: Confirm that the cellular plan is active in the carrier system. Instruct the customer to toggle **Airplane Mode** and restart the device.

- **Error: "Invalid eSIM QR Code"**
  - Solution: Verify the correct QR code was provided to the customer. If needed, resend a new QR code via the eSIM portal.

---

### **References for Agents:**
- **eSIM Troubleshooting Guide** (Document #12345)
- **Provisioning Portal Access** (Internal Tool Link)
- **IMEI & EID Retrieval Guide** (Document #54321)

