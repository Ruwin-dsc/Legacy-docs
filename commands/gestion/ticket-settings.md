# Ticket settings

**Description:** This feature allows you to set up a ticketing system where server members can request assistance.

When you use the `ticket-settings` command, you will access the configuration panel. Don't worry—it's easy to set up!

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-20 à 21.56.35.png" alt=""><figcaption><p>Ticket settings panel</p></figcaption></figure>

## ⚙️ Configuration Options

### 🔹 Role Restrictions

* **First Select Menu**: Allows only members with the selected role to create tickets.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-20 à 21.59.06.png" alt=""><figcaption><p>Allowed roles</p></figcaption></figure>

* **Second Select Menu**: Prevents members with the selected role from creating tickets.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-20 à 22.01.16.png" alt=""><figcaption><p>Restricted roles</p></figcaption></figure>

{% hint style="warning" %}
💡 **Tip:** If you can't find your role, simply type its name in the Select Menu.
{% endhint %}

### 🔹 Button Settings

* **Button 1**: Defines whether the ticket system will use **buttons** or a **select menu**.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-20 à 22.04.11.png" alt=""><figcaption><p>Choose button or select menu</p></figcaption></figure>

* **Button 2**: Toggles the **Claim** button. When enabled, support team members can claim tickets, making them visible only to the ticket creator, the support member, and administrators.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-20 à 22.06.53.png" alt=""><figcaption><p>Claim button setting</p></figcaption></figure>

* **Button 3**: Enables or disables **ticket transcripts**, which save a full log of the conversation.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-20 à 22.09.34.png" alt=""><figcaption><p>Transcript settings</p></figcaption></figure>

{% hint style="warning" %}
🔴 **Red = Disabled** | 🟢 **Green = Enabled**
{% endhint %}

### 🔹 Additional Ticket Options

* **Button 5**: Adds more options to the ticket panel, such as extra buttons or select menu choices.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-20 à 22.21.39.png" alt=""><figcaption><p>Add more options</p></figcaption></figure>

Clicking this button opens a **new panel** with additional settings:

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-20 à 22.22.27.png" alt=""><figcaption><p>Advanced ticket options</p></figcaption></figure>

#### 🎛️ Advanced Settings

* **First Select Menu**: Defines which roles will be **mentioned** when a ticket is created.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-20 à 22.27.55.png" alt=""><figcaption><p>Roles to mention</p></figcaption></figure>

* **Second Select Menu**: Defines which roles have **access** to the ticket (e.g., support team roles).

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-20 à 22.29.32.png" alt=""><figcaption><p>Support team access</p></figcaption></figure>

* **Third Select Menu**: Specifies the **category** where ticket channels will be created.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-20 à 22.30.36.png" alt=""><figcaption><p>Ticket category</p></figcaption></figure>

{% hint style="warning" %}
💡 **Tip:** If you can’t find your role or category, simply type its name in the Select Menu.
{% endhint %}

### 🔹 Button Functions

* **Button 1**: Sets an emoji for the button or select menu.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-21 à 12.29.17.png" alt=""><figcaption><p>Set emoji</p></figcaption></figure>

* **Button 2**: Defines the **text** of the button or select menu option.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-21 à 12.30.27.png" alt=""><figcaption><p>Set button text</p></figcaption></figure>

* **Button 3**: Sets the **name of the ticket channel**. Use `!variables ticket` to insert dynamic values like ticket number, username, etc.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-21 à 12.36.02.png" alt=""><figcaption><p>Set ticket channel name</p></figcaption></figure>

* **Button 4**: Defines the **message** displayed when a ticket is opened. This guides the user on what to do next.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-21 à 12.42.21.png" alt=""><figcaption><p>Set ticket opening message</p></figcaption></figure>

* **Button 5**: Saves the current configuration.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-21 à 12.48.05.png" alt=""><figcaption><p>Save settings</p></figcaption></figure>

* **Button 6**: Returns to the main settings menu.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-21 à 12.49.47.png" alt=""><figcaption><p>Return to main menu</p></figcaption></figure>

## 📌 Deploying the Ticket Panel

Once your settings are configured, it’s time to **install your ticket panel**!

1. Create a message where the ticket buttons or select menu will be placed.
   * Use the `!embed` or `!say` command.
   * Copy the message **ID**.
2. Click the **4th button** in the main settings menu (see below).
   * A pop-up will appear asking for the message ID.
   * Once confirmed, your ticket panel will be updated!

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-21 à 13.12.33.png" alt=""><figcaption><p>Deploying the ticket panel</p></figcaption></figure>

### 🗑️ Resetting Options

* **Button 6**: Deletes all your configured ticket options.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-02-21 à 13.13.14.png" alt=""><figcaption><p>Reset ticket settings</p></figcaption></figure>

Your **ticket system** is now ready to go! 🚀
