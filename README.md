# Image Uploader App

## Overview

The Image Uploader App is a React application that allows users to upload images, view their details, and manage themes. The app features a simple interface for dragging and dropping or selecting images, previewing them, and displaying detailed information about the uploaded image.

## Features

- Upload images with a file size limit of 1MB.
- Preview images before uploading.
- View details of the uploaded image including size, dimensions, and format.
- Copy the image URL to the clipboard.
- Toggle between light and dark themes.

## Prerequisites

- [Node.js](https://nodejs.org/) (v16 or later)
- [npm](https://www.npmjs.com/get-npm) (comes with Node.js)

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/image-uploader-app.git
cd image-uploader-app
```

### 2. Install Dependencies
```bash
npm install
```
### 3. Set Up Cloudinary Variables

Replace your_cloud_name and your_upload_preset with your actual Cloudinary Cloud Name and Upload Preset in the ImageUploader.jsx file .


#### To obtain these values:

#### Cloud Name: Log in to your Cloudinary account, and you’ll find it in the top right corner of your dashboard.
#### Upload Preset: Create one in the Cloudinary dashboard under the Upload Presets section.

### 4. Run the Development Server
npm run dev
The application will be available at http://localhost:5173.

### 5. Build the Project
To build the project for production, run:
npm run build
The production build will be created in the dist directory.

### 6. Preview the Build
To preview the production build locally, run:

npm run preview


## Usage

### 1.Upload Image:
- Drag and drop an image file onto the designated area or click to select a file.
- The app will display a preview of the image before uploading.
- Click "Upload Image" to upload the image.
  
  ### 2.View Image Details:
- After the image is uploaded, you will be redirected to the Image Details page.
- The page displays information such as the image name, size, dimensions, format, and URL.
  
  ### 3.Copy Image URL:
- Click the "Copy URL" button to copy the image URL to your clipboard (publicly accessible).
  
  ### 4.Toggle Theme:
- Click the sun/moon icon in the navbar to switch between light and dark themes.
 


## Cloudinary Configuration

 To integrate Cloudinary, follow these steps:

### 1.Create a Cloudinary Account:
- Sign up at Cloudinary's website.

### 2.Obtain Cloudinary Credentials:
- Cloud Name: Find it in your Cloudinary Dashboard.
- Upload Preset: Create one under the Upload Presets section in your Cloudinary settings.

### 3.Configure Environment Variables:
-Add your Cloudinary Cloud Name and Upload Preset to the .env file as described in the "Set Up Environment Variables" section.

### 4.Update Your Application Code:
- Ensure the ImageUploader component in src/components/ImageUploader.jsx uses these environment variables in the upload URL.

  
## Dependencies
This project uses the following dependencies:

- axios
- cloudinary
- react
- react-dom
- react-dropzone
- react-router-dom
- sass
- tailwindcss
- vite

## Screenshots



## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Cloudinary for providing a simple image upload service.
Vite for the fast build tool.

 
 
