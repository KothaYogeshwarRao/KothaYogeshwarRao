def encrypt(text, shift):
    encrypted_text = ""
    for char in text:
        if char.isalpha():
            shift_amount = shift % 26
            shifted_char = ord(char) + shift_amount
            if char.islower():
                if shifted_char > ord('z'):
                    shifted_char -= 26
                encrypted_text += chr(shifted_char)
            elif char.isupper():
                if shifted_char > ord('Z'):
                    shifted_char -= 26
                encrypted_text += chr(shifted_char)
        else:
            encrypted_text += char
    return encrypted_text

def decrypt(text, shift):
    return encrypt(text, -shift)

def main():
    while True:
        choice = input("Do you want to (e)ncrypt or (d)ecrypt a message? (q to quit): ").lower()
        if choice == 'q':
            break
        if choice in ('e', 'd'):
            message = input("Enter your message: ")
            shift = int(input("Enter the shift value: "))
            if choice == 'e':
                result = encrypt(message, shift)
                print(f"Encrypted message: {result}")
            else:
                result = decrypt(message, shift)
                print(f"Decrypted message: {result}")
        else:
            print("Invalid choice. Please enter 'e' to encrypt, 'd' to decrypt, or 'q' to quit.")

if _name_ == "_main_":
    main()- 👋 Hi, I’m @KothaYogeshwarRao
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
KothaYogeshwarRao/KothaYogeshwarRao is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
