# FoodGie 🥘 - NewHacks 2025 Best Use of Gemini API Winner Project 

A website designed to help you organize your fridge!

Snap a photo of your fridge, Get nutrition info, recipes, and expiry tracking. 

**Built using Python, Flask, and Gemini API**

Supports camera functionality for easy photo capture, links, and file uploads.

FoodGie turns a single photo of your groceries or fridge into a structured inventory: what you bought, how much, its nutrition, and when it'll expire. From there it recommends recipes that use up what's expiring soonest, and tracks the calories you actually eat.

**Project structure**
'''
Website/
  app.py                    Flask app & routes (analyze, recipes, fridge, consume)
  data.py                   JSONBin read/write/consume logic
  templates/
    index.html               Photo capture / food analyzer
    fridge.html               Inventory dashboard
    recipes.html               Recipe generator & results
    settings.html               Calorie goals, reminders, log
  static/
    css/                      Styles
    js/
      camera.js                Camera capture
      analyzer.js               Photo analysis UI
      recipes.js                 Recipe generation UI
      calorie-tracker.js         Calorie logging
  requirements.txt
  ''' 
