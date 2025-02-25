## **Call Tracking Notes Template**

### **Profile Information**

**Notes:** 

**Profile Name:** 

**Profile ID:** 
**Merchant ID:** 
**Asset ID:** 
**BTN (Business Tracking Number):** 
**CTN (Call Tracking Number):** 

**CID (Customer ID):** 
**JSRW (JavaScript Rewrite):** 
**GTM Container ID:** 
**URL:** 

#CMUPDATE 
Call Tracking:

---

### **Call Tracking Configuration**

1. **Local CTN:**  
- Based on the targeted location, a Local CTN (`CTN`) was procured, configured, imported, and forwarded to BTN (`BTN`) on Marchex and Skai.

2. **Toll-Free CTN:**  
- Based on the targeted location, a Toll-Free CTN (`CTN`) was procured, configured, and forwarded to BTN (`BTN`) on both Marchex and Skai.

3. **US Calls Blocking:**  
- US Calls are being blocked.

4. **CTN Verification:**  
- Checked the CTN (`CTN`) on both Marchex and Skai, and it was properly configured, imported, and forwarding to BTN (`BTN`).

5. **YP LP Website:**  
- The website (`URL`) is a YP LP, therefore, the BTN was changed for the CTN directly.

---

### **Website Protocol & Tracking**

1. **HTTP Protocol (Unsecured):**  
- The website (`URL`) uses the HTTP protocol and is not secured. A Proxy Rewrite was created with URL: `URL`.

2. **HTTP Protocol (Proxy Not Working):**  
- The website (`URL`) uses the HTTP protocol and is not secure, but the Proxy is not working anymore. Therefore, a JSRW was created with the tracking parameter `?_vsrefdom=XXXXX` and properly configured.

3. **HTTPS Protocol (Secured):**  
- The website (`URL`) uses the HTTPS protocol, which is secure. Therefore, a JSRW was created with the tracking parameter `?_vsrefdom=XXXX` and properly configured.

4. **JSRW Verification:**  
- Checked the JSRW with tracking parameter `?_vsrefdom=XXXX`; it was properly configured, and the BTN (`BTN`) was changed to the CTN (`CTN`).

5. **Proxy Rewrite Verification:**  
- Checked the Proxy Rewrite with URL: `URL` and it was properly configured, changing the BTN (`BTN`) to the CTN (`CTN`).

---

### **GTM (Google Tag Manager) Setup**

1. **GTM Container Creation:**  
- The GTM container was created with ID: `AAAA` and the Marchex tag was properly set up with all 3 triggers.

2. **GTM Container Verification:**  
- Checked the GTM container with ID: `AAAA` and the Marchex tag was properly set up with all 3 triggers.

3. **GTM Naming Convention Update:**  
- Checked the GTM container with ID: `AAAA` and the Marchex tag didn't have the best naming convention. Therefore, it was changed from 'Custom HTML' to 'Marchex - JSRW'.

4. **GTM Script Installation:**  
- GTM Script was installed on the website (`URL`).  
- GTM Script was found installed on the website (`URL`).  
- GTM Script was not installed on the website (`URL`) because it's not from YP.  
- GTM Script was not found installed on the website (`URL`), and we couldn't install it because it's not a YP Website.

5. **Customer Instructions:**  
- Please tell the customer to follow the instructions on the following YP site: [https://www.yp-pj-conversions.ca/?GTM=](https://www.yp-pj-conversions.ca/?GTM=)

---

### **Deactivation & Removal**

1. **CTN Deactivation:**  
- As requested, we deactivated and removed the CTN from both Marchex and Skai.

2. **JSRW Deletion:**  
- JSRW with tracking parameter `?_vsrefdom=XXXX` was deleted.

3. **Marchex Tag Pausing:**  
- The Marchex tag of the GTM container with ID: `ZZZ` was paused.

4. **Proxy Rewrite Deletion:**  
- The Proxy Rewrite with URL: `AAAAA` was deleted.

---

### **Ongoing Issues**

1. **Marchex CTN Swap Issue:**  
- Ongoing issue with Marchex; CTN won't swap even after troubleshooting. Waiting for an update from the Marchex team.

---

### **Additional Info**

- **Time Zones:**  
- BC = Pacific  
- ON-QC = Eastern  
- NS/NB = Atlantic  
- MB = Central  
- AB / NT / YT = Mountain  
- NL = Newfoundland

---

### **Broken Links & JS Issues**

1. **Broken Link (Working):**  
- We evaluated the URL with a validation tool, and `XXXXX` is working fine as of now.

2. **Broken Link (Not Working):**  
- We evaluated the URL with a validation tool, and `XXXX` is not working. Therefore, it was replaced with `XXXX`.

3. **Broken JS (Fixed):**  
- After changing the website's protocol from HTTP to HTTPS, the call tracking started working correctly.

4. **SSL Security Error:**  
- The website `XXX` is showing an SSL Security Error. After bypassing the message, the website is fully working.

---

### **JavaScript Snippet to Block US Calls**

```js
!AL & !AK & !AZ & !AR & !CA & !CO & !CT & !DE & !DC & !FL & !GA & !HI & !ID & !IL & !IN & !IA & !KS & !KY & !LA & !ME & !MD & !MA & !MI & !MN & !MS & !MO & !MT & !NE & !NV & !NH & !NJ & !NM & !NY & !NC & !ND & !OH & !OK & !OR & !PA & !RI & !SC & !SD & !TN & !TX & !UT & !VT & !VA & !WA & !WV & !WI & !WY
```

