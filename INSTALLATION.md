# Installation
### Step 1: Create New Dashboard
1. In Home Assistant, go to Settings > Dashboards and press the "Add Dashboard" button on the bottom right. Choose "New Dashboard from scratch" Choose a name and the URL for the dashboard. We will use ``echo-show`` as URL. <div align="center"><img src="img/dashboard_creation.png" /></div>

2. Open the dashboard click on "Edit Dashboard" in the top right corner. Tick the "Start with an empty dashboard" option and press "Take Control"
   Note that this step might not appear depending on how you set-up new dashboards to appear".
 <div align="center"><img src="img/take_control.png" /></div>

3. Edit the view "Home".<div align="center"><img src="img/edit_home.png" /></div> Rename it if you want, and choose "1" as the URL.<div align="center"><img src="img/home_view.png" /></div>

4. You can now create as many views as you like, the only important thing is that you give them unique numbers as URLs just like in the previous step. You can also do this later if you want.

5. Now we're finished in Home Assistant. Open the [Alexa Developer Console](https://developer.amazon.com/alexa/console/ask) and sign-in with the Amazon account that is linked to your Echo Show.
# Create an Alexa Smart Home Skill

<div align="center"><img src="img/23.png" /></div>

### Step 6: Click on Create Skill
Navigate to [Alexa Developer Console](https://developer.amazon.com/alexa/console/ask) and click on **Create Skill**.

<div align="center"><img src="img/24.png" /></div>

### Step 7: Configure Skill Basics
- **Name your skill** *(Only used in the console)*.
- Choose your **Primary Locale** (Country), if necessary.

<div align="center"><img src="img/25.png" /></div>

### Step 8: Select Skill Type
- Choose the **Smart Home** radio button.
- Choose the **Custom** pane.
- Toggle **Sync Locales** to ON.

<div align="center"><img src="img/26.png" /></div>

### Step 9: Hosting Options
- Choose **Alexa-hosted (Python)**.
- Select the hosted region closest to you.

Click **Next**.

<div align="center"><img src="img/27.png" /></div>

### Step 10: Skill Template
- Choose **Start from scratch**.

<div align="center"><img src="img/28.png" /></div>

### Step 11: Review and Create
- Review settings and click **Create**.
- Wait a few minutes for the skill to initialize.

### Step 12: Skill Dashboard
Once initialized, you'll see the skill dashboard.

<div align="center"><img src="img/29.png" /></div>

### Step 13: Set Invocation Name
- Under "Building your skill" on the right, select **1. Invocation Name**.
- Enter a name for your skill. *(e.g., "dashboard viewer")*

Don’t forget to hit **Save**.

<div align="center"><img src="img/30.png" /></div>

### Step 14: Menu Overview
Expand the menu on the left. It should look like this:

<div align="center"><img src="img/31.png" /></div>

### Step 15: Delete Default Intent
- Delete the **Hello World** intent.
- Confirm deletion.

<div align="center"><img src="img/32.png" /></div>

### Step 16: Create a Custom Intent
- Enter **OpenPageIntent**.
- Click on **Create custom intent**.

<div align="center"><img src="img/33.png" /></div>

### Step 17: Add Intent Slots
- Under the intent, add a slot named **page**.
- Click the **+** under Intent Slots and select **Amazon Number**.

<div align="center"><img src="img/34.png" /></div>

### Step 18: Add Sample Utterances
 - Enter the following under sample utterances:
