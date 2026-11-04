# Saudades

A private photo album for the cast and crew of *For It May Be Better Than Nothing at All*.

Every photo and all album data in this repository are encrypted (AES-256-GCM, key derived from the
album password with PBKDF2-SHA256). The page decrypts them in the visitor's browser after the password
is entered. Nothing readable is stored here.
