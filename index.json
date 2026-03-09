{
  "project_name": "SNAPVAULT",
  "project_type": "Secure File Sharing Platform",
  "description": "SNAPVAULT is a mobile responsive secure file sharing web platform where users can upload sensitive files, encrypt them, and share them securely using a secret key. Files can only be opened with the correct username and secret key.",

  "technology_stack": {
    "frontend": ["HTML5", "CSS3", "JavaScript"],
    "database": "SQL (MySQL or SQLite)",
    "security": ["AES Encryption", "Secret Key Authentication"]
  },

  "ui_requirements": {
    "design": "Modern UI",
    "responsive": true,
    "mobile_support": true,
    "framework_optional": "Bootstrap or Flexbox/Grid"
  },

  "features": {
    "user_authentication": [
      "User registration",
      "User login with username and password",
      "Session management"
    ],

    "file_management": [
      "Upload file",
      "Read file information",
      "Update file details",
      "Modify file metadata",
      "Delete file",
      "Share file with another user"
    ],

    "security_features": [
      "Encrypt sensitive files before storing",
      "Generate secret key for file access",
      "Sender shares secret key with receiver",
      "Receiver must enter username and secret key to open file",
      "Secret key validation before file access"
    ],

    "sharing_features": [
      "Generate secure share link",
      "Allow sender to assign receiver username",
      "Option to create one secret key for related files between sender and receiver",
      "Share multiple files using the same secret key"
    ]
  },

  "workflow": [
    "User registers and logs into SNAPVAULT",
    "Sender uploads a file",
    "System encrypts the file before saving",
    "System generates a secret key",
    "Sender shares the secret key with the receiver",
    "Receiver enters username and secret key",
    "System verifies credentials",
    "Receiver can open or download the file",
    "Sender can update, modify, or delete the file"
  ],

  "database_schema": {
    "users": {
      "user_id": "INT PRIMARY KEY AUTO_INCREMENT",
      "username": "VARCHAR(100)",
      "password": "VARCHAR(255)"
    },

    "files": {
      "file_id": "INT PRIMARY KEY AUTO_INCREMENT",
      "file_name": "VARCHAR(255)",
      "file_path": "TEXT",
      "encrypted": "BOOLEAN",
      "owner_id": "INT",
      "secret_key": "VARCHAR(255)",
      "created_at": "DATETIME"
    },

    "file_sharing": {
      "share_id": "INT PRIMARY KEY AUTO_INCREMENT",
      "file_id": "INT",
      "sender_id": "INT",
      "receiver_username": "VARCHAR(100)",
      "secret_key": "VARCHAR(255)"
    }
  },

  "frontend_pages": [
    "Home Page",
    "Register Page",
    "Login Page",
    "User Dashboard",
    "Upload File Page",
    "File Manager Page",
    "Share File Page",
    "Secure File Access Page"
  ],

  "extra_features": [
    "Mobile responsive layout",
    "Copy secret key button",
    "File access logs",
    "Search and filter files"
  ]
}
