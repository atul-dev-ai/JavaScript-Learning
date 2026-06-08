# Hello World in JavaScript

## কী শিখলে:
JavaScript এ আউটপুট দেখার মূলত কয়েকটি উপায় আছে:

1. **console.log()** - এটি সবচেয়ে বেশি ব্যবহৃত হয়। মূলত ব্রাউজারের কনসোল (Console) এ আউটপুট দেখার জন্য এটি ব্যবহার করা হয়, যা ডিবাগিং বা কোড চেক করার জন্য কাজে লাগে।
   ```javascript
   console.log("Hello World!");
   ```

2. **alert()** - এটি ব্রাউজারে একটি পপ-আপ মেসেজ বা অ্যালার্ট বক্স হিসেবে আউটপুট দেখায়।
   ```javascript
   alert("Hello World!");
   ```

3. **document.write()** - এটি সরাসরি HTML ডকুমেন্টের ভেতর টেক্সট প্রিন্ট করে দেয়। (তবে রিয়েল-লাইফ প্রজেক্টে এটি খুব একটা ব্যবহার করা হয় না)
   ```javascript
   document.write("Hello World!");
   ```

4. **DOM Manipulation (innerHTML / textContent)** - HTML এর কোনো নির্দিষ্ট উপাদানের (যেমন `<div>` বা `<p>`) ভেতর টেক্সট বসানোর জন্য।
   ```javascript
   document.getElementById("myId").innerHTML = "Hello World!";
   ```

## প্র্যাকটিস:
* আপনার `script.js` ফাইলে `console.log("Hello Bangladesh")` লিখে ব্রাউজারের কনসোল (F12 > Console) ওপেন করে চেক করুন।
* একটি `alert("Welcome to JS!")` পপ-আপ তৈরি করুন।