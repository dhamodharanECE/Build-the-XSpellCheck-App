# 📝 XSpellCheck – Real-Time Spell Checker in React

**XSpellCheck** is a **React-based real-time spell-checking application** that identifies and corrects commonly misspelled words as the user types.  
It leverages a **custom dictionary** to suggest accurate corrections for typos and ensures improved writing quality for user-inputted text.  

This project demonstrates the conversion of a **class component** implementation into a **functional component** using React Hooks (`useState`, `useEffect`), maintaining the same UI and working behavior.

---

## 🚀 **Features**

✅ **Real-Time Spell Checking** – Detects misspelled words as the user types in a textarea.  
✅ **Auto Correction Suggestion** – Displays the correct spelling for the first detected error.  
✅ **Custom Dictionary** – Uses a pre-defined set of common misspellings.  
✅ **Case-Insensitive Detection** – Works with both lowercase and uppercase inputs.  
✅ **Sentence Handling** – Checks full sentences and flags only the **first incorrect word**.  
✅ **Responsive & Clean UI** – Matches the provided class-based UI design.  
✅ **No Suggestion on Empty Input** – Automatically hides suggestions when text is cleared.

---

## 🧠 **Custom Dictionary**

The spell-check logic uses the following dictionary for corrections:

javascript
const customDictionary = {
  teh: "the",
  wrok: "work",
  fot: "for",
  exampl: "example"
};
💡 How It Works
The user types text into a <textarea>.

The app continuously monitors input changes using React Hooks.

It splits the text into words and checks each one (case-insensitively) against the custom dictionary.

If a misspelled word is found:

Displays the first detected correction in the format:

arduino
Copy code
Did you mean: <correct-word>?
If all words are correct or the text is empty, no suggestion message is shown.

🧩 Implementation Requirements
Must use Functional Components (not class-based).

Use React Hooks for state and effect management.

Maintain exact UI and working as the original class-based version.

Must use a <textarea> for text input.

# Clone the repository:

bash
Copy code
https://github.com/dhamodharanECE/Build-the-XSpellCheck-App.git
Navigate to the project folder:

bash
Copy code
cd xspellcheck
Install dependencies:

bash
Copy code
npm install
Start the application:

bash
Copy code
npm start
Open your browser and visit:

arduino
Copy code
http://localhost:3000
🧾 Example Scenarios
Input	Output
wrok	Did you mean: work?
For exampl this wrok	Did you mean: example?
The wrok is done	Did you mean: work?
teh cat	Did you mean: the?
(Empty Text)	No suggestion displayed

🧠 Learning Outcomes
Converting React Class Components → Functional Components

Using React Hooks (useState, useEffect) for managing state and logic

Handling real-time input validation

Implementing case-insensitive string comparison

Building clean and accessible UI in React

# Picture Overview:

1. Hero Section:

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/a2482210-f816-490a-a522-047797ff969d" />

2.Error Handling:

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/d1749937-2fed-41c2-83d4-0be72a821a64" />

1. Deployment Link:
2. 
    ```bash
    https://build-the-x-spell-check-app-git-0953d7-dhamodharan-ss-projects.vercel.app?_vercel_share=A4Ej16ciiodyODHvVtSaVGrf4yBwrft6
    
👨‍💻 Author
Dhamodharan S
Full Stack Web Developer | Passionate about React and UI Development

📧 Email: dhamodharans206@gmail.com
🌐 https://github.com/dhamodharanECE/

📝 License
This project is open source and available under the MIT License.
