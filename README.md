# **Client-Side Text Extractor from Images**

### **Overview**

This is a simple, single-page web application that extracts text from images directly in the user's web browser. It's built with HTML, Tailwind CSS, and JavaScript, and it leverages the Tesseract.js library for client-side Optical Character Recognition (OCR), which means no external API key or server-side processing is required.

### **Features**

- **Clean, responsive UI:** Provides a user-friendly interface for effortless image uploads.

- **Client-Side Processing:** All text extraction happens locally on the user's device, ensuring privacy and removing dependencies on external services.

- **No API Key Required**: The application is completely self-contained and does not require any API keys to function.

- **Real-Time Feedback:** Includes a loading spinner and a dedicated output area to show the extraction progress and results.

- **Zero-dependency single-file app**: All code is self-contained in a single HTML file, making it easy to share, use, or deploy.

### **How to Use****
Clone the repository and open the **text_extraction.html** file in your web browser.

Click the "Choose an Image" button to select an image from your device.

The application will automatically process the image and display the extracted text in the output area below.

### **Technologies Used**

- **HTML5:** For the page structure.

- **Tailwind CSS**: For modern and responsive styling.

- **JavaScript:** For handling user interactions and running the OCR library.

- **Tesseract.js:** The core OCR engine that powers the text extraction.

### **Setup for Development**

To run this project locally, simply clone the repository and open the text_extraction_local.html file in your browser. There is no need for any further setup or configuration.

```
git clone [https://github.com/your-username/ai-text-extractor.git](https://github.com/your-username/ai-text-extractor.git)
cd ai-text-extractor
```

### **Contributing**


Contributions are welcome! If you have suggestions or improvements, please feel free to open an issue or submit a pull request
