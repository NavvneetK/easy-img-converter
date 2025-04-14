# 📸 Bulk Image Converter CLI Tool

A lightweight and handy **Command Line Interface (CLI)** tool that lets you **convert, resize, and compress** multiple images in bulk — straight from your terminal!

No need to open heavy editors or manual converters — let the command line do the magic. 🪄

---

## 🚀 Features

✅ Convert images to formats like **JPEG, PNG, WEBP**  
✅ Resize images to specific dimensions (width × height)  
✅ Compress images to reduce file size  
✅ Works on folders with hundreds of images  
✅ Super fast and easy to use!

---

## 🛠️ Installation

You can install this tool using `pip` (after it's published on PyPI):

```bash
pip install bulkimgconvert


Argument	Description	                    Example
--input	    Path to input folder	        --input ./images
--output	Path to output folder	        --output ./converted
--format	Output format: JPEG, PNG, WEBP	--format JPEG
--resize	Resize width and height	        --resize 800 600
--quality	Compression quality (10–100)	--quality 70

💡 Usage
Basic Conversion:
bulkimgconvert --input ./input_folder --output ./output_folder --format JPEG


Resize & Convert:
bulkimgconvert --input ./input_folder --output ./output_folder --format PNG --resize 800 600

Add Compression:
bulkimgconvert --input ./input_folder --output ./output_folder --format WEBP --quality 70

📦 Example Use Case
Let’s say you’re a developer or designer who receives 100s of product images in different formats. Instead of manually converting each one for your website — you run:

bulkimgconvert --input ./raw --output ./web --format WEBP --resize 600 400 --quality 80

Boom 💥 — your entire folder is ready in seconds!


❤️ Contributions
Pull requests, ideas, and suggestions are welcome! Let’s make image conversion faster and simpler for everyone.