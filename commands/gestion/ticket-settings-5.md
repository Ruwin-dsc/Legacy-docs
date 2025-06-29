# Captcha

**Description:** This feature is useful for preventing malicious users in 02Auth.

When you use the `captcha` command, you will access the configuration panel. Don't worry—it's easy to set up!

<figure><img src="../../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

## ⚙️ Configuration Options

### 🔹 Button Function

* **Button** : This allows you to enable or disable the captcha system.

{% hint style="warning" %}
🔴 Red = Disabled | 🟢Green = Enabled
{% endhint %}



### 🔹 Select Menu Configuration

* "**Select Channel.**" : Here you can set the channel where the captcha will be sent.

<figure><img src="../../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure>

* "**Role given before passing the captcha**" : Here, you can assign a role that will be granted while the user completes the captcha.

<figure><img src="../../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure>

* "**Role given after passing the captcha**" : Here, you can integrate the role that will be assigned after the user completes the captcha

<figure><img src="../../.gitbook/assets/image (64).png" alt=""><figcaption></figcaption></figure>

* "**Select an option**" : Define an option for the captcha (Letter, Number, Special Characters)

<figure><img src="../../.gitbook/assets/image (65).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (66).png" alt=""><figcaption></figcaption></figure>

Une fois votre configuration rempli veuillez l'activer avec le bouton dans la première catégorie de [<mark style="background-color:blue;">**Configuration Options**</mark>](ticket-settings-5.md#button-function)

<figure><img src="../../.gitbook/assets/image (67).png" alt=""><figcaption></figcaption></figure>

Once the configuration is activated, your new members will receive a code to enter in the designated channel.

<figure><img src="../../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
Ensure there are no role conflicts between the autorole and the captcha system. If you activate the captcha, please disable the autorole if it is active.
{% endhint %}
