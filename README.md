# Captcha Generator 
A simple image captcha generator

### Prerequisites
1. Install the dependencies by executing the following command if needed:
   	pip install tk
	pip install Pillow
	pip install captcha

### Explaination

1. **Import Libraries**: The code imports necessary libraries for generating CAPTCHA images (`random`, `string`, `PIL`, `captcha`, and `tkinter`).

2. **`createImage` Function**: This function generates a new CAPTCHA image by creating a random alphanumeric string and using the `ImageCaptcha` class to generate and display the image.

3. **`check` Function**: This function compares the user’s input with the generated CAPTCHA string. It displays "Verified" if the input matches, or "Incorrect!" if it doesn't and generates a new CAPTCHA.

4. **Tkinter Window Setup**: The main part of the code initializes a Tkinter window with widgets like a text entry box, reload button, and submit button.

5. **Event Binding**: The submit button and the `Return` key are bound to the `check` function, allowing the user to submit the CAPTCHA using both methods.

6. **Looping GUI**: The program enters a loop with `root.mainloop()` to keep the window active until it is closed by the user.
