# ⚖️ BMI Comparison

## 📌 About
This JavaScript script calculates and compares the Body Mass Index (BMI) of two individuals, Mark and John, and logs the result to the console.

## 📂 Project Structure
- `script.js` - The main JavaScript file containing the BMI calculation and comparison logic.

## 📝 Code
```javascript
const massMark = 78;
const heightMark = 1.69;
const massJohn = 92;
const heightJohn = 1.95;

const BMIMark = massMark / (heightMark * heightMark);
const BMIJohn = massJohn / (heightJohn * heightJohn);

if (BMIMark > BMIJohn) {
    console.log(`Mark's BMI ${BMIMark} is higher than John's! (${BMIJohn})`);
} else {
    console.log(`John's BMI ${BMIJohn} is higher than Mark's! (${BMIMark})`);
}
```

## 🚀 Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Navigate to the project folder:
   ```sh
   cd your-repo-name
   ```
3. Run the script using Node.js:
   ```sh
   node script.js
   ```

## 🔥 Output Example
```
John's BMI 24.19 is higher than Mark's! (27.31)
```

## 💡 Features
- Uses JavaScript to calculate BMI using the standard formula: `BMI = mass / height²`
- Compares two BMI values and logs the result dynamically
- Uses template literals for cleaner output formatting

## 👨‍💻 Author
**Goga Gabelia** - Software Developer

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
