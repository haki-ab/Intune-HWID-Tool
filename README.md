# 🖥️ AutopilotHashGen

**AutopilotHashGen** is a zero-dependency PowerShell-based tool that extracts the Windows Autopilot Hardware Hash (HWID) with a single click — no typing, no admin headaches.

> ✅ Designed for IT Admins deploying devices to Microsoft Intune  
> ✅ Works from any folder — Desktop, USB, Downloads  
> ✅ No installation, no prerequisites  
> ✅ Outputs a `.csv` file ready for import into Intune

---

## 📦 What's Inside

- `gethash.ps1` – PowerShell script that invokes `Get-WindowsAutopilotInfo` safely
- `gethash.bat` – One-click launcher for non-technical users
- ✅ Output: `AutoPilotHWID.csv`

---

## ⚙️ How to Use

1. **Download & Extract**
2. **Double-click `gethash.bat`**
3. The script will:
   - Elevate privileges if needed
   - Invoke the PowerShell module
   - Export the hardware hash to `AutoPilotHWID.csv`
4. ✅ You're done! Upload the `.csv` file to Microsoft Endpoint Manager (Intune).

---

## 📌 Notes

- Works on **Windows 10/11 Pro, Education, or Enterprise**
- The device **does not need to be joined to Intune**
- Requires **local admin** rights

---

## 🧠 Why This Exists

Manual HWID collection is error-prone and confusing for end users.  
This project was built to solve that pain — clean, fast, and foolproof.

---

## 🔒 Disclaimer

This script uses official Microsoft commands only.  
No third-party binaries or telemetry are involved.

---

## 📄 License

MIT License — use freely, modify, or redistribute.

---

