# Soundness-pubKey-setup

![image](https://github.com/user-attachments/assets/0a9d608e-4e40-4db4-bd5e-997972bdf176)


Soundness Layer is a decentralized verification layer ensuring fast, scalable, and cross-chain data verification. Built on Walrus for data availability and Sui for sequencing, it leverages restaking for security.

- Updates your system packages
- Installs Rust
- Installs `soundnessup` (Soundness Layer installer)
- Sets up your shell environment
- Generates a Soundness key (`my-key`)

## Waitlist:

1. Visit: https://soundness.xyz/
   -  Submit your email

## Generate Your Key here:

1. Go to Codespace: https://github.com/codespaces
   - Create Account
   - Click **BLANK** Use this template

![image](https://github.com/user-attachments/assets/83450bdf-5243-4e46-9099-841d99685b46)

2. Paste the following Command:
```
sudo apt update && sudo apt upgrade -y && \
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y && \
source $HOME/.cargo/env && \
rustc --version && cargo --version && \
echo 'source $HOME/.cargo/env' >> ~/.bashrc && source ~/.bashrc && \
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash && \
source ~/.bashrc && \
soundnessup install && \
soundnessup update && \
soundness-cli generate-key --name my-key
```
   - Don't forget to save your Mnemonic Phrase and Pub-Key

![image](https://github.com/user-attachments/assets/aa480a38-c10e-4403-b967-87c32300ba69)

## Join Discord:

1. Join here: https://discord.gg/MRDQmzWeWP
   - Go to **#soundness-cockpit** Channel ▶️ Submit your **Pub-Key**.
   - Format: `/access gUOAfnrUH1dmddsadas29GZW/pOGPuBl+kT9w=`
  
![image](https://github.com/user-attachments/assets/d43d5ef2-150c-4ea1-8ce1-22a1bba77c89)

2. Link your Telegram and Twitter:
- For **Telegram** Type: `/link_telegram <Your_Username>`
- For **Twitter** Type: `/x_login <Your_Twitter_Profile>`
- View your linked X account, whitelist key, and Telegram account Type: `/info`

  ![image](https://github.com/user-attachments/assets/d1aa9656-17da-4f62-89d2-561661dd67cc)

Official Guide: https://github.com/SoundnessLabs/soundness-layer/tree/main/soundness-cli
