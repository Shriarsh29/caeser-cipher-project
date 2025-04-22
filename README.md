# caeser-cipher-project
Caesar Cipher 🔐
A simple and interactive Python implementation of the classic Caesar Cipher — one of the oldest and easiest encryption techniques. This tool lets users encrypt or decrypt messages by shifting letters through the alphabet.

📌 Features
Encrypt (encode) or decrypt (decode) messages

Preserves non-alphabet characters like spaces and punctuation

Supports lowercase letters

Modular shift logic with wrap-around

Interactive CLI interface

Option to run the program repeatedly

💡 How It Works
The Caesar Cipher works by shifting each letter in the message by a certain number of places in the alphabet. For decryption, the same shift is applied in reverse.

Example (shift = 3):

yaml
Copy
Edit
Original : hello world
Encoded  : khoor zruog
🛠️ How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/caesar-cipher.git
cd caesar-cipher
Run the script:

bash
Copy
Edit
python caeser_cipher.py
Follow the prompts:

python
Copy
Edit
Type 'encode' to encrypt, type 'decode' to decrypt:
Type your message:
Type the shift number:
✅ Example Output
python
Copy
Edit
Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello world
Type the shift number:
5
Here is the encoded result: mjqqt btwqi
📁 Files
caeser_cipher.py: Main Python script with Caesar Cipher logic and user interaction

README.md: Project documentation

LICENSE: MIT License file

.gitignore: Ignores Python cache and IDE files

📜 License

This project is licensed under the MIT License. See the LICENSE file for more information.
