## 🧱 Network Setup Steps  

### Step 1: Add Devices
- 🏠 **Home Gateway**
- 💡 **IoT Devices** (e.g., Smart Fan, Smart Light)
- 💻 **Laptop** or 📱 **Smartphone** (for control)
  
![image](https://github.com/user-attachments/assets/ee802973-6b66-4ed3-9c3a-7aaa702a9ed4)

---

### Step 2: Connect IoT Devices to Gateway - Go to `Config > Wireless` on each IoT device - Set the **SSID** to match the Home Gateway’s SSID (case-sensitive) - Ensure **Power** is ON

![image](https://github.com/user-attachments/assets/b93f07ed-b4c5-4915-9da3-a06a6d90d611)


### Step 3: Connect Laptop to Gateway - Go to `Laptop > Config > Wireless0` - Set the **SSID** to the same as the Home Gateway - Ensure it gets an IP address (DHCP or static in the same range)

![image](https://github.com/user-attachments/assets/24a153de-a954-484f-b8b0-5bf5c2fcc469)



### Step 4: Link IoT Devices to Home Gateway - Go to `Config > IoT Server` on each IoT device - In **Server Address**, select **Home Gateway** from the dropdown  > This registers each IoT device with the Home Gateway controller.

![image](https://github.com/user-attachments/assets/4cd1cf6b-f6cd-48a0-8d0e-5cd0f0cc4e36)


### Step 5: Control IoT Devices from Laptop (Using IoT Monitor) 1. Click on the **Laptop** 2. Go to `Desktop > IoT Monitor`

![image](https://github.com/user-attachments/assets/f883c8bd-27f9-4a38-b969-798a8f7258c2)


3. Fill in the following:    - **IoT Server Address**: IP address of the Home Gateway (e.g., `192.168.25.1`)    - **Username**: `admin`    - **Password**: `admin` 4. Click **Login**
   
![image](https://github.com/user-attachments/assets/72981e94-b05d-4e80-83a3-30799767aed3)


### ✅ Confirmation: Devices Successfully Connected

After login, you'll see a list of IoT devices (like Fan and Light) that can be turned ON/OFF from the interface.

> 🟢 The network is now live and functional — IoT devices are connected, controlled, and fully operational.

> ![image](https://github.com/user-attachments/assets/8d985eff-0a09-4ce1-93ef-512446c6687e)

