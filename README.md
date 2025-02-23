Visual Product Search Engine

Overview-
This project is a Visual Product Search Engine that allows users to capture a screenshot of a product, recognize objects within the image using Google Cloud Vision API, and search for similar products on Flipkart, Myntra, and Amazon. The results are then displayed in a Tkinter-based GUI.

Features-
Screen Capture: Capture a screenshot using pyscreenshot.
Image Recognition: Use Google Cloud Vision API to extract relevant keywords from the image.
Web Scraping: Scrape product data from Flipkart, Myntra, and Amazon.
Search Aggregation: Display aggregated search results in a user-friendly Tkinter window.
System Tray Integration: A PyQt5-based system tray icon to easily trigger screen capture.



Usage-
Run the application:
python main.py
A system tray icon will appear.
Click on the tray icon and select "Capture Screen".
The application will capture the screen, analyze the image, and search for similar products online.
The search results will be displayed in a GUI window.



Troubleshooting-
If the application fails to detect objects in an image, ensure your Google Cloud Vision API credentials are correctly set up.
If a website structure changes, update the web scraping logic accordingly.
If Myntra search fails due to timeout, retry the request after a few minutes.



Future Enhancements-
Improve search accuracy with additional e-commerce platforms.
Implement caching for repeated searches to improve performance.
Add a GUI-based keyword refinement feature.










![Image](https://github.com/user-attachments/assets/2f9d106a-7fda-480d-9bd4-7d457709754d)
![Image](https://github.com/user-attachments/assets/be06451b-2132-446e-9cfe-16dcbe35a080)
![Image](https://github.com/user-attachments/assets/ee56d503-3fb4-4d9f-b2ff-ceaf71265229)
![Image](https://github.com/user-attachments/assets/9e9fbc5b-4796-4a0c-bef5-15403af5ecc1)
![Image](https://github.com/user-attachments/assets/bacf3d9e-a4fb-4de5-ba3e-565959a1534d)
