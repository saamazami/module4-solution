(function (window) {
  var byeSpeaker = {};
  var speakWord = "Good Bye";

  byeSpeaker.speak = function (name) {
    console.log(speakWord + " " + name);
  };

  window.byeSpeaker = byeSpeaker;

})(window);
Key points addressed:

The entire content is wrapped inside an IIFE (Immediately Invoked Function Expression), as per Step 6.
An object named byeSpeaker is created, and the speak method is attached to it, fulfilling Step 7 and Step 8.
The byeSpeaker object is exposed to the global scope using the window object, as specified in Step 9.

---
---

(function (window) {
  var helloSpeaker = {};
  var speakWord = "Hello";

  helloSpeaker.speak = function (name) {
    console.log(speakWord + " " + name);
  };

  window.helloSpeaker = helloSpeaker;

})(window);
Key points addressed:

The entire content is wrapped inside an IIFE (Immediately Invoked Function Expression), as per Step 2.
An object named helloSpeaker is created, and the speak method is attached to it, fulfilling Step 3 and Step 4.
The helloSpeaker object is exposed to the global scope using the window object, as specified in Step 5.