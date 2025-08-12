This Python script creates a portfolio website using the Flask framework. It defines three routes:
/ → Loads index.html (Home page)
/about → Loads about.html (About page)
/contact → Loads contact.html (Contact page)
The templates folder is specified so Flask knows where to find the HTML files, and the static folder is for CSS or other static assets.
The threading module is used to run the Flask app in a separate thread, allowing it to execute alongside other processes without blocking the main program. 
The app is run in debug mode for easy testing, with use_reloader=False to prevent duplicate server starts when using threads.
