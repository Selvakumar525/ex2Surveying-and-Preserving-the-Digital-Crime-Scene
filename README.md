# Surveying and Preserving the Digital Crime Scene
```
Name : Selva Kumar A
Reg.no: 212222110042
```
## **Aim:**
Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  
![a1](https://github.com/user-attachments/assets/37bee9e9-9b13-4bae-9892-784e74b195a3)


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  
![a2](https://github.com/user-attachments/assets/e5001737-b330-4ce5-b286-197f22abdc59)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**
![a3](https://github.com/user-attachments/assets/8dbbc674-63aa-4f8d-8276-a78e65bc2cc9)


- Select **Local Disk** → **next** 

![a4](https://github.com/user-attachments/assets/ebe48aa5-a3b6-4e07-b78e-608b2dbc0dba)


- Select Disk → **Choose the VHD drive (`Drive1`)**
![a5](https://github.com/user-attachments/assets/5c6ffd5c-d990-420d-ae2b-a52af20aab7f)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  
![a6](https://github.com/user-attachments/assets/72dc62b8-4a97-4c5b-b4bb-ea24990f2166)

![a7](https://github.com/user-attachments/assets/99744793-055e-4c59-9eb9-04a4d0423070)


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  
![a8](https://github.com/user-attachments/assets/24844e98-cbe4-4231-a2ac-68f86f7667c1)


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files

![f1](https://github.com/user-attachments/assets/7ff6e886-f0c1-40df-b66c-6483633ea171)

### Folder after deleting the files

![a9](https://github.com/user-attachments/assets/358d8f10-0660-45f2-b955-f86b768c906b)

### Folder after extracting the deleted images using autopsy

![a10](https://github.com/user-attachments/assets/ae532a78-8f93-499a-9e95-d0378f7b5c22)

## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
