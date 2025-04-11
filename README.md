Accessible Web App with Voice & Keyboard Navigation

This project is an accessibility-focused, multi-page web application built using HTML, CSS, and JavaScript. It allows users to navigate through pages using keyboard arrows, voice commands, or the custom voice trigger "Hey Ash".

Features
	•	Keyboard Navigation: Use ArrowRight and ArrowLeft keys to navigate between pages.
	•	Voice Control:
	•	Say "Hey Ash" to activate the assistant.
	•	Use "Go to page X" (e.g., "Go to page 2") to switch to a specific page.
	•	Contact Form: A simple form to collect user name, email, and message.
	•	ARIA Accessibility: Uses role and aria-labelledby attributes for screen reader support.
	•	Dynamic Alerts: Announces page transitions and interactions.

Pages
	1.	Page 1 – Welcome screen
	2.	Page 2 – Informational section
	3.	Page 3 – More content
	4.	Contact Us – Includes a contact form

Technologies Used
	•	HTML5
	•	CSS3
	•	JavaScript
	•	Speech Recognition API (WebKit-based)

How to Use
	1.	Open index.html in a supported browser (preferably Chrome for Web Speech API support).
	2.	Use Arrow keys or voice commands like:
	•	"Hey Ash"
	•	"Go to page 1", "Go to page 2", etc.
	3.	Fill out the Contact Us form and submit.

Accessibility Notes
	•	Voice feedback and keyboard control ensure a more inclusive experience.
	•	Proper use of semantic elements and ARIA attributes help screen reader users.
	•	Form elements are fully accessible and labeled.

Browser Compatibility
	•	Fully supported in Google Chrome
	•	Other browsers may not support webkitSpeechRecognition

Future Improvements
	•	Add visual indicators for active voice commands
	•	Support additional languages for voice recognition
	•	Add form submission handling and validations

License

This project is open-source under the MIT License.
