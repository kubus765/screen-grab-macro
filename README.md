Python script designed to automate the testing process by searching for specific images on the screen and typing predefined text when those images are found. This script utilizes the PyAutoGUI library for screen interaction and the screeninfo library to get monitor dimensions.

Features:
Image Recognition: Uses PyAutoGUI's image recognition capabilities to locate specified images on the screen.
Text Typing: Types predefined text when target images are found.
Custom Confidence Threshold: Allows setting a custom confidence threshold for image recognition.
Multi-Threading: Utilizes threading to concurrently search for multiple images.
Usage:
Image Paths: Set the paths for the target images (image_path_1 and image_path_2) and corresponding text to type (text_to_type_1 and text_to_type_2).
Customization: Adjust the custom confidence threshold (custom_confidence) and sleep times as needed.
Run: Execute the script, and it will continuously search for the specified images on the primary monitor.
Dependencies:
PyAutoGUI: For GUI automation.
Screeninfo: For retrieving monitor information.
Instructions:
Install the required dependencies using pip install -r requirements.txt.
Run the script
Notes:
Make sure the target images are distinct and recognizable on the screen.
Adjust the screen regions and confidence threshold according to your specific use case.
License:
This project is licensed under the MIT License.

Feel free to contribute, report issues, or suggest improvements!
