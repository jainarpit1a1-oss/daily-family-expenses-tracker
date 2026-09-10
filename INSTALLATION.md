# Installation Guide - Family Expenses Tracker

## Prerequisites
- ServiceNow PDI (Personal Developer Instance)
- System Administrator role
- XML Update Set file

## Step-by-Step Installation

### Step 1: Download the Update Set
- Download `family_expenses_tracker_v1.0.xml` from this repository
- Save it to your computer

### Step 2: Import to Your ServiceNow Instance

1. Open your **ServiceNow PDI** instance
2. Search for **"System Update Sets"** in the search bar
3. Click on **"List"** option
4. Click **"Import XML file"** button
5. Click **"Choose File"** and select `family_expenses_tracker_v1.0.xml`
6. Click **"Upload"** button

### Step 3: Preview the Update Set
1. The system will show you all changes that will be applied
2. Review the changes carefully
3. Look for any errors (shown in red)
4. Click **"Preview Update Set"** to continue

### Step 4: Commit the Update Set
1. If preview looks good, click **"Commit Update Set"** button
2. Wait for the system to process (usually 10-30 seconds)
3. You should see a success message: "Update Set committed successfully"

### Step 5: Access Your Application
1. In the ServiceNow search bar, search for: **"Family Expenses Tracker"**
2. Click on the result to open your application
3. Start adding family expenses!

## Troubleshooting

### Issue: "File Upload Failed"
**Solution**: 
- Make sure you're logged in as an Admin
- Ensure the XML file is not corrupted
- Try uploading again

### Issue: "Update Set Commit Failed"
**Solution**:
- Check for naming conflicts
- Ensure you're on a clean PDI instance
- Check the error log in ServiceNow

### Issue: "Application doesn't appear in search"
**Solution**:
- Clear your browser cache (Ctrl+Shift+Delete)
- Refresh the ServiceNow page (Ctrl+R)
- Log out and log back in

## Support
If you encounter any issues, check the official [ServiceNow Documentation](https://docs.servicenow.com)

---

**Enjoy using Family Expenses Tracker! 🎉**
