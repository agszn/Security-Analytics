# Security Analytics Platform

This project is a comprehensive web application built with Django, SQLite, and machine learning, focusing on security analytics, including cryptography, steganography, phishing detection, and secure file handling. The platform provides tools for encryption, decryption, steganography, URL phishing detection, and interactive blog functionalities for sharing and discussing security topics.

## Features

### 1. Cryptography & Encryption
The platform supports encryption and decryption of files and messages using cryptographic algorithms to ensure data security.

- **Screenshot**:  
  ![Cryptography & Encryption](assert/images/cryptography_encryption.png)

### 2. Steganography & Decryption
Users can hide data within images using steganography, and the system also provides the option to decrypt hidden data.

- **Screenshot**:  
  ![Steganography](assert/images/stegnography.png)
  ![Decryption](assert/images/CryptoStegnographyDecryption.png)

### 3. URL Phishing Detection
The platform includes a machine learning-based tool to detect phishing URLs. Users can input URLs, and the system will analyze and predict if the URL is malicious or safe.

- **Screenshot**:  
  ![URL Phishing Detection](assert/images/url_phishing_detection.png)
  ![Phishing Detection Result](assert/images/Url_phishing_result.png)

### 4. Blog Functionality
Users can create blog posts related to security topics, download posts, get notifications from authors, and share, like, or comment on posts. This feature promotes discussions and knowledge sharing in the community.

- **Screenshots**:  
  ![Blog Page](assert/images/blog.png)
  ![Download & Notify Author](assert/images/Blog_download_notify_author.png)
  ![Reshare, Like, Comment](assert/images/reshare_like_comment_.png)

### 5. Profile Management
Users can manage their profile, track their activities, and customize their settings.

- **Screenshot**:  
  ![Profile Page](assert/images/profile.png)

### 6. About Page
The application also provides an about page that details the project’s purpose, features, and security techniques used.

- **Screenshot**:  
  ![About Page](assert/images/about.png)

### 7. Home Page
The homepage provides an overview of the platform’s features and allows users to navigate easily through the application.

- **Screenshot**:  
  ![Home Page](assert/images/index.png)

## Technologies Used

- **Django**: Web framework for backend development.
- **SQLite**: Database for storing user information, blog posts, and security data.
- **Machine Learning**: Used for phishing detection and other security analytics.
- **Cryptography**: Implements encryption and decryption algorithms for secure data handling.

## Installation

Follow these steps to set up and run the project locally:

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   ```

2. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run database migrations:**

   ```bash
   python manage.py migrate
   ```

4. **Start the Django development server:**

   ```bash
   python manage.py runserver
   ```

5. **Access the application:**

   Open your browser and go to `http://127.0.0.1:8000/` to use the platform.

## Usage

- **Encryption/Decryption**: Encrypt sensitive data or decrypt previously encrypted files/messages.
- **Steganography**: Hide information inside images and retrieve it later using decryption methods.
- **Phishing Detection**: Input URLs for analysis and get real-time feedback on potential phishing risks.
- **Blog Interaction**: Create security-related blog posts, comment, like, share, and download posts. Authors receive notifications when their posts are interacted with.
- **Profile Management**: Keep track of your activities, edit your profile, and manage security settings.

## Screenshots

- **About Page**  
  ![About Page](assert/images/about.png)

- **Blog Page**  
  ![Blog Page](assert/images/blog.png)

- **Download & Notify Author**  
  ![Blog Download & Notify Author](assert/images/Blog_download_notify_author.png)

- **Cryptography & Encryption**  
  ![Cryptography & Encryption](assert/images/cryptography_encryption.png)

- **Steganography Decryption**  
  ![Steganography Decryption](assert/images/CryptoStegnographyDecryption.png)

- **Decryption**  
  ![Decryption](assert/images/decryption.png)

- **Homepage**  
  ![Home Page](assert/images/index.png)

- **Profile Page**  
  ![Profile Page](assert/images/profile.png)

- **Reshare, Like, Comment**  
  ![Reshare, Like, Comment](assert/images/reshare_like_comment_.png)

- **Steganography**  
  ![Steganography](assert/images/stegnography.png)

- **URL Phishing Detection**  
  ![URL Phishing Detection](assert/images/url_phishing_detection.png)

- **Phishing Detection Result**  
  ![Phishing Detection Result](assert/images/Url_phishing_result.png)

