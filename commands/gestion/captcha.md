# Captcha

**Description:** This feature is useful for preventing malicious users in 02Auth.

When you use the `captcha` command, you will access the configuration panel. Don't worry—it's easy to set up!

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

## ⚙️ Configuration Options

### 🔹 Button Function

* **Button 1**: Enables or disables the captcha system.

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

### 🔹 Button Function (Captcha Validation)

* **Button 1:** The button below the embed will open a Discord form where your members must enter the **code** shown in the image (<mark style="color:green;">Green Box</mark>) on the button (<mark style="color:red;">Red Box</mark>).

<figure><img src="../../.gitbook/assets/https___files.gitbook.com_v0_b_gitbook-x-prod.appspot.com_o_spaces_2F4oU7ecFpX37mgJVGoqeR_2Fuploads_2F9sWN9OAnCVAhdhpfsVFA_2Fimage.avif" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
<mark style="color:red;">**Red = Disabled**</mark>**&#x20;|&#x20;**<mark style="color:green;">**Green = Enabled**</mark>
{% endhint %}

### 🔹 Select Menu Configuration

* "**Select Channel**" : You can set the captcha code sending for new arrivals in this option

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

Once the channel is set up and the **system is active**, each new arrival will receive a code to enter in this room.

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

* "**Role given before passing the captcha**" : Define a role that will be automatically assigned when a person joins the server (_e.g., a "waiting captcha" role that has no access to any channels on the server except those for the captcha_).

<figure><img src="../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

* "**Role given after passing the captcha**" : Define a role to be assigned to individuals who have completed the captcha. (For example, a member role that grants access to public server channels and information)

<figure><img src="../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Be careful to avoid conflicts between the captcha and the auto-role. For instance, if both your captcha and auto-role are active, we strongly recommend deactivating at least one. Otherwise, the bot might grant both captcha and full server access simultaneously.
{% endhint %}

* "**Select an option**": Define the code for the captcha (With letters, numbers, or special characters). You can create multiple ones.

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

The code will therefore be composed of the options you have defined.

<figure><img src="../../.gitbook/assets/image (21).png" alt=""><figcaption><p>example</p></figcaption></figure>
