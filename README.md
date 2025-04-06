# CloudPigeon - Securing your cloud files

## What is CloudPigeon?
CloudPigeon is a powerful file encryption tool designed to protect your privacy and secure your sensitive data when using cloud storage services. In today's digital world, cloud storage has become an essential part of our lives, but it also raises concerns about data privacy and security.

## Why Use CloudPigeon?
- **Enhanced Privacy:** Your files are encrypted before uploading to cloud storage, ensuring that no one - including cloud provider employees - can access your sensitive information.
- **Military-Grade Security:** Uses AES-256 encryption, the same standard used by governments and financial institutions.
- **Complete Control:** You hold the encryption key (passphrase), meaning only you can decrypt and access your files.
- **Perfect for Sensitive Data:** Ideal for protecting:
  - Personal documents and photos
  - Financial records and tax documents
  - Business confidential information
  - Medical records and legal documents
  - Intellectual property and research data
- **Cloud Storage Compatibility:** Works with any cloud storage service (Dropbox, Google Drive, OneDrive, etc.).
- **User-Friendly:** Simple interface for encrypting and decrypting files with just a few clicks.
- **Batch Processing:** Encrypt or decrypt multiple files at once to save time.

## How It Works
CloudPigeon encrypts your files locally on your computer before they are uploaded to cloud storage. When encrypted, your files are transformed into unreadable data that can only be decrypted with your personal passphrase. This means that even if someone gains unauthorized access to your cloud storage, they cannot read your files without knowing your passphrase.

## Folder Configuration
The ciphertext folder needs to be pointed to a local folder that is mapped to your cloud storage. For example, if you use OneDrive, the ciphertext folder should be your OneDrive folder or any subfolder within it. The plaintext folder, on the other hand, should be a local folder that is outside of your mapped cloud storage folder. This ensures that your original files remain secure and are not directly exposed to the cloud.

## Best Practices
- Use a strong, unique passphrase that you can remember.
- Keep your passphrase secure and never share it.
- Maintain a backup of your encrypted files.
- Consider encrypting files in batches based on their security requirements.
- Regularly verify that you can decrypt important files.

## Initial Setup
1. Click the **Config** button to set up your default folders:
   - **Default Plaintext Folder:** Where your original files are stored (outside of cloud storage).
   - **Default Ciphertext Folder:** Where encrypted files will be saved (inside your cloud storage folder).
   - **Default Passphrase:** Optional master password for encryption/decryption.

## Encrypting Files
1. Navigate to your files in the left panel (Plaintext).
2. Select one or multiple files you want to encrypt.
3. Enter your passphrase (or use the saved default).
4. Click the **Encrypt** button.
5. Encrypted files will be saved in your ciphertext folder with a `.cp` extension.

## Decrypting Files
1. Navigate to your encrypted files in the right panel (Ciphertext).
2. Select one or multiple `.cp` files you want to decrypt.
3. Enter the same passphrase used for encryption.
4. Click the **Decrypt** button.
5. Decrypted files will be saved in your plaintext folder.

## File Management
- Right-click on files to:
  - Rename files.
  - Delete files.
- Use the **Delete** key to quickly remove selected files.
- Use the eye button (👁️) to show/hide the passphrase.

## Important Security Notes
- Always remember your passphrase - it cannot be recovered!
- Keep your encrypted files (`.cp`) safe.
- The same passphrase must be used for encryption and decryption.
- Files are encrypted using AES-256 encryption, a globally trusted standard.
- Encryption is performed locally on your computer for maximum security.
- No data is transmitted to any external servers during encryption/decryption.

## Screenshots
![image](https://github.com/user-attachments/assets/83f30de5-32b0-46e5-b83f-7020625a5738)
![image](https://github.com/user-attachments/assets/4888a60f-ec8c-4161-b41d-0d25900f4a48)
