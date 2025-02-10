Step 1: Create a GCP Account
1. Go to [Google Cloud Console](https://console.cloud.google.com/).
2. Sign in with a Google account or create a new one.
3. Set up billing (Google offers free credits for new users).

## Step 2: Create a Compute Engine Instance
1. Navigate to the **Compute Engine** section.
2. Click **Create Instance**.
3. Set the following parameters:
   - Name: `gcp-test-instance`
   - Region: Choose a nearby region
   - Machine Type: `e2-micro` (suitable for testing)
   - Boot Disk: Ubuntu 22.04 LTS
   - Check `Allow HTTP traffic` and `Allow HTTPS traffic` if needed for web traffic.

4. Click **Create**.
5. A sample python file is already deployed.