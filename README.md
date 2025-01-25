# Image Trimmer and Resizer

**Image Trimmer and Resizer** is a web-based tool designed to simplify image preparation for article writers, especially those working in WordPress environments. The application ensures that uploaded images are resized to a width of **825 pixels** while maintaining the aspect ratio, and optimizes the output image to be under **100 KB** in size. This ensures that the images are web-friendly and adhere to common publishing requirements.

---

## Features

- **Drag and Drop**: Quickly upload images by dragging and dropping them into the interface.
- **Clipboard Support**: Paste copied images directly into the application using `CTRL + V`.
- **Manual Upload**: Option to upload images manually from your local system.
- **Automated Resizing**: Automatically resizes images to a width of 825 pixels, adjusting the height proportionally.
- **Size Optimization**: Ensures the output image size is always less than 100 KB.
- **User-Friendly Interface**: Clean and simple interface for quick processing.

---

## Purpose

This application is built with article writers in mind. It streamlines the process of preparing images for online publishing by ensuring:

- Standardized width for WordPress or other CMS platforms.
- Reduced image size for faster website performance.
- Hassle-free image upload and processing.

---

## Getting Started

### Prerequisites

- **Node.js** (v14.x or later)
- **npm** (v6.x or later) or **yarn**

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Mark-Maverick/image-trimmer-and-resizer.git
   cd image-trimmer-and-resizer
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

   Or using yarn:

   ```bash
   yarn install
   ```

### Running the Application

Start the development server:

```bash
npm run dev
```

Or using yarn:

```bash
yarn dev
```

Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to access the application.

---

## Usage

1. **Drag and Drop**: Drop an image file into the designated area on the interface.
2. **Paste from Clipboard**: Copy an image and press `CTRL + V` to upload it.
3. **Manual Upload**: Click the upload button to select an image from your device.
4. **Automatic Processing**: The application will resize and optimize the image.
5. **Download**: Save the processed image to your device.

---

## Technologies Used

- **Next.js**: Framework for server-side rendering and static site generation.
- **Tailwind CSS**: Utility-first CSS framework for modern styling.
- **Image Processing Libraries**: Handles resizing and optimization.

---

## Contributing

Contributions are welcome! If you have suggestions for features or improvements, feel free to open an issue or submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

