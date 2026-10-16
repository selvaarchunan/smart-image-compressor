# Smart Image Compressor

A free, browser based image compression tool for reducing image file sizes, resizing images and converting between popular image formats. Process images locally in your browser without uploading them to a compression server.

## Features

- **Multiple image uploads:** Select or drag and drop multiple images.
- **Adjustable compression quality:** Set image quality from 10% to 100%.
- **Image resizing:** Choose original resolution, 2560px, 1920px, 1280px or 800px maximum dimensions.
- **Format conversion:** Keep the original format or convert images to WebP, JPEG or PNG.
- **Individual downloads:** Download compressed images separately.
- **ZIP downloads:** Download multiple compressed images in a single ZIP archive.
- **Storage savings:** View original sizes, compressed sizes and estimated percentage savings.
- **Image previews:** Preview processed images before downloading.
- **Privacy focused processing:** Image processing takes place in the browser without uploading image files to a backend server.
- **Responsive interface:** Use the tool on desktop and mobile browsers.

## Demo

Download or clone this repository and open `image-compressor.html` in a modern web browser.

A hosted demo can be added here after deploying the project to GitHub Pages.

## Getting Started

### Option 1: Download the project

1. Open this repository on GitHub.
2. Select **Code** and choose **Download ZIP**.
3. Extract the downloaded archive.
4. Open `image-compressor.html` in your browser.
5. Upload your images and adjust the compression settings.

### Option 2: Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/smart-image-compressor.git
cd smart-image-compressor
```

Open `image-compressor.html` in your browser.

Replace `YOUR-USERNAME` with your GitHub username.

## How to Use

1. Open the image compressor.
2. Upload images or drag and drop them into the upload area.
3. Adjust the quality setting.
4. Choose the maximum image dimensions.
5. Select the desired output format.
6. Download individual images or download all processed images as a ZIP file.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- HTML Canvas API
- Browser Image Bitmap API
- JSZip for ZIP archive creation
- Lucide icons

## Privacy

Image processing is performed locally in the browser. The application does not send uploaded image files to a dedicated image processing server.

The current HTML loads JSZip and Lucide from external CDNs, so an internet connection may be required to load those libraries. The image files themselves are processed locally.

## Limitations

- Compression results vary depending on the image format, dimensions and quality settings.
- The quality setting does not affect PNG compression in the same way it affects JPEG and WebP.
- Converting a transparent image to JPEG removes transparency.
- Browser memory and available device resources may limit the number or size of images processed at once.
- The current implementation does not include server-side processing or cloud storage.

## Contributing

Contributions, suggestions and bug reports are welcome.

1. Fork this repository.
2. Create a feature branch.
3. Make your changes.
4. Test the application in a modern browser.
5. Submit a pull request.

## Licence

This project is intended for open source distribution. Add a `LICENSE` file specifying your chosen licence before publishing it for reuse. The MIT Licence is one option if you want to permit broad reuse, modification and distribution.

## Author

Developed as a lightweight image optimisation tool using HTML, CSS and JavaScript.

If you find this project useful, consider starring the repository and sharing it with other developers.
