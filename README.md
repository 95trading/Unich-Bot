# 🚀 UNICH Bot - Airdrop 500M Token [v1.1]

## 🔥 Update v1.1:
✅ Bug fixes.

## 📖 How to Use the Bot:

### 1️⃣ Access the project:
👉 [Unich Airdrop](https://unich.com/en/airdrop/sign-up?ref=6IXTHN)

### 2️⃣ Register and Login:
- Sign up for an account and log in using the referral code: **6IXTHN**

### 3️⃣ Get the Token:
- After logging in successfully, press `F12` to open **Developer Tools**
- Go to the **Console** tab and enter the following code to extract the token:

```javascript
function getCookie(name) {
    return document.cookie
        .split('; ')
        .find(row => row.startsWith(name + '='))
        ?.split('=')[1] || null;
}
let token = getCookie("AIRDROP_token");
console.log("Copy Token:", token);
```

### 4️⃣ Save the Token:
- Copy the extracted token and paste it into `dulieu.txt`
- Each token should be on a separate line.

### 5️⃣ Run the Bot:
- Execute `bot.exe`

## 🌐 Proxy Format:
- Each proxy should be listed on a separate line in `proxy.txt`
```
http://user:pass@host:port
```

## 📌 Download the Latest Bot:
👉 [BOT v1.1 Download](https://drive.google.com/file/d/1M7634qjO41cinN4hadzMjT1fuQRhhh5w/view?usp=sharing)
