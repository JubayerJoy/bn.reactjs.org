---
title: একটি সহজ কম্পোনেন্ট
order: 0
domid: hello-example
---

React কম্পোনেন্ট একটি `render()` মেথড তৈরি করে যা ইনপুট ডেটা নেয় এবং কী দেখাতে হবে তা প্রদান করে। এই উদাহরণটি JSX নামে একটি XML এর মত সিনট্যাক্স ব্যবহার করেছে। কম্পোনেন্টটে যেই ইনপুট ডেটাই দেওয়া হয়, তা `this.props` এর মাধ্যমে `render()` মেথডের ভেতরে ব্যবহার করা যায়।

**JSX একটি অপশনাল সিনট্যাক্স এবং এটি React এ ব্যবহার করা আবশ্যিক নয়।** JSX এর কম্পাইলেশন ধাপে, যেই জাভাস্ক্রিপ্ট তৈরি হয়,  [Babel REPL](babel://es5-syntax-example) ব্যবহার করে আপনি তা পর্যবেক্ষণ করতে পারেন।