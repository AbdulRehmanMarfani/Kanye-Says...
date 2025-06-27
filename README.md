
---

# Kanye Says 🎤

A fun and interactive Kanye West quote generator built using Python and the Tkinter GUI library. This app uses the [kanye.rest](https://api.kanye.rest) API to fetch and display random Kanye quotes in a stylish window.

---

## Features 💬

* **Random Kanye Quotes**: Fetches real-time quotes from Kanye West with each click.
* **Clean GUI**: Minimalistic and visually appealing layout using canvas and images.
* **One-Click Simplicity**: Press the Kanye button to instantly get a new quote.
* **Error Handling**: Raises an error if the API request fails (to be extended with user-facing error messages).

---

## Requirements 🛠️

* Python 3.6+
* `requests` library (`pip install requests`)
* Active Internet Connection

---

## Files Included 📂

1. **`main.py`**: Main script containing the GUI logic and API integration.
2. **`background.png`**: The background image displayed behind the quote.
3. **`kanye.png`**: The Kanye button image that fetches a new quote when clicked.

---

## How to Run It? ▶️

1. Clone or download the repository.
2. Make sure you have `requests` installed:

   ```bash
   pip install requests
   ```
3. Place all the files (`main.py`, `background.png`, `kanye.png`) in the same directory.
4. Run the script:

   ```bash
   python main.py
   ```

---

## Screenshot 📸

![image](https://github.com/user-attachments/assets/fe1878a2-9508-4465-bd66-2316e4746f74)


---

## Developer Note 🧑‍💻

> This was the **first time I ever worked with an API**. Before creating this project, I didn’t even know what an API was. Through this app, I learned how to:
>
> * Fetch data using the `requests` library
> * Work with REST APIs and handle JSON
> * Integrate dynamic data into a Tkinter GUI
>
> It was a turning point in my development journey — from writing static scripts to building interactive applications that pull real-time data from the web.

---

## Future Enhancements 🚀

* Show a loading message or disable the button while fetching quotes
* Add a "Copy to Clipboard" button for easy sharing
* Store favorite quotes locally
* Add animation or change facial expressions for Kanye dynamically

---

## Credits ✨

* **Programming**: Abdul Rehman Marfani
* **Libraries Used**: Tkinter, Requests
* **API Used**: [kanye.rest](https://api.kanye.rest)

---

Enjoy Kanye’s wisdom, one quote at a time 😎

---
