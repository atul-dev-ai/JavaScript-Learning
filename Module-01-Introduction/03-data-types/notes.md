# JavaScript Data Types

## কী শিখলে:
ভেরিয়েবলে আমরা কী ধরনের ডেটা রাখছি, তার উপর ভিত্তি করে ডেটা টাইপ নির্ধারণ করা হয়। জাভাস্ক্রিপ্টে মূলত দুই ধরনের ডেটা টাইপ আছে:

### 1. Primitive Data Types (প্রাইমিটিভ ডেটা টাইপ)
* **String**: টেক্সট বা অক্ষর সংরক্ষণের জন্য। (কোটেশনের ভেতরে রাখতে হয় `""` বা `''`)
  ```javascript
  let name = "Atul";
  let greeting = 'Hello';
  ```
* **Number**: পূর্ণসংখ্যা বা দশমিক সংখ্যা সংরক্ষণের জন্য।
  ```javascript
  let age = 25;
  let price = 99.99;
  ```
* **Boolean**: এটি শুধু দুটি মান নিতে পারে- `true` (সত্য) অথবা `false` (মিথ্যা)।
  ```javascript
  let isStudent = true;
  let isMarried = false;
  ```
* **Undefined**: ভেরিয়েবল ডিক্লেয়ার করা হয়েছে কিন্তু কোনো মান দেওয়া হয়নি।
  ```javascript
  let x;
  console.log(x); // আউটপুট: undefined
  ```
* **Null**: ভেরিয়েবলের মান ইচ্ছাকৃতভাবে "কিছুই না" বা "ফাঁকা" করে রাখার জন্য।
  ```javascript
  let currentJob = null;
  ```

### 2. Non-Primitive Data Types (নন-প্রাইমিটিভ/রেফারেন্স ডেটা টাইপ)
* **Object**: একসাথে অনেকগুলো প্রপার্টি (Key-Value) সংরক্ষণের জন্য।
  ```javascript
  let person = { name: "Rahim", age: 30 };
  ```
* **Array**: একটি ভেরিয়েবলে একসাথে অনেকগুলো ডেটা সিরিয়াল অনুযায়ী সংরক্ষণের জন্য।
  ```javascript
  let colors = ["Red", "Green", "Blue"];
  ```

*নোট: কোনো ডেটার টাইপ জানতে আমরা `typeof` অপারেটর ব্যবহার করতে পারি।*
```javascript
console.log(typeof "Hello"); // "string"
console.log(typeof 10); // "number"
```

## প্র্যাকটিস:
* String, Number এবং Boolean টাইপের কয়েকটি ভেরিয়েবল ডিক্লেয়ার করুন।
* `typeof` ব্যবহার করে সেই ভেরিয়েবলগুলোর ডেটা টাইপ কনসোলে প্রিন্ট করে দেখুন।
