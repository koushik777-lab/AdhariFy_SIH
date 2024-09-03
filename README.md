# 🌟 **AdhariFy** 🌟

![AdhariFy Logo](static/images/logo.png)

🚀 **AdhariFy** is an innovative liveness detection platform, developed as part of the prestigious **Smart India Hackathon (SIH)** by Team **DarkBeast**. Our mission is to revolutionize identity verification, making it more secure, reliable, and user-friendly. Say goodbye to spoofing and hello to AdhariFy! 🥳

## 🔥 **Why AdhariFy?**

In an era where digital security is essential, **AdhariFy** shines as a game-changer. Here’s why:

- **🛡️ Enhanced Security:** Our liveness detection technology ensures that only real, live users can authenticate their identity, dramatically reducing the risk of fraud.
- **🧠 Intelligent Detection:** Leveraging cutting-edge machine learning algorithms, AdhariFy can accurately distinguish between live users and spoofing attempts.
- **⚡ Fast & Efficient:** The platform offers real-time liveness detection, ensuring a seamless user experience without compromising on security.
- **🌐 Versatile Applications:** AdhariFy is adaptable across multiple domains, making it the ideal solution for various industries.

## 🚀 **Use Cases & Practical Applications**

### 1. **E-Governance** 🏛️
   - **Aadhaar Verification**: Ensure the person verifying their identity via Aadhaar is genuinely present, minimizing identity theft risks.
   - **🗳️ Online Voting Systems**: Enable secure, tamper-proof online voting, ensuring the voter is physically present.

### 2. **Banking & Finance** 💳
   - **📲 Digital Onboarding**: Verify the identity of new customers during digital onboarding to prevent fraudulent account creation.
   - **💸 Transaction Authentication**: Add an extra layer of security to financial transactions by verifying the user’s presence during high-value operations.

### 3. **Healthcare** 🏥
   - **🩺 Telemedicine**: Ensure that the person consulting with a healthcare provider online is indeed the patient, protecting sensitive medical data.
   - **🧾 Insurance Claims**: Authenticate the presence of a claimant during video-based insurance claims processing.

### 4. **E-Commerce** 🛒
   - **🛍️ Secure Purchases**: Protect online shoppers by verifying the user’s identity during high-value purchases or account changes.

## 🔧 **Project Structure**

Here's a quick overview of the project structure:


```
AdhariFy/
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── liveness.js
│   └── images/
│       ├── logo.png
│       └── aadhar.svg
│
├── templates/
│   ├── index.html
│   └── about.html
│
├── app.py
├── README.md
└── requirements.txt
```

## 🚀 **Features**

- **Real-time Face Detection** 🧑‍💻
- **Liveness Detection** using facial landmarks 👁️👁️
- **Simple and Intuitive UI** 🎨
- **Secure and Fast** 🛡️⚡

## 🎯 **How It Works**

1. 📸 The application captures real-time video from the webcam.
2. 🕵️‍♂️ It uses OpenCV and Haar cascades to detect faces and eyes in the video feed.
3. ✅ A liveness check is performed by ensuring both eyes are detected in the frame.
4. 💚 If liveness is detected, a green bounding box with "Liveness Detected" is shown. Otherwise, it indicates "Spoof Detected" with a red bounding box.

## 🌟 **Contribution**

🤝 Contributions are welcome! Feel free to open an issue or submit a pull request.

## 💬 **Contact**

For any inquiries or suggestions, feel free to reach out:

- 📧 **Email**: [koushiksarkar741777@gmail.com](mailto:koushiksarkar741777@gmail.com)
- 🐙 **GitHub**: [https://github.com/koushik777-lab/AdhariFy_SIH](https://github.com/koushik777-lab/AdhariFy_SIH)

*Happy Coding!* 😄🚀
