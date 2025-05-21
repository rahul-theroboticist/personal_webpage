---
title: "Contact"
date: 2024-05-19
type: "landing"

design:
  # Section spacing
  spacing: '2rem'

sections:
  - block: markdown
    content: |
      <form name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field" class="max-w-xl mx-auto p-6 bg-white rounded-md shadow-md">
        <input type="hidden" name="form-name" value="contact">
        <p class="hidden">
          <label>Don’t fill this out if you're human: <input name="bot-field" /></label>
        </p>
        <div class="mb-4">
          <label for="name" class="block text-gray-700 font-bold mb-2">Name</label>
          <input type="text" id="name" name="name" required class="w-full px-3 py-2 border border-gray-300 rounded-md">
        </div>
        <div class="mb-4">
          <label for="email" class="block text-gray-700 font-bold mb-2">Email</label>
          <input type="email" id="email" name="email" required class="w-full px-3 py-2 border border-gray-300 rounded-md">
        </div>
        <div class="mb-4">
          <label for="message" class="block text-gray-700 font-bold mb-2">Message</label>
          <textarea id="message" name="message" rows="5" required class="w-full px-3 py-2 border border-gray-300 rounded-md"></textarea>
        </div>
        <button type="submit" class="bg-blue-500 text-white px-4 py-2 rounded-md hover:bg-blue-600">Send</button>
      </form>
---
